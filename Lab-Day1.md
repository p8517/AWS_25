# To become familiar with how files are added to and removed from HDFS and how to view files in HDFS

**The hdfs dfs command to view the usage of hdfs**

  ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223824-b17d5380-bba5-11ea-87ca-2e5fcf711b78.png)
  
**Run the -ls command to view the contents of the user’s root directory in HDFS, which is /user/root**

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223385-1dab8780-bba5-11ea-92c7-f7093a134f59.png)
 
 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223391-1f754b00-bba5-11ea-8085-492b9a4b47cb.png)
 
**Create a directory named test in HDFS:**

  ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223411-256b2c00-bba5-11ea-8a1a-ae51fd671eed.png)
  
*c. Verify that the folder was created successfully: *

  ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223414-2603c280-bba5-11ea-80b2-b3898bd276ea.png)

**Create a couple of subdirectories for test:**

  ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223438-2e5bfd80-bba5-11ea-9f22-4fa125baa842.png)
 

**To recursively view the contents of a folder, use -ls -R:**

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223416-269c5900-bba5-11ea-90f3-85216b934ce6.png)
 

**Delete a Directory means delete the test2 folder (and recursively, its subcontents) using the -rm -R
command:**

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223418-27cd8600-bba5-11ea-954f-b8ac945fb18c.png)
 
**Upload a File to HDFS:**

 ![Screenshot (258)]
 
 ![Screenshot (258)]
 
*a.Now let’s put a file into the test folder. Change directories to  /root/devph/labs/Lab2.1:*

 ![Screenshot (258)]
 
*b. Notice this folder contains a file named data.txt:* 

 ![Screenshot (258)]

 
*c. Run the following -put command to copy data.txt into the test folder in HDFS:*

 ![Screenshot (258)]
 
*d. Verify that the file is in HDFS by listing the contents of test: *

 ![Screenshot (258)]
 

**5 ) Copy a File in HDFS :**

 ![Screenshot (258)]
 
**Now delete the data2.txt file using the -rm command: **

 ![Screenshot (258)]
 

**View the Contents of a File in HDFS:**

 ![Screenshot (258)]
 

**tail command to view the end of a file:**

![Screenshot (258)]
  

**Getting a File from HDFS:**

![Screenshot (258)]

![Screenshot (258)]

![Screenshot (258)]
 
** The getmerge Command:**

 ![Screenshot (258)]
 
** Specify the Block Size and Replication Factor :**

*a. Put /root/devph/labs/Lab2.1/data.txt into /user/root in HDFS, giving it a  blocksize of 1,048,576 bytes.*

 ![Screenshot (258)]
 

*b. Run the following fsck command on data.txt:*
 
![Screenshot (258)]






