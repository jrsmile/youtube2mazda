# youtube2mazda
youtube-dl configuration script for easy geration of mp4 videos to be played via mazda connect (MZD) via USB-Stick.

requirements:

youtube-dl:

sudo curl https://yt-dl.org/downloads/2016.05.16/youtube-dl -o /usr/local/bin/youtube-dl
sudo chmod a+rx /usr/local/bin/youtube-dl

polipo ( to convert ssh socks proxy in http proxy):
apt-get install polipo

a ssh server somewere to bypass geo block.
