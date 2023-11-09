<h1>Analyze Network Traffic with TCPDump</h1>
<h2>Description</h2>

This lab focuses in creating a shell script using Visual Studio Code, creating a .pcap file to store the data, changing the permission settings on the .pcap file to allow for execution and then running the script. Additionally, we will utilize Wireshark to view the TCP packets captured to better analyze them.
<br/>

<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 

<h2>Environments Used </h2>

- <b> Visual Studio Code and Wireshark</b>

<h3>Creating the script with Visual Studio Code:</h3>

<p align="left">
Open Visual Studio Code (create a folder on your desktop) then creat a new file by right-clicking on the left side of the pane.
<br/>
<img src="https://i.imgur.com/kdKOr97.png" height="60%" width="60%" alt="New file screenshot"/>
<br /> 
  
After creating the shell file, write the command line. Then, right click on the shell file and open an Integrated Terminal.
<br/>
<img src="https://i.imgur.com/IO2LKKA.png" height="60%" width="60%" alt="Integrated Terminal Screenshot"/>
<br />

The script is written but our .sh file needs proper executable permissions. use the chmod command to change the permissions.
<br />
<img src="https://i.imgur.com/gu3dFKl.png" height="60%" width="60%" alt="Permission Screenshot"/>
<br />

After changing the permission settings we can initiate the script. (We will need to visit the site and refresh it in order to generate data)
<br/>
<img src="https://i.imgur.com/L2bTssy.png" height="60%" width="60%" alt="Initiating Script screenshot"/>
<br />

We can modify to use the (-w) command to write onto a .pcap file, then we can run the script and analyze the .pcap file for data
<br/>
<img src="https://i.imgur.com/SEoDaIs.png" height="60%" width="60%" alt=".pcap snapshot"/>
<br/>

The .pacp file will not be readable, but you can run a code in the Integrated Terminal to view data in ASCII format
<br/>
<img src="https://i.imgur.com/qV27D9l.png" height="60%" width="60%" alt="View .pcap file in ASCII screenshot"/>
<br />

Opening the Wireshark Network Analyzer
<br/>
<img src="https://i.imgur.com/bnWEblQ.png" height="60%" width="60%" alt="Wireshark Screenshot"/>
<br />
Look for the .pcap file you created in your folder and open it
<br/>
<img src="https://i.imgur.com/CXK4iPc.png" height="60%" width="60%" alt="Open capture file screenshot"/>
<br />
Wireshark present the information in a format that is easier to understand. Now you can use multiple filters like, Source IP, Protocol and Info.
<br/>
<img src="https://i.imgur.com/Xabus2i.png" height="60%" width="60%" alt="wireshark screenshot 2"/>
<br />

</p>

<h2> Summary </h2>
I used Studio Visual Code to create a shell script. I used the chmod command to alter the permission setting on the .sh file to allow for execution, then I ran the file. I created a .pcap file to store the data then I used Wireshark to open the .pcap file and analyze the data.
