# Microsoft Azure Computing & VPN Understanding
#
#
# Set up Microsoft Azure Resource Group
# Create Windows 10 Virtual Machine Inside Our Resource Group
# Remote Desktop Virtual Machine 
# Utilize a VPN with our VM Remotely using Proton VPN
# See the changes of location from NO VPN to using Proton VPN

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Command Line Tool
- VPN Proton Software

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Step 1
  - Create a Resource Group where the Virtual Machine will be installed.
- Step 2
  - Create a Virtual Machine within the Resource group making sure the region, size of machine and the networking validates.
- Step 3
  - Use Remote Desktop to remotely login to your Virtual Machine using the Public IP Address.
- Step 4
  - Browse whatismyipaddress to find your location which is USWest (where my VM was created) on Arizona, USA.
- Step 5
  - Download Proton VPN on your VM to find a secure VPN Server in another location.
- Step 6
  - Browse whatismyipaddress from your VM with the VPN running and see the location change. (shows my VM being in Netherlands)

<h2>Actions and Observations</h2>

CREATING A RESOURCE GROUP IN MICROSOFT AZURE.
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/45abdb8b-db08-457c-8952-c27c659aea13)
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/18fd5851-30b4-4400-bcfa-e6f57b988cb9)

CREATE A VIRTUAL MACHINE WITH WINDOWS 10 OS, THE CPU SIZE AND MEMORY TO RUN IT, AND MAKE YOUR USERNAME AND PASSWORD FOR YOUR VM.
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/89657ce3-15f0-4db9-adb0-48caa2110863)

MAKE SURE IT VALIDATES ALL THE INFORMATION AND THEN CREATE IT. (IT WILL AUTOMATICALLY GIVE IT A NETWORK)
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/d2ae1424-3168-4aee-8b2d-b2a8e29ac9a1)

YOU CAN SEE THE DETAILS THAT AZURE GIVES TO YOUR NEW VM (NIC, NETWORK SECURITY GROUPS, IP ADDRESS ETC)
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/051ca282-48d1-49e6-a4b8-48d0c193a8ff)

COPY THE PUBLIC IP ADDRESS FROM YOUR VM IN AZURE AND ON YOUR LOCAL COMPUTER OPEN REMOTE DESKTOP TO LOGIN INTO YOUR VM USING THE USERNAME AND PASSWORD YOU PROVIDED.
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/54f1b974-dc9c-4c7c-aed0-b27490ec3358)

OPEN COMMAND PROMPT TO SEE YOUR VM HOST AND NAME TO VERIFY
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/727ae620-91fe-4b26-b4a6-1f2735fe01fd)

OPEN YOUR BROWSER AND LOOK THE IP ADDRESS LOCATION ON (whatismyipaddress.com) SHOWS USWEST ARIZONA
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/62d754a1-a11b-4db3-9a18-9e706cb476d1)

DOWNLOAD PROTON VPN WITH YOUR SPECIFIC OPERATING SYSTEM
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/0018ccbf-2309-44f2-870a-88ebecda63b2)

STABLISH A CONNECTION WITH A VPN SERVER 
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/94caf404-1c57-4150-b32d-30f7f4f5a845)

OPEN YOUR BROWSER AND LOOK UP THE IP ADDRESS LOCATION ON (whatismyipaddress.com) AND SEE THE CHANGE IN IP ADDRESS, NOW IT SHOWS THE NETHERLANDS.
![image](https://github.com/JasonCIT/MicrosoftAzureComputing/assets/145295769/560a9898-4a08-42e3-96bc-ad061e18b78a)

