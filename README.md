# Project Title: WSL & DOCKER

## Overview

This project is about setting up a local development environment on my pc, using ubuntu wsl and docker containerization application.

## Prerequisites

- Download & Install Docker,
- Install & Install WSL(Ubuntu),
- Enable virtualization(BIOS/UEFI),
- Integrate WSL Ubuntu with docker,
- Run docker.

## Step-by-Step Guide

### 1. Enable WSL

Instructions on enabling WSL on Windows:
- Open PowerShell as admin and run this command: <dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart>

###2. conversion
- On PowerShell: <wsl --set-version <Ubuntu> 2>: This command is used to change wsl version from WSL1 to wsl2.

###3. Docker
- Open docker and enable WSL engine
- Select 'Ubuntu' then save & restart

##4. Ubuntu CLI
- run command: <docker version> to test integration

##5. WSL
- clone repo.
