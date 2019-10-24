# Dynamic-gnome-wallpapers
Day night wallpapers for gnome-shell

REDDIT COMMENTS FOR THIS:

https://www.reddit.com/r/unixporn/comments/dlxtlg/gnome_dynamic_wallpaper/?utm_source=share&utm_medium=web2x

Original art : https://dynamicwallpaper.club/wallpaper/jculsb683ok

HOW TO GET THIS :

git repo : https://github.com/b1izzard-34/Dynamic-gnome-wallpapers

This repository has the collection of wallpapers along with the xml files.

Feel free to use the Atacama-timed and Lakeside-timed folders. I havent changed the other files yet.

What you have to do (I'll use Atacama as an exmaple) :

    Create a folder the Atacama wallpapers "Atacama-timed" in /usr/share/backgrounds/gnome .

    Copy all the pictures from the Atacama folder to Atacama-timed.

    Copy the Atacama-timed.xml from Atacama folder to /usr/share/backgrounds/gnome .

    Now go to /usr/share/gnome-background-properties .

    Make a copy of the file adwaita.xml and name it as Atacama.xml

    Open the Atacama.xml and change the path inside the <filename> tag to the path of your .xml file (in this case /usr/share/backgrounds/gnome/Atacama-timed.xml )

    reboot and BINGOO !! you will have your wallpaper in the backgrounds option in gnome-control-center.

There is no need to overwrite Adwaita dynamic wallpaper and no limitation - there is directory with background properties. Just duplicate /usr/share/gnome-background-properties/adwaita.xml to e.g. lakeside.xml, inside change <filename> element content to e.g. /usr/share/backgrounds/Lakeside-timed/lakeside-timed.xml. New theme have to be copied in /usr/share/backgrounds/, I've changed adwaita-timed.xml to lakeside-timed.xml for aesthetic reason but what is important to replace all paths inside this file from like /usr/share/backgrounds/gnome/Lakeside(4).jpeg to /usr/share/backgrounds/Lakeside-timed/Lakeside(4).jpeg. I had to restart Gnome Shell to make it work properly.

I have repo with some wallpaper, you can duplicate it if you want. And at this repo you can find dynamic systemd theme changing. Repo: https://gitlab.com/rejedai/themer.

Alternatively, install this https://flathub.org/apps/details/com.github.maoschanz.DynamicWallpaperEditor, add pictures, save, click on "apply"

