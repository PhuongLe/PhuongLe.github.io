Thank a UBC project, and we have tried to develop a distributed file system that helped me have a deep understanding of the fundamentals of a distributed system. Although it is just a small project,
 we have put a lot of effort into keeping the architecture simple and elegant and applied optimizations wherever possible (e.g., caching) with end-to-end automation tests. 

This distributed file system is designed to conduct basic file handling operations such as file write, read, delete and update. 
The system utilizes “Master Server” to handle the operations, and the master is selected through the leader election process. 
Also, the system can tolerate multiple node failures without impacting file availability and file handling functionalities. 
It is designed so that every file is written onto 3 nodes asynchronous via an active replication process to maintain 3 replicas of the file in case of node failure. 
The put and read operation make use of Simple Write Quorum wherein R = W = 2. 
The failure detection mechanism is deployed such that every node sends and receives heartbeat messages from 2 successor and 2 predecessor nodes in a ring topology.  

The source code and more details of the design and implementation can be found [here](https://github.com/PhuongLe/simple-distributed-file-system).

