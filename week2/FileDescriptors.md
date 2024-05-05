1. Small non-negative integer which identifies a file to the kernel. 
2. The use of an integer value to represent a file helped build tools for file I/O, sockets, network I/O, IPC, etc.
3. Basic Idea: ![file_descriptors.png](./images/file_descriptors.png)
4. ![](descriptor_table.png)
5. ![](forking.png)
6. read(2)
	1. ![](read(2).png)
7. write(2)
	1. ![](write(2).png)
8. lseek(2)
	1. ![](lseek(2).png)
	2. ![](lseek_usage.png)
	3. Seeking is not possible for all file descriptors
	4. 