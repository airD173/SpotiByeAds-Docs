# Installation

Here we will go over installing Python 3 and pip, downloading the project, and installing the necessary packages using pip.

(python-intallation)=
## Installing Python 3

(windows-installation)=
### Windows

If you already have Python 3, skip this section. Navigate to [python.org/downloads](https://www.python.org/downloads/).

```{admonition} Tip:
:class: tip

You may install an older and more stable version of Python
```

![win-python-download](https://cdn.discordapp.com/attachments/847957606567378984/873954698439303168/win-python-download.png)

Click on the large yellow button close to the top of the screen. Here it says "Download Python 3.9.6", but it may be slightly different for you.
Open the downloaded file. It should look something like this.


![win-python-install](https://cdn.discordapp.com/attachments/847957606567378984/873954698900697168/win-python-install.png)

Make sure "Add Python to PATH" is checked towards the bottom. Click "Install Now", grant any permissions it asks for, and wait for it to complete.

![win-python-install-success](https://cdn.discordapp.com/attachments/847957606567378984/873954699995389962/win-python-install-success.png)

If you see a screen something like this, you have successfully installed Python 3!

(ubuntu-installation)=
### Debian/Ubuntu

(ubuntu-python)=
#### Installing Python 3

Since most Debian based Linux distributions come with Python 3, first check if you already have it installed. Run the command `python3 --version`. If you get a response similar to `Python 3.8.10`, then you already have Python installed.
If you don't get an output like that, you need to install Python 3. Run the command `sudo apt install python3`.

(ubuntu-pip)=
#### Installing pip

Even if you have Python 3, you may not have pip on Debian/Ubuntu. To check if you have pip installed, run the command `pip3 --version` in a terminal. If you get an output such as `pip 20.0.2 from /usr/lib/python3/dist-packages/pip (python 3.8)`, then you already have pip installed. If not, run the command `sudo apt install python3-pip`.

(project-download)=
## Downloading the project

```{admonition} Tip:
:class: tip

If you have git installed, you may clone the repo instead
```

Navigate to [github.com/daspartho/SpotiByeAds](https://www.github.com/daspartho/SpotiByeAds).

![gh-download](https://cdn.discordapp.com/attachments/847957606567378984/873954690918912070/gh-download.png)

Click on the green button labeled "Code" and click on it. A drop down menu should appear. Press "Download ZIP".

(project-extraction)=
## Extracting the project

(win-extraction)=
### Windows
![win-extract-zip-1](https://cdn.discordapp.com/attachments/847957606567378984/873954695062896690/win-extract-zip-1.png)

After downloading the ZIP file, right click on it and press "Extract All".

![win-extract-zip-2](https://cdn.discordapp.com/attachments/847957606567378984/873954695759163402/win-extract-zip-2.png)

Choose where you want to extract the project to and press "Extract".

(ubuntu-extraction)=
### Debian/Ubuntu

![ubuntu-extract-zip](https://cdn.discordapp.com/attachments/847957606567378984/873977045053485086/ubuntu-extract-zip.png)

After downloading the ZIP file, right click on it and press "Extract Here".

(package-installation)=
## Installing packages

```{admonition} Tip:
:class: tip

If you know how to, you may also install using requirements.txt
```

Open Command Prompt or PowerShell on Windows or Terminal on Debian/Ubuntu. Type in the command `pip install spotipy pynput`. On Debian/Ubuntu you may need to type `pip3 install spotipy pynput`.
You should get a success message similar to `Successfully installed pynput-1.7.3 spotipy-2.18.0`, but it may be slightly different.

