# gnome-live-wallpaper
Gnome live wallpaper that changes during the day.
![alt text](https://i.imgur.com/D0ePDeQ.gif)

If you want the wallpaper to change during the day, you need to:
* alter the gnome-timed.xml - change absolute path to point the right directory on your disk
* you can do the same changes in timed-test.xml if you need to see check how transition looks like in fast-forward
* use Gnome Tweak tool to change your wallpaper: Appearance->Background->Image to gnome-timed.xml file (or timed-test.xml)
* done

Feel free to use the pictures as static wallpapers if you don't want to bother with script. 
SVG source files included so you might easily adjust them to your taste!

The general concept of the graphic is inspired by some old Gnome wallpaper (low res bitmap), but the whole content is done from zero, using Inkscape.
The scripts are copied from default Gnome live paper
