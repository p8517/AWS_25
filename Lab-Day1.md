# To become familiar with how files are added to and removed from HDFS and how to view files in HDFS

**The hdfs dfs command to view the usage of hdfs**

  ![dfs1](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(258).png)
  


**Run the -ls command to view the contents of the user’s root directory in HDFS, which is /user/root**

  ![dfs2](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(260).png)
  ![dfs3](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(261).png)
 

**Create a directory named test in HDFS:**

  ![dfs4](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(266).png)
  
c. Verify that the folder was created successfully: 
  ![dfs5](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(267).png)

**Create a couple of subdirectories for test:**

   ![dfs6](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(285).png)
 

**To recursively view the contents of a folder, use -ls -R:**
 ![dfs7](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(268).png)
 

**Delete a Directory means delete the test2 folder (and recursively, its subcontents) using the -rm -R
command:**
 ![dfs8](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(269).png)
 
**Upload a File to HDFS:**

 ![dfs9](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(270).png)
  ![dfs10](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(271).png)
 
a.Now let’s put a file into the test folder. Change directories to  /root/devph/labs/Lab2.1: 

 ![dfs11](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(280).png)
 
b. Notice this folder contains a file named data.txt: 
 ![dfs12](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(281).png)

 
c. Run the following -put command to copy data.txt into the test folder in HDFS:
 ![dfs13](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(282).png)
 
d. Verify that the file is in HDFS by listing the contents of test: 
 ![dfs14](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(283).png)
 

**5 ) Copy a File in HDFS :**
 ![dfs15](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(286).png)
 
**Now delete the data2.txt file using the -rm command: **
 ![dfs16](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(287).png)
 

**View the Contents of a File in HDFS:**
 ![dfs17](https://github.com/p8517/AWS_25/tree/Big-Data/imagess/Screenshot(288).png)
 

**tail command to view the end of a file:**
  ![dfs18](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(289).png)

**Getting a File from HDFS:**
 ![dfs19](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(290).png)
  ![dfs20](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(292).png)
   ![dfs21](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(293).png)
 
** The getmerge Command:**
 ![dfs22](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(298).png)

** Specify the Block Size and Replication Factor :**
a. Put /root/devph/labs/Lab2.1/data.txt into /user/root in HDFS, giving it a  blocksize of 1,048,576 bytes. 
 ![dfs23](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(300).png)
 

b. Run the following fsck command on data.txt:
 
 ![dfs24](https://github.com/p8517/AWS_25/tree/Big-Data/images/Screenshot(301).png)






