## Creating-a-backdoor-with-SET
## creating a backdoor with SET - Ethical Hacking Techniques course


## NAME : RAMESH KRISHNAN S
## REG NO : 212224220076



# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode



### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:

Open terminal and try execute some kali linux commands


## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1577" height="1013" alt="Screenshot 2026-08-25 134104" src="https://github.com/user-attachments/assets/7e9cab72-e6c9-4c5c-9193-f973a2816a9a" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="482" height="207" alt="Screenshot 2026-08-25 134157" src="https://github.com/user-attachments/assets/4bc149dd-6e68-4b24-82d5-4549796c0f93" />

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="512" height="288" alt="Screenshot 2026-08-25 134233" src="https://github.com/user-attachments/assets/b1575e56-fcd0-4b20-ab23-4465ceec1422" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1345" height="460" alt="Screenshot 2026-08-25 134256" src="https://github.com/user-attachments/assets/a274de4a-0ffa-47e8-9856-fa64c9ffd2a7" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="755" height="472" alt="Screenshot 2026-08-25 134402" src="https://github.com/user-attachments/assets/442b2258-4c7a-4319-9406-5f3e88a79686" />


It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="755" height="472" alt="Screenshot 2026-08-25 134402" src="https://github.com/user-attachments/assets/4160146c-b61c-40a8-b5a3-f57783826507" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1123" height="183" alt="Screenshot 2026-08-25 134541" src="https://github.com/user-attachments/assets/b63e1bd6-7330-42a1-b8b8-1bb513ae5b67" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1600" height="743" alt="dc483e0c-0969-490c-b2d6-881888d4101a" src="https://github.com/user-attachments/assets/94761821-b4a3-4b28-8478-ad2a79c267b3" />



SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1600" height="743" alt="e7c15a4f-64d8-43c1-803c-c93a69625a71" src="https://github.com/user-attachments/assets/eaccc74c-d6ce-4870-aeec-1674cd3a884f" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1600" height="743" alt="e7c15a4f-64d8-43c1-803c-c93a69625a71" src="https://github.com/user-attachments/assets/f7f425e8-2423-40e8-861b-e83108e65ff6" />












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
