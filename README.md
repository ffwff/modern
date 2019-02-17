# login

![Screenshot](/screenshot.png)

a simple login theme for lightdm-webkit2-greeter.

// i should really clean this up

## install

* install `lightdm` and `lightdm-webkit2-greeter`
* clone the repository somewhere
* replace `bg.jpg` with a background image
* replace `bg-blurred.jpg` with a background image with blur (20% gaussian blur is what I used)
* move the repository to `/usr/share/lightdm-webkit/themes/`
* change `webkit_theme` key to `modern` in `/etc/lightdm/lightdm-webkit2-greeter.conf`
* change `greeter-session=lightdm-gtk-greeter` to `greeter-session=lightdm-webkit-greeter` in your `/etc/lightdm/lightdm.conf` file

## how to use?

* move your mouse or press any key to reveal the login screen
* click on your avatar to switch log in user

## credits

* [background image by @yokaibanish](https://www.pixiv.net/member_illust.php?mode=medium&illust_id=72795228)
