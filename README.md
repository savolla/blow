# blow
### (low-battery notifier)

---

![meme](https://i.pinimg.com/736x/42/73/c4/4273c4aec0cfe16658d6adb9bfd61ef5.jpg)

+ An experimental script for notifying **low battery** written in bash.
+ This script is actually created mostly for WM users.
+ As we know that most WMs do not warn us on low battery levels and this causes a lot of problems sometimes.
+ This also works on tty terminals without X if you use ssh or something.

I hope this little script will help you to solve those problems :)

you can customize things at **VARIABLES** section. Set your personal wave, mp3 file to play when your battery decreases to $CURRENT_BATTERY_VALUE. You can also use commands like i3-nagbar instead of ringing a sound or even *espeak* :v

You can also find more interesting sounds on [This Website](https://freesound.org) for free.

### Installation

---

installation? All you need to do is make it run at startup and enjoy!

To start the script at startup use;
* WM config file
or
* .xinitrc
or
* ~/.config/autostart/

don't let your data being lost :)

written by savolla.
