### Table of Contents
---
- [[#Pre video Questions|Pre video Questions]]
- [[#Post video Answers|Post video Answers]]
		- [[#Question 1 explanation|Question 1 explanation]]
		- [[#Question 2 explanation|Question 2 explanation]]
		- [[#Question 3 explanation|Question 3 explanation]]
		- [[#Question 4,5 and 6 explanation|Question 4,5 and 6 explanation]]
		- [[#Question 7 explanation|Question 7 explanation]]
		- [[#Question 8 explanation|Question 8 explanation]]

### Pre video Questions
---
1. [[#Question 1 explanation]|How many packets were captured in this trace file? ]]
	- 2186
2. [[#Question 2 explanation]|What protocol does packet number 8 contain? (The highest-layer protocol)]]
	- HTTP
3. [[#Question 3 explanation]|If you just installed Wireshark for the first time, what is the name of the profile you are using? (bottom right corner)]]
	- Default
4. [[#Question 4,5 and 6 explanation]|Look at packet number one - what is the source IP address in this packet?]]
	- 192.168.56.102
5. [[#Question 4,5 and 6 explanation]|What is the source TCP port in this same packet?]]
	- 32294
6. [[#Question 4,5 and 6 explanation]|What TCP flag is set in this packet?]]
	- 0x002 (SYN)
7. [[#Question 7 explanation]|What is the frame number of the next packet in this TCP conversation]]
	- 6
8. [[#Question 8 explanation]|Can you set a filter for this TCP conversation? How many packets do you get?]]
	- Yes, 51

### Post video Answers
---
##### Question 1 explanation
 -  Can find this information in the bottom bar

![[Pasted image 20230809214433.png]]

-  Or hit the Green (DOWN) arrow on the top bar.

![[Pasted image 20230809214539.png]]

##### Question 2 explanation
- The ***Protocol*** tab always shows the highest protocol
- In number 8 below that packet contains the actual ***Payload***
![[Pasted image 20230809215459.png]]

##### Question 3 explanation
- The profile we are using can be found in the lower right corner. We can custom make profile that are specialized to the task we are trying to accomplish
![[Pasted image 20230809215801.png]]

##### Question 4,5 and 6 explanation
- You can find all the information pertaining to the IP address Port and the Flag in the frame list at the top for a quick glance. 
- You can also select the packet and find all the information by looking through all the tabs
![[Pasted image 20230809220216.png]]

##### Question 7 explanation
- Right Click on packet that you want to see all conversations for.
- Select ***Conversation Filter***
- Select ***Select protocol you wish to track*** 
	- In our case it was TCP
	![[Pasted image 20230809221513.png]]

##### Question 8 explanation
- once you follow the steps for ***question 7*** you can see the number of packets displayed in the lower bar
![[Pasted image 20230809221805.png]]