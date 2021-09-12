# Setup

Here we will go over creating a new Spotify application, getting the ClientID and secret, and running the program with them.

(spotify-application)=
## Creating a Spotify Application

Navigate to [www.developer.spotify.com/dashboard/](https://developer.spotify.com/dashboard/). Sign in and accept the terms of service if necessary.

```{image} img/spotify-application-create.png
:alt: spotify-application-create
:width: 750px
:align: center
```

Click on the green "Create An App" button. Add anything you want as the app name and app description.

```{image} img/spotify-application-edit.png
:alt: spotify-application-edit
:align: center
```

Click on the green "Edit Settings" button.

```{image} img/spotify-application-edit2.png
:alt: spotify-application-edit2
:height: 400px
:align: center
```

Set the "Redirect URI" section to [http://localhost:8080/](http://localhost:8080/). Save the settings.

```{image} img/spotify-application-info.png
:alt: spotify-application-info
:width: 750px
:align: center
```

Note down your Client ID and Client Secret somewhere.

```{admonition} Warning:
:class: warning

Be careful with your Client Secret. It's called a secret for a reason.
```

## Running The Program

Open the folder where you saved SpotiByeAds. Double-click on main.py (on Debian/Ubuntu, you'll need to open the folder in terminal and run `python3 main.py`).

```{image} img/spotibyeads-info-prompt.png
:alt: spotify-application-info-prompt
:width: 750px
:align: center
```

Enter information as prompted. You may choose to save your information for a future session if you want to.

```{image} img/spotify-application-agree2.png
:alt: spotify-application-agree2
:height: 400px
:align: center
```

Press the green agree button.

```{image} img/spotify-application-success.png
:alt: spotify-application-success
:width: 500px
:align: center
```

If all goes well, you should see a window like this.

Close the window and check the program. It should say `Awesome, that's all I needed. I'm watching for ads now <.<`. If so, then congratulations! You can go without those pesky ads.