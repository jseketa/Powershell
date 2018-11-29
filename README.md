# Collection of random powershell scripts made for remote execution
---

Execute a script with 
```powershell
iex (New-Object Net.WebClient).DownloadString($remote_path)
```
where $remote_path is the path to the raw github file.
