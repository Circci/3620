# 3620
3620 Group Project

Jason Rangel and Miriam Lozneanu 

We decided to do the Gordon supercomputer.

  Gordon is a XSEDE cluster, and Appro and SDSC designed it. It is consisted of 1024 compute nodes and 64 I/O nodes. It supports the XSEDE core software stack. The XSEDE core software stack includes remote login remote computation.
  Gordon provides the compilers, but also, it uses the multiple MPI implementations such as OpenMPI. The best performance on Gordon is to use the Intel compilers and MVAPICH2. 
  Gordon uses the TORQUE Resource Manager to manage user jobs. If you use PBS, then TORQUE shares syntax and user interface. When you run in batch mode, you can access the compute nodes using the qsub command. 
Users have access to a high performance scratch file system. To have the highest levels of performance, capacity, and stability, the scratch files system should have routine purge. The users should be encouraged to monitor their usage and delete files.	
  In our topology, we have four compute nodes, one for networking and then one for parallel file sharing. You will be able to see if each node is ready and also if any of them have failed. It creates a link with type LAN. It generate the nodes. Then, it creates interfaces for each node.







Topology viewer:

In the topology viewer, there are 7 nodes. 




Validaiton Results 

