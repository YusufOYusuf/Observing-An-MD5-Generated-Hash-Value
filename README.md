<h1>Observing an MD5 Generated Hash Value</h1>


<h2>Description</h2>
In this lab, I learned to observe an MD5-generated hash value. MD5 hashing algorithm produces a 128-bit hash value or digest value of an entire file. These hash values can be used for checking the data integrity of the file. When a user downloads any file, the file data can be manipulated by an attacker in between. MD5 gives authentication that the file has been manipulated or not.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar open up the terminal  <br/>
<img src="https://i.postimg.cc/g2ztDGP0/Screen-Shot-2023-02-23-at-1-53-56-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  
<br />
In the Terminal window execute the "md5sum ~/Downloads/ucertify.iso > ~/Downloads/temp.txt" to compute and check the MD5 message digest of the of a downloaded file for errors<br>
<img src="https://i.postimg.cc/7Lm52Mn6/Screen-Shot-2023-02-23-at-1-56-26-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



<br />
Now execute the "diff ~/Downloads/actual.txt ~/Downloads/temp.txt" command to check the MD5 hash value of the downloaded file and its actual MD5<br>
<br> The diff command stands for "difference" and it is used to display the differences in the files by comparing the files line by line <br>
<br> If the file is the same than it is error free <br>
<img src="https://i.postimg.cc/cJR5d6Z0/Screen-Shot-2023-02-23-at-2-01-16-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />


















