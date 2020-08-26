# Launch and Play Spotify at Specific Time
---
**Please note that the methods discussed are only applicable to macOS users**.


## Story Behind

I failed to get up early recently...

I understand that some soft piano background music might help waking gradually in the morning, and there ARE mobile apps thats is exactly doing that. But you need to pay for different musics... 

So I decided that there IS a way to make my Spotify plays automatically in the morning and learned some AppleScript.

## Instructions

There are a couple ways to do this.
![TouchBarScreenShot](https://github.com/madeyexz/Launch-and-Play-Spotify-at-Specific-Time/blob/master/Screenshots/Touch%20Bar%202.png)

### 1. Using the Calendar
1. Open the Calendar
2. Create an event and set the time
3. click "alert" - "custom..."
4. In the drop-down menu, select "Open file"
5. Select "Plays Spotify"

### 2. Using the Quick Action
1. Copy the codes of [this](https://github.com/madeyexz/Launch-and-Play-Spotify-at-Specific-Time/blob/master/Plays%20Spotify.scpt)
2. Open Automator
3. Copy everything in the picture ![the picture](https://github.com/madeyexz/Launch-and-Play-Spotify-at-Specific-Time/blob/master/Screenshots/Workflow.png)
4. Save it whatever name you like
5. Open "System Preference" - "Extensions" - "Touch Bar" and check the thing you just saved
6. click "customize control strip..." on the same page and drag Quick Action into Touch Bar slot
7. Done

Or you can download my workflow [here](https://github.com/madeyexz/Launch-and-Play-Spotify-at-Specific-Time/tree/master/Morning%20Spotify%20Launcher.workflow/)

### 3. Combing with BetterTouchTool to Make This

![What we see with Spotify opened](https://github.com/madeyexz/Launch-and-Play-Spotify-at-Specific-Time/blob/master/Screenshots/Touch%20Bar%202.png)

BTT is the thing that makes the useless Touch Bar useful.

1. Install (and purchase if you want) BTT [here](https://folivora.ai/)
2. Do exactly what "Using the Quick Action" does or download it [here](https://github.com/madeyexz/Launch-and-Play-Spotify-at-Specific-Time/tree/master/Morning%20Spotify%20Launcher.workflow/)
3. Click the "add" button on the buttom-left corner and select "Spotify"
4. Click the "add" button on the buttom-middle and create a new trigger.
5. Select "Touch Bar button" and then customize its appearance what ever you like
6. In "Assiged Action(s)", select "Workflow"
7. Select "Morning Spotify Launcher"
8. Done

Now when you open Spotify you should see the "Alarm" button like I do.



