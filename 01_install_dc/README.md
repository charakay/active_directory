# 01 installing the Domain Controller

1. Use 'sconfig' to:
    - Change the hostname
    - Change the IP address to static on the DC
    - Change the DNS server to our own IP address (DC controller)

2. Install the Active Directory Windows Features

'''shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools