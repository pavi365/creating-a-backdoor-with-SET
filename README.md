# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

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

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/9e0f7837-0cf8-47ba-8436-00e7ef25b760)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/1ba4e484-a8ac-403e-a855-b9158055d905)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/f03567e6-53d1-46d7-94e4-32e77e8dc334)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/67146c36-2dcf-42f0-a1f0-794af18e7be8)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/015442b3-8701-4039-86ac-27f090dcb212)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/c778ea6e-4d13-447f-b36b-f19e5c73c1eb)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/845cbfc5-8cce-4334-9c28-b82d5012915c)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/331339d9-02e6-4459-8510-4bb1f48974c5)

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/a1b81ca1-66d6-4c44-a61e-c3664b6f4856)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/pavi365/creating-a-backdoor-with-SET/assets/115135775/4a54600e-43a7-4a01-ad1a-69dfc5436693)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
