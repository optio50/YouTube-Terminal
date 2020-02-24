![](ScreenShot.png)
![](ScreenShot2.png)

Make all files (ytMenu & .menu files) executable before using this script.

Watch Youtube Videos without going to the youtube site. (Either on your local display or chromecast)


This script is faster than going to youtube and selecting your video of interest.


These files will fetch the latest 99 videos (or whatever # you want) and display it to you in the terminal.


Make your selection and the video will open on your local screen or a chromecast device. (MPV used for local & MKchromecast used for casting).


A menu is also included to simplify the process. The menu script will automatically and instantly see all files with the ".menu" extension and display the choices on your screen.

The menu is not limited to running the youtube script files,
it will display and run any script it sees with the .menu extension which makes it a universal menu to be used for whatever you want.


In addition the youtube channel files themselves are universal, modify any file to any channel on youtube you like via the variable options in the channel file.


Change this variable in the ytMenu script to where the .menu files are kept.


location=""${HOME}"/YouTubeVids/"

Requirements:

curl (for fetching the channel html source)


mpv (for playing the videos)


youtube-dl (for grabbing the url and titles) Youtube-DL install instructions https://youtube-dl.org/



Optional:


MKchromecast (for casting the video to your chromecast device) https://mkchromecast.com/#installation

I have included a bunch of sample files to get you started.
