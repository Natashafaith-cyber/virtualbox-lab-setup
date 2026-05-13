# Virtualization Lab Setup on Debian

## Overview
This project documents the setup of a virtualization environment using VirtualBox on Debian Linux. The goal is to create a controlled lab environment for system analysis, testing, and security practice.

## Objectives
- Install VirtualBox on Debian
- Configure virtualization environment
- Prepare for Windows virtual machine deployment
- Document setup process with terminal evidence

## Environment
- Host OS: Debian Linux
- Virtualization Tool: VirtualBox

## Installation Process

Screenshots of installation and setup are provided in the images folder.

1 System update-command[sudo apt update && sudo apt upgrade -y]
2 Package installation-command[sudo apt install build-essential dkms linux-headers-$(uname -r)]
3 VirtualBox installation-command [sudo apt install virtualbox]
4 Application launch - command [virtualbox]

## Installation Screenshots

### Step 1: System Update
[System Update]-(images/-step1.png)(images/step1-output.png)

### Step 2: Package Installation
[Package Installation]-(images/install-step2.png)(images/install-step2-output)

### Step 3: VirtualBox Installed
[VirtualBox installation]-(images/virtualbox-installed.png)(images/virtualbox--installed.png)

### step 4: Apllication Lauch
[Application Lauch]-(images/application-lauch.png)


## Outcome
VirtualBox was successfully installed and configured on Debian. The environment is now ready for creating and managing virtual machines for further lab exercises.


## Virtual Lab Setup

A Windows virtual machine was created using VirtualBox on a Debian host system.

### Configuration
- RAM: 4GB
- CPU: 2 cores
- Storage: 80GB
- OS: Windows 11

### Purpose
Used for system testing, monitoring, and cybersecurity practice in a controlled environment.
