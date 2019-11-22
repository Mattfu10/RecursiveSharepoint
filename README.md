# RecursiveSharepoint
# Recursive deletion of sharepoint folder to avoid O365 Retention Policies
# Credit to https://www.sharepointdiary.com/2018/08/sharepoint-online-delete-all-files-and-sub-folders-recursively-from-folder-using-powershell.html
# Files will not delete when in use 
# Ensure you are in Admin Sharepoint Online Management Shell link https://www.microsoft.com/en-us/download/details.aspx?id=35588
# Install https://www.microsoft.com/en-us/download/details.aspx?id=42038 CSOM Here
# To remove auto-saved credentials and have them requested upon running pass
 #Get Credentials to connect
    $Cred= Get-Credential
