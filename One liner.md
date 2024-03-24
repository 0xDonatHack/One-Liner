
# Execute automatically when download

Linux:-

`curl -s http://example.com/myscript.sh | bash`


Windows:-

`(New-Object System.Net.WebClient).DownloadString('http://example.com/myscript.ps1') | Invoke-Expression`

## Note :-

Replacehttp://example.com/myscript.ps1 with your hosted script link

### How This Commands Run

##### Step1: 

This will first Download the file Given in the link.

##### Step2:

Now, Downloaded file will run Automatically.
