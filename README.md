# Dual Booting Kali Linux and Windows
# Information:
In this article, I will show you how to dual boot kali linux along side windows. I also made a video on this so go watch that if you are confused on any of the steps.
# Before you start:
Make sure you have the following on hand: 1) FLASH DRIVE WITH AT LEAST 20 GB OF STORAGE 2) AT LEAST 30 GB OF STORAGE SPACE ON YOUR DRIVE THAT YOU CAN ALLOCATE TO KALI LINUX
# Other things to check:
Please also ensure that you have at least 8 GB of memory. It isn't required but it makes life a lot easier. You could probably get by with half that but running some tools will cause issues.
# Step 1- Downloading your ISO file:
After you've checked everything over and have the required materials on-hand, you'll want to download the ISO file for Kali Linux. Go to https://www.kali.org/get-kali/#kali-platforms and select "Bare Metal" <br />
![image](https://user-images.githubusercontent.com/77810019/136435143-070df2ae-15a9-4180-b328-1b465df0765a.png) <br />
Next, chose either 64 or 32 bit (google how to check which one applies to you) and then download the file called "Installer" <br />
![image](https://user-images.githubusercontent.com/77810019/136435443-c4bad747-77df-46ed-8d44-519176dbbf01.png) <br />
This download is large so give it some time to install. It took me approximately 25 minutes to complete. <br />
# Step 2- Creating your Live-USB:
Now that you've finished downloading your ISO file, plug in your USB drive. Next, download rufus from my file repository. Run it and select the ISO file that you just downloaded and set your usb drive as the device. <br />
![image](https://user-images.githubusercontent.com/77810019/136435949-d1225f3f-6857-48e4-ad86-f4c3064df930.png) <br />
After your rufus interface looks close to mine, press the start button and let it do its thing. Once it is done, your USB drive will look something like this: <br />
![image](https://user-images.githubusercontent.com/77810019/136436159-624ae895-d887-4fac-bda1-47707dafa346.png) <br />
