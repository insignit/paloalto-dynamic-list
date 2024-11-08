# paloalto-dynamic-list

This page can be used for dynamic blocking list from Insign-IT

## Config

Security Rule name:
```
insignit-edl-ip-block
insignit-edl-domain-block
```

External Dynamic Lists:
```
Insignit-IP-Block - https://raw.githubusercontent.com/insignit/paloalto-dynamic-list/main/outbound-block.txt
Insignit-Domain-Block - https://raw.githubusercontent.com/insignit/paloalto-dynamic-list/main/inbound-block.txt
```

## How to Add this to Palo?

First we need to create a external dynamic list\
![Alt text](pics/1.png?raw=true "Title")\
\
Use the correct format. Look at the top of this Readme File. Beware you have to create 2 items (inbound and outbound).\
![Alt text](pics/2.png?raw=true "Title")\
\
Ater creating a external dynamic list. We must sure to use this list within a Security Rule. \
Create a security rule look at below:
![Alt text](pics/3.png?raw=true "Title")\
\
Use the correct name format look at the top of this readme file. Beware you have to create 2 items(inbound and outbound).
![Alt text](pics/3.1.png?raw=true "Title")\
\
Be aware this for Outbound Rule\
![Alt text](pics/3.2.png?raw=true "Title")\
\
Be aware this for Inbound Rule\
![Alt text](pics/3.2.1.png?raw=true "Title")\
\
Be aware this for Outbound Rule\
![Alt text](pics/3.3.png?raw=true "Title")\
\
Use any \
![Alt text](pics/3.4.png?raw=true "Title")\
\
For services we need to also block any \
![Alt text](pics/3.5.png?raw=true "Title")\
\
We need to Block the traffic so define Block\
![Alt text](pics/3.6.png?raw=true "Title")\
\
This is a example how it should be.\
![Alt text](pics/4.png?raw=true "Title")
