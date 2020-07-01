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

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223422-28661c80-bba5-11ea-9594-d767682f704a.png)
 
 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223425-28feb300-bba5-11ea-89bd-0d3fe446c8bd.png)
 
*a.Now let’s put a file into the test folder. Change directories to  /root/devph/labs/Lab2.1:*

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223431-2b610d00-bba5-11ea-93a2-2382d36ed4ac.png)
 
*b. Notice this folder contains a file named data.txt:* 

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223433-2bf9a380-bba5-11ea-8df9-2ccd0523e3ba.png)

 
*c. Run the following -put command to copy data.txt into the test folder in HDFS:*

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223434-2c923a00-bba5-11ea-96db-1f723408ef56.png)
 
*d. Verify that the file is in HDFS by listing the contents of test: *

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223436-2d2ad080-bba5-11ea-9568-a0ca58aed6a3.png)
 

**5 ) Copy a File in HDFS :**

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223439-2ef49400-bba5-11ea-9bfc-6e85e77453ad.png)
 
**Now delete the data2.txt file using the -rm command: **

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223440-2f8d2a80-bba5-11ea-9761-ab8054e945ae.png)
 

**View the Contents of a File in HDFS:**

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223444-3025c100-bba5-11ea-8d08-5cfcb84d9b2e.png)
 

**tail command to view the end of a file:**

![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223444-3025c100-bba5-11ea-8d08-5cfcb84d9b2e.png)
  

**Getting a File from HDFS:**

![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223446-30be5780-bba5-11ea-8ed9-a94b483fe3c1.png)

![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223456-33b94800-bba5-11ea-84f7-8d011bcb75e6.png)

![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223461-3451de80-bba5-11ea-9c16-7b9255af15f8.png)
 
** The getmerge Command:**

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223482-39af2900-bba5-11ea-8b99-4d09a750f5e0.png)
 
** Specify the Block Size and Replication Factor :**

*a. Put /root/devph/labs/Lab2.1/data.txt into /user/root in HDFS, giving it a  blocksize of 1,048,576 bytes.*

 ![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223495-3b78ec80-bba5-11ea-9f25-e44396fab3a4.png)
 

*b. Run the following fsck command on data.txt:*
 
![Screenshot (258)](https://user-images.githubusercontent.com/63599387/86223497-3caa1980-bba5-11ea-9e4d-9056aa750f52.png)






