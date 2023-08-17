#### AZ-104 Steps

## How to Create a User
<img width="587" alt="AAD" src="https://github.com/Futrawei/cloud-projects/assets/71726772/cd8ed25c-c8ed-4cdc-894e-c3b1387be0c9">
<img width="713" alt="Fill in User Info" src="https://github.com/Futrawei/cloud-projects/assets/71726772/daaf939c-3117-456e-bb94-5ca9b52fc110">
<img width="576" alt="New User" src="https://github.com/Futrawei/cloud-projects/assets/71726772/781d377b-7cd1-4671-9bd2-97ee90f0eda4">
<img width="366" alt="Users" src="https://github.com/Futrawei/cloud-projects/assets/71726772/70f7bb0d-05e6-4ce4-b7b6-9abe7765a9d9">

## Automate Azure Tasks using PowerShell
Step 1: Open up your PowerShell and type in the following below one at a timee.
* $PSVersionTable.PSVersion (This will show you what version of PowerShell you have)
* Install-Module -Name AZ -AllowClobber (type "y" for "Yes")
* Import-Module AZ
* Connect-AzAccount (Microsoft Azure GUI Window will appear.)
* Sign-In to the account (After logging in you'll get a message that says "Authentication complete. You can return to the application. Feel free to close this browser and go back to the PowerShell)

Step 2: Create a variable called "Credential" to set your credentials so you won't be asked again. 
* Type "$Credential = Get-Credential" (Window will appear for you to input your credentials for your Azure Account)
* User:
* Password:
* Connect-AzAccount Get-Credential $Credential
