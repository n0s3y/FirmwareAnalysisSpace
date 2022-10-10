# FirmwareAnalysisSpace

This projects leans on 'vagrant' and 'virtualbox'. Make sure this is installed.

Vagrant will startup a Virtualbox box that has FirmAE pre-installed. 

The default username: 'vagrant'.
The default password: 'vagrant'.

If the script says; "    default: Warning: Authentication failure. Retrying..."     THEN open Virtualbox manually and open the box that is showing 'running'.

![image](https://user-images.githubusercontent.com/105726899/194804975-817658d4-9dac-401b-8aa9-a8e0d8fb5987.png)

## Installation

1. Install Vagrant and Virtualbox.
```console
sudo apt install vagrant virtualbox -y
```

2. Install base box via github.
```console
cd FirmwareAnalysisSpace && vangrant up
```


3. OPTIONAL: if you want to install via default cloud.vagrant, do:.
```console
vagrant init n0s3y/Kali && vagrant up
```

