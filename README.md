# Oracle-Windows-Server

## Root Access

```
sudo -i
```

## Update Packages

```
apt-get update
```

## Install Requirement Packages

```
apt-get install -y xz-utils openssl gawk file
```

## Installing DD Image

```
wget --no-check-certificate -qO InstallNET.sh 'https://github.com/praveenkarunarathne/Oracle-Windows-Server/releases/latest/download/InstallNET.sh' && bash InstallNET.sh -dd 'https://github.com/praveenkarunarathne/Oracle-Windows-Server/releases/latest/download/winsrv2022-data-x64-us-efi.vhd.gz'
```

## Login Details

Username :-

```
Administrator
```

Password :-

```
nat.ee
```

## Activating Windows

Use this script :- https://github.com/massgravel/Microsoft-Activation-Scripts
