# Tp2-network-security

# Introduction 

This report provides an overview of network packet analysis using Wireshark, a powerful and open-source tool used to capture, analyze, and filter network traffic. In this report, we will explore the basics of network packet analysis, learn how to capture and interpret network traffic, and examine different types of network protocols.

Through this report, we will gain a comprehensive understanding of Wireshark packet analysis, the tools and techniques used for capturing and analyzing network traffic. By the end of this report, we will be equipped with the knowledge and skills required to capture and analyze network traffic.

## Schema:

First of all, here's an overview of how our configuration schema:

We will have **three** different machines : 

The first and second machine will be on different networks.

- For the first machine called **kali** the ip address is : ``192.168.1.2``

- For the second machine called **kali2** its ip address is : ``192.168.2.2``

In the image bellow the third machine will work as a router with two interfaces.

<p align="center">
  <img width="1000" src="https://user-images.githubusercontent.com/73228919/225160013-3eb43128-6559-4cbb-b038-a8d61e6c8721.png">
</p>

# 1) Configuration:

Let's now configure our machine:

- For the ***first*** machine (*client*) we're going to set the ip address manually:

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/225417652-27623f7b-af38-40a1-bbc3-22eccf3e3e00.png">
</p>

Then we're going to test with the command ``Ifconfig``.

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/225418388-7c40c631-a5da-498c-967b-949eb67622e7.png">
</p>

- Same thing for the ***second*** machine (*client*) we're going to set the ip address manually:

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/226129512-d4e99dba-cedf-4f3b-94af-0ce712664b8f.png">
</p>

Then we're going to test with the command ``Ifconfig``.

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/226129516-070314c4-9029-4f53-947b-467d8b5fde38.png">
</p>

- Now for the ***third*** machine which plays the role of a *router*

First we're going to set two adapters as the images bellow show:

<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/228249860-91255e52-2f7e-4387-b59f-7211c6cb4119.png">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/228249888-cedb800b-42ea-416b-a09c-c90e05526483.png">
</p>

Then we're going to set the ip adresses of both adapters:

<p align="center">
  <img height="400" width="500" src="https://user-images.githubusercontent.com/73228919/226129853-ef041ebd-2cfa-4202-8000-2bfb47c438e2.png">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/226129876-f90eeabd-ccdd-426c-9927-1af57bea4314.png">
</p>

Then we're going to test with the command ``Ifconfig``.

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/226174161-73efb99b-1cfe-4ba7-9707-e269d8604abe.png">
</p>

- Then we're going to set the routing table and set the ip forwarding value to 1. The images bellow show the routing commands and the routing table and also the we changed the valur of the ipo forward to 1.

<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/226182527-af7d4474-5583-4805-87c8-03450e5574a6.png">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/226182555-04a6bd28-3778-4f0f-ba1b-cbfd320583dd.png">
</p>

# 2) Wireshark:

- Now here's a demo that demonstrates the pinging between the machines.

https://user-images.githubusercontent.com/73228919/227377301-deb1daf8-66ac-4841-9b0d-05107d3d2817.mp4


- As we can see in the video we started ``wireshark`` in the routing machine and we captured the ***network traffic***.

The next step we're going to analyze the **trams**.

<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/227197397-dd5d926e-87a5-4a2f-a967-fc7765e66fdb.png">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/227197487-204b95d2-7224-44d2-bda6-7db9c29fa657.png">
</p>

# Conclusion:

In conclusion, the analysis of the tram network architecture using Wireshark provided a detailed understanding of the network design and communication protocols. By examining the network traffic, it was possible to identify the various components of the tram network and their communication patterns.

The analysis revealed that the tram network consists of several interconnected nodes and devices, including switches, routers, and tram vehicles. The communication between these devices is facilitated by various protocols, including Ethernet, TCP/IP, and UDP. By understanding the communication protocols used in the network, it is possible to design and implement more efficient and reliable tram networks.


<p align="right">(<a href="#top">back to top</a>)</p>



