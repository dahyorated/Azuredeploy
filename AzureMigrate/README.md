Step 1

Create Windows Server 2019 Virtual machine (Preferably Gen 2 with 8 cores and 32 GB RAM size)

-----------------------------------------------------------------------------------

Step 2

Activate Hyper V role on Windows Server 2019 

Using PowerShell:

Install-WindowsFeature -Name Hyper-V -ComputerName <computer_name> -IncludeManagementTools -Restart

Doc: https://docs.microsoft.com/en-us/windows-server/virtualization/hyper-v/get-started/install-the-hyper-v-role-on-windows-server
