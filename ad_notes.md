# Active Directory
Get a list of all users:

```powershell
Get-ADUser -Filter * | Select-Object Name
```
