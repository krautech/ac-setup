# ac-setup
This holds the chocolatey script for AC testing and development

Below is a command that can be run on a Windows machine via admin powershell to setup Chocolatey!

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

Afterwards, run the setup powershell script from the repo to get the software for testing/eval.
