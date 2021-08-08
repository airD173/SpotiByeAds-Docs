# Setup

Here we will go over creating a new Spotify application, getting the ClientID and secret, and running the program with them.

(spotify-application)=
## Creating a Spotify Application

Navigate to [www.developer.spotify.com/dashboard/](https://developer.spotify.com/dashboard/). Sign in and accept the terms of service if necessary.

![spotify-application](https://cdn.discordapp.com/attachments/847957606567378984/874006629547405332/spotify-application-create.png)

Click on the green "Create An App" button. Add anything you want as the app name and app description.

![spotify-application-edit](https://cdn.discordapp.com/attachments/847957606567378984/873999420646125618/spotify-application-edit.png)

Click on the green "Edit Settings" button.

![spotify-application-redirect](https://cdn.discordapp.com/attachments/847957606567378984/874006940664102922/spotify-application-edit2.png)

Set the "Redirect URI" section to [http://localhost:8080/](http://localhost:8080/). Save the settings.

![spotify-application-info](https://cdn.discordapp.com/attachments/847957606567378984/873990653862903818/spotify-application-info.png)

Note down your Client ID and Client Secret somewhere. Be careful with the Client Secret; it's called a secret for a reason.

## Running The Program

Open the folder where you saved SpotiByeAds. Double-click on main.py (on Debian/Ubuntu, you'll need to open the folder in terminal and run `python3 main.py`).

![spotibyeads-info-prompt](https://cdn.discordapp.com/attachments/847957606567378984/873998825822486538/spotibyeads-info-prompt.png)

Enter information as prompted. You may choose to save your information for a future session if you want to.

![spotify-application-agree](https://cdn.discordapp.com/attachments/847957606567378984/874008393604546681/spotify-application-agree2.png)

Press the green agree button.

![spotify-application-success](https://cdn.discordapp.com/attachments/847957606567378984/874001761193574440/spotify-application-success.png)

If all goes well, you should see a window like this.

Close the window and check the program. It should say `Awesome, that's all I needed. I'm watching for ads now <.<`. If so, then congratulations! You can go without those pesky ads.