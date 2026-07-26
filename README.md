![alt text](Before.png)
![alt text](After.png)

# Icon-for-FadeIn
FadeIn is a powerful and well reputed screenwriting software for Mac, Windows, and Linux. When installing it on immutable Linux distros like Bazzite, Bluefin, or Fedora Silverblue it requires a distrobox container, which does't effectively produce an application icon. This is an icon so it can be properly displayed in your GNOME dash. 

**NOTE:** The specific placement of the icon may vary system to system or based on how your desktop environment organizes elements like this. Any alternate installation instructions are most welcome. This icon was built to be used for the GNOME image of Bazzite.

---

# How to Install

## GNOME

1. Open Nautilus file manager and navigate to the Home.
2. Crtl+H to reveal hidden folders
3. Navigate to .local>share>appplications and open the FadeIn desktop entry: "Fadein.desktop"
4. Open it in your preferred text editor and locate the line: Icon=/home/excelsior/.local/share/icons/distrobox/fedora.png that is the location of the false icon.
5. Rename is this to: Icon=/home/excelsior/.local/share/icons/distrobox/fadein-icon.svg
6. Locate the path: /.local/share/icons/distrobox and place the icon there.

---

## Status & Contributing

This effort is totally unaffilitated with FadeIn and since FadeIn does not or not yet have a flatpak option, I've created this so the application feels at home on my Bazzite desktop. 
