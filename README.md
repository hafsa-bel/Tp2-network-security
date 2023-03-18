# Tp2-network-security

# Introduction 

This report provides an overview of network packet analysis using Wireshark, a powerful and open-source tool used to capture, analyze, and filter network traffic. In this report, we will explore the basics of network packet analysis, learn how to capture and interpret network traffic, and examine different types of network protocols.

Through this report, we will gain a comprehensive understanding of Wireshark packet analysis, the tools and techniques used for capturing and analyzing network traffic. By the end of this report, we will be equipped with the knowledge and skills required to capture and analyze network traffic.

## Schema:

First of all, here's an overview of how our configuration schema:

We will have **three** different machines : 

The first and second machine will be on different network.

- For the first machine called **kali** the ip address is : ``192.168.1.2``

- For the second machine called **kali2** its ip address is : ``192.168.2.2``

In the image bellow the third machine will work as a router with two interfaces.

<p align="center">
  <img width="1000" src="https://user-images.githubusercontent.com/73228919/225160013-3eb43128-6559-4cbb-b038-a8d61e6c8721.png">
</p>

# 1) Configuration:

Let's now configure our machine:

- For the first machine we're going to set the ip address manually:

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/225417652-27623f7b-af38-40a1-bbc3-22eccf3e3e00.png">
</p>

Then we're going to test with the command ``Ifconfig``.

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/225418388-7c40c631-a5da-498c-967b-949eb67622e7.png">
</p>

- Same thing for the second machine we're going to set the ip address manually:

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/226129512-d4e99dba-cedf-4f3b-94af-0ce712664b8f.png">
</p>

Then we're going to test with the command ``Ifconfig``.

<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/73228919/226129516-070314c4-9029-4f53-947b-467d8b5fde38.png">
</p>

- Now for the third machine which plays the role of a router we're going to set the adresses of both adapters

<p align="center">
  <img height="300" width="500" src="https://user-images.githubusercontent.com/73228919/226129853-ef041ebd-2cfa-4202-8000-2bfb47c438e2.png">
  <img width="500" src="https://user-images.githubusercontent.com/73228919/226129876-f90eeabd-ccdd-426c-9927-1af57bea4314.png">
</p>



