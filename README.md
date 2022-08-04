# ARP-spoofing-dector
If we look at how our ARP spoofer program works, we will be able to notice that we created a function to send ARP responses that used to poison the ARP table of the victim machine. We will be making some changes in that function and edit it so that if the packets have a layer of spoofed ARP, the program could detect it. We will use the following code in order to do so :
