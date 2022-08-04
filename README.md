# ARP-spoofing-dector
If we look at how our ARP spoofer program works, we will be able to notice that we created a function to send ARP responses that used to poison the ARP table of the victim machine. We will be making some changes in that function and edit it so that if the packets have a layer of spoofed ARP, the program could detect it. We will use the following code in order to do so :
https://an4ndita.medium.com/write-your-own-arp-spoof-detector-in-python-coding-for-cyber-security-program-5-9c23ff5e6175
<p algin="center">![image](https://user-images.githubusercontent.com/67865621/182819680-eaf680a0-04eb-4d85-9f24-2443f92124fb.png)</p>
<br>


USAGE :

$ git clone https://github.com/An4ndita/arp-detector.git

$ cd arp-detector

$ python3 arpdetector.py

Enter the interface >



DEPENDENCIES :

$ pip install scapy
