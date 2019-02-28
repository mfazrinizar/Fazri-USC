# Fazri-USC

Fazri-USC is a tool that can check and show the detail of the website/url's response. Fazri-USC has a full name, it is Fazri-URL Status Checker. 

## How to Run This Tool/Program ?

There are 3 kind of OS (Operating System) which is tested and compatible against this tool/program. They are Kali Linux, Windows, and Android. Run these commands :

### Kali Linux (Terminal Kali Linux)

- apt-get install perl
- apt-get install git
- cpan install Term::ANSIScreen
- git clone https://github.com/Anon6372098/Fazri-USC
- cd Fazri-USC
- perl usc.pl

or

- sudo apt-get install perl
- sudo apt-get install git
- cpan install Term::ANSIScreen
- git clone https://github.com/Anon6372098/Fazri-USC
- cd Fazri-USC
- perl usc.pl

### Windows (CMDer)

- install package manager chocolatey first in the CMD as Admin 

@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
  
- choco install perl
- choco install git
- cpan install Term::ANSIScreen
- git clone https://github.com/Anon6372098/Fazri-USC
- cd Fazri-USC
- perl usc.pl

### Android (Termux)

- pkg update && pkg upgrade
- pkg install perl
- pkg install git
- cpan install Term::ANSIScreen
- git clone https://github.com/Anon6372098/Fazri-USC
- cd Fazri-USC
- perl usc.pl
