# ActiveDirectory
Log of setting up Active Directory
This is useful for experimenting with active directory set up and how to manage group policy and different OUs

Part One:
Getting the Tools

You need a virtualization app, the iso for windows server, the iso for windows 10/11, and a computer with at least 8 Gb of spare memory and 4 spare CPUs

Google virtualbox and download that software

![image](https://github.com/user-attachments/assets/894fe368-aed9-48c2-aec5-3eb3627148cc)

Then google windows 10 or 11 iso and download it from microsoft

11 is more current, but it forces you to use a windows/outlook account in order to finish setting up the computer.
It may be possible to bypass this by setting up the virtual machine to boot up without internet, we can cover how to do that later

After that, google windows server iso. You'll have the option of several different free versions after signing up with your name, phone number and email.
Download that

Go to virtualbox and click New

![image](https://github.com/user-attachments/assets/de6a6108-6619-440e-ad8b-799159a9b8e2)

You'll have to select the iso file for the server and make sure there's more than 4GB of memory and at least 2 CPUs of processing power.

![image](https://github.com/user-attachments/assets/66cc1091-6ec6-4fb1-9e66-0d3039f4fa25)

Then you'll want to create a virtual hard disk for the server. I did 80 Gb, but you may be able to do fine with 50Gb. 
Do not pre-allocate full size. This takes away 80Gb of your computer's space immediately and reserves it for the virtual server, as opposed to allowing the server to fill up to 80 Gb over time.
![image](https://github.com/user-attachments/assets/0a4738e9-4691-44e5-93ab-7e431b1149bf)

Click next and finish and your server will boot up.
The install for windows 10/11 is the exact same. 

Troublshooting steps:
Sometimes the install will fail altogether. 
Make sure the server and windows computer both have 2 CPUs and enough storage space allowed for each of them. 

You can also make click "Skip unattended install" because sometimes the manual install works better.

You can also go into settings for each machine and 

