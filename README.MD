//Run in powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco install -y git.install 
choco install -y jdk8
choco install -y docker
choco install -y jenkins
choco install -y gradle												
choco install -y intellijidea-community
choco install -y notepadplusplus.install
choco install -y clink
choco install -y ConEmu
choco install -y Atom

