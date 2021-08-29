# Install-Docker-Exercise
![Installdocker1](Images_DockerInstall/logo.png)
## Purpose of Docker
Developers write a code, generate an output and make it work on his machine, when developer share there build (Developed application) to other machine then the build doesn’t work. To solve this issue **Docker** Helps to create a same environment in another machine.

## About Docker
Docker is an application which creates a container or a image on which different elements are placed and it holds all the code and information of build. This container is portable and deployed everywhere. 
Docker container has:
* Code
* Dependences
*	Configuration
*	Process
*	Networking
*	O.S (small chunk)
*	And more

## Features of Docker
*	Environment Standardization 
*	Isolation And portability
*	Build Once and deploy everywhere

## Advantages of Docker
* It is compatible with any programming language
*	It allows to have a sealed and air tight container warped of code and Portable
*	It allows to have social containers to share container in public.

## Install the Docker

### Pre-requisite
To install Docker on a machine it has to satisfy the below software and hardware requirements

#### Software Requirements
* Windows 10 64-bit
* Enable the WSL 2 feature on Windows. 

#### Hardware Requirements
* 64-bit processor with Second Level Address Translation (SLAT)
* 4GB system RAM
* BIOS-level hardware virtualization support must be enabled in the BIOS settings. 

### Procedure
In this procedure I am sharing my experiences when installing docker
Do this following:
1. To download Docker visit https://docs.docker.com/desktop/windows/install/.
1. Click on **Docker Desktop for windows**, it downloads the **Docker Desktop Installer.exe** file. Double click on **Docker Desktop Installer.exe**. see the following figure.
![Installdocker1](Images_DockerInstall/Install%201.png)

1. Allow access to install application (For windows). The *Docker Desktop* window is prompted then it download docker packages. see the following figure.
![Installdocker1](Images_DockerInstall/Install%202.jpg)

1. When Download is done, *Docker Desktop* window is Transformed to *Configuration* window. In *Configuration* window ensure to check **Install required Windows components for WSL 2** then Click **OK** as shown in figure below.
![Installdocker1](Images_DockerInstall/Install%203.jpg)

1. *Docker Desktop 3.6.0* window is prompted and it automatically unpack the Files and install as shown in below figure
![Installdocker1](Images_DockerInstall/Install%204.png) 

1. The Installing *Docker 3.6.0* window is transformed and shows installation succeeded as shown in figure below. 
![Installdocker1](Images_DockerInstall/Install%205.png)

1. Click on **Close and restart** to complete the installation process. 
On successful installation and after restart, search for Docker, and select **Docker Desktop** in the search results. See figure below
![Installdocker1](Images_DockerInstall/Install%206.png) 

1. Click on **Docker Desktop** and It loads docker application. see the Application interface in below figure.
![Installdocker1](Images_DockerInstall/Install%20Docker-End.png) 

