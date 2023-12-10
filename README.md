<h1>Packet Capturing with Wireshark</h1>


<h2>Description</h2>
In this project I am conducting traffic capturing and analyzing web traffic using the network analyzer tool Wireshark in a virtual lab enviornment. I will further conduct additional labs to familiarize myself with the usage of Wireshark to prepare for a security role where I may need to utilize the tool. 
<br />


<h2>Utilities Used</h2>

- <b>Wireshark</b> 
  
<h2>Environments Used </h2>

- <b>Ubuntu</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Step 1: Instsall the application using the command terminal & inputting: Sudo apt install wireshark <br/>
  
![Wireshark Step 1](https://github.com/JonathanTayviah/WireShark-Beginners-/assets/153164850/8c05d970-d9f3-460d-a148-122f99b17997)

<p align="center">
Step 2: Start a packet capture to capture the current packets running on the network

![image](https://github.com/JonathanTayviah/WireShark-Beginners-/assets/153164850/c82b4dd6-454b-468e-b552-bc812e7357c6)

<p align="center">
Step 3: Select the ethernet adapter 

![image](https://github.com/JonathanTayviah/WireShark-Beginners-/assets/153164850/07ecf29c-7cab-4921-8897-a4df61e73d4f)

<p align="center">
Step 4: After capturing the current packets running, stop the capture & save it as a file

![image](https://github.com/JonathanTayviah/WireShark-Beginners-/assets/153164850/0bc58ba4-f871-4247-8ea5-2b4ae585b67d)

<p align="center">
Step 5: Open the capture file and it will appear in the middle of the GUI so the data can be veiwed 

![image](https://github.com/JonathanTayviah/WireShark-Beginners-/assets/153164850/2172f2af-dad2-4b37-ba88-c25303b6ab43)

<p align="center">
Step 8: Use a display filter to detect HTTPS packets. In this step I used Firefox to go to a random site and detect its HTTPS packets 

![image](https://github.com/JonathanTayviah/WireShark-Beginners-/assets/153164850/923459f6-46c8-4653-ab1d-bd886b0c8cf6)
