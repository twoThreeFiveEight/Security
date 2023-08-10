### How to create your own Wireshark profile

- Right Click on the profile menu on the lower bar
- Select ***New***
![[Pasted image 20230809225602.png]]

- Name your profile to reflect what you are going to do with it.

![[Pasted image 20230809225910.png]]

- Start adding feature in the new window

#### Time features
- ***View > Time Display Format > Seconds since previous captured packet*** 
	- Makes the time column display the time in between packets. It is good looking for delays.
- ***Edit > Preferences > column*** Click the plus sign for ***add***
	- Add the ***Delta      Delta time displayed***

#### Adding a column by right click
- Right Click on the Item you want to add to the column Select ***Apply as Column*** 
	- We added th TTL as a column 

#### Saving a common filter
- Type the filter in and select the ***+*** Character in next to the Filter Enter button on right
- Here we added the tcp.flags.syn\==1 as a saved Filter called TCP \[SYN] 
![[Pasted image 20230809232931.png]]


#### Coloring Rules
- Coloring Rules are based on filters. You must know how to filter for the thing you are trying to color.
- ***View > Coloring Rules*** 
	- Note the list is read from top to bottom. This is why we put the ***BAD TCP*** on top because otherwise it would want to evaluate our bright green tcp.flags.syn\==1 rule we set.


