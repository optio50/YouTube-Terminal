Watch Youtube Videos without going to the youtube site.
This script is faster than going to youtube and selecting your video of interest.
These files will fetch the latest 99 videos (or whatever # you want) and display it to you in the terminal.
Make your selection and the video will open on your local screen or a chromecast device. (MPV used for local & MKchromecast used for casting).
A menu is also included to simplify the process. The menu script will automatically and instantly see all files with the ".menu"
extension and display the choices on your screen. The menu is not limited to running the youtube script files,
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

ABC-news.menu
Adrian-Rogers.menu
AP-news.menu
BBC-Earth.menu
BBC-news.menu
CBC-news.menu
CBS-news.menu
CNET.menu
CNN-news.menu
DistroTube.menu
Duck-Commander.menu
Duck-Dynasty.menu
Euronews.menu
Foxnews.menu
FPS-Russian.menu
France24.menu
Golf-Channel.menu
Greg-Laurie.menu
Hikok45.menu
History.menu
Joe-Rogan-Experience.menu
MovieClips.menu
MSNBC-news.menu
NASA.menu
NASCAR.menu
NBA.menu
NBC-news.menu
NFL.menu
NHL.menu
NOVA.menu
OANN.menu
PBS-news.menu
PGA-Tour.menu
PhoneArena.menu
Raptor.menu
RedBull.menu
SKYnews.menu
SpaceX.menu
Twit.menu
XDA.menu
