scripts
=======
some scripts that do stuff

####np (now playing)
A now playing script for mpd, designed to be used with an IRC client that allows you to execute shell command and send the output to the server. If it had no output then something went wrong. At the moment it's client agnostic. I might try to make a proper one for weechat and irssi at a later date.
#####Requirements
  * Python 3
  * "python-mpd2" https://github.com/Mic92/python-mpd2

####newall
Selects a random wallpaper from ~/wallpaper/
#####Requirements
 * feh
 * shuf (You might already have this)
 * find (Every distro ever should have this...)
