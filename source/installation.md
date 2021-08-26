# Installation

Here we will go over installing Python 3 and pip, downloading the project, installing packages using pip, and adding Spotify to PATH.

(python-intallation)=
## Installing Python 3

(windows-installation)=
### Windows

If you already have Python 3, skip this section. Navigate to [python.org/downloads](https://www.python.org/downloads/).

```{admonition} Tip:
:class: tip

You may install an older and more stable version of Python if you would prefer
```


```{image} https://cdn.discordapp.com/attachments/847957606567378984/873954698439303168/win-python-download.png
:alt: win-python-download
:height: 450px
:align: center
```

Click on the large yellow button close to the top of the screen. Here it says "Download Python 3.9.6", but it may be slightly different for you.
Open the downloaded file. It should look something like this.


```{image} https://cdn.discordapp.com/attachments/847957606567378984/873954698900697168/win-python-install.png
:alt: win-python-install
:height: 400px
:align: center
```

Make sure "Add Python to PATH" is checked towards the bottom. Click "Install Now", grant any permissions it asks for, and wait for it to complete.


```{image} https://cdn.discordapp.com/attachments/847957606567378984/873954699995389962/win-python-install-success.png
:alt: win-python-install-success
:height: 400px
:align: center
```

If you see a screen something like this, you have successfully installed Python 3!

(ubuntu-installation)=
### Debian/Ubuntu

Since most Debian based Linux distributions come with Python 3, first check if you already have it installed. Run the command `python3 --version`. If you get a response similar to `Python 3.8.10`, then you already have Python installed.
If you don't get an output like that, you need to install Python 3. Run the command `sudo apt install python3`.

```{admonition} Warning:
:class: warning

Most distributions don't come with pip installed. Run `pip3 --version` to see if it's installed. If not, run `sudo apt install python3-pip`.
```

(project-download)=
## Downloading the project

```{admonition} Tip:
:class: tip

If you have git installed, you may clone the repo instead
```

Navigate to [github.com/daspartho/SpotiByeAds](https://www.github.com/daspartho/SpotiByeAds).

```{image} https://cdn.discordapp.com/attachments/847957606567378984/873954690918912070/gh-download.png
:alt: gh-download
:height: 450px
:align: center
```

Click on the green button labeled "Code" and click on it. A drop down menu should appear. Press "Download ZIP".

(project-extraction)=
## Extracting the project

(win-extraction)=
### Windows
```{image} https://cdn.discordapp.com/attachments/847957606567378984/873954695062896690/win-extract-zip-1.png
:alt: win-extract-zip-1
:height: 400px
:align: center
```

After downloading the ZIP file, right click on it and press "Extract All".

```{image} https://cdn.discordapp.com/attachments/847957606567378984/873954695759163402/win-extract-zip-2.png
:alt: win-extract-zip-2
:height: 400px
:align: center
```

Choose where you want to extract the project to and press "Extract".

(ubuntu-extraction)=
### Debian/Ubuntu

```{image} https://cdn.discordapp.com/attachments/847957606567378984/873977045053485086/ubuntu-extract-zip.png
:alt: ubuntu-extract-zip
:height: 400px
:align: center
```

After downloading the ZIP file, right click on it and press "Extract Here".

(package-installation)=
## Installing packages

```{admonition} Note:
:class: note

The program now installs packages automatically, so you no longer have to manually install anything. The below instructions are optional.
```

Open Command Prompt or PowerShell on Windows or Terminal on Debian/Ubuntu. Type in the command `pip install spotipy pynput`. On Debian/Ubuntu you may need to type `pip3 install spotipy pynput`.
You should get a success message similar to `Successfully installed pynput-1.7.3 spotipy-2.18.0`, but it may be slightly different.

(win-path)=
## Adding Spotify to PATH

```{admonition} Note:
:class: note

This is only required for Windows systems. Linux users can skip this step.
```

```{image} https://cdn.discordapp.com/attachments/847957606567378984/874104192527106078/spotify-path1.png
:alt: spotify-path1
:height: 400px
:align: center
```

Search up Spotify in Windows search (Windows Key + S) and press "Open file location".

```{image} https://cdn.discordapp.com/attachments/847957606567378984/874104875657617468/spotify-path2.png
:alt: spotify-path2
:height: 400px
:align: center
```

This should bring up a Spotify shortcut. Right-click on that and press "Open file location".

```{image} https://cdn.discordapp.com/attachments/847957606567378984/874107667319242813/spotify-path3.png
:alt: spotify-path3
:height: 400px
:align: center
```

```{admonition} Tip:
:class: tip

The default path for Spotify is C:\Users\yourname\AppData\Roaming\Spotify
```

This should open the location of the Spotify executable. Click on the path at the top of the File Explorer and copy it.
From the command line, run `setx path "%path%;spotifypath"`, replacing spotifypath with the path that you just copied.
To check that it has been added to the PATH variable, run `path`. You should see the path to Spotify you just added at the very end.

Now click "Next" to go over creating a new Spotify application, getting the ClientID and secret, and running the program with them.