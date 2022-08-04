# ARP-spoofing-dector
If we look at how our ARP spoofer program works, we will be able to notice that we created a function to send ARP responses that used to poison the ARP table of the victim machine. We will be making some changes in that function and edit it so that if the packets have a layer of spoofed ARP, the program could detect it. We will use the following code in order to do so :
https://technicalhaydeen.medium.com/arp-spoof-detector-in-python-68a424823cbe
<bR>
  
  
  ![image](https://user-images.githubusercontent.com/67865621/182820483-4f586d61-67a2-4b70-bdb4-33d5ba5c74a5.png)

  
  
<br>


USAGE :

$ git clone https://github.com/technicalhayden/ARP-spoofing-dector.git

$ cd arp-detector

$ python3 arpdetector.py

Enter the interface >



DEPENDENCIES :

$ pip install scapy
