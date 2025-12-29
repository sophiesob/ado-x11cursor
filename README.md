# ado-x11cursor
X11 Cursor based on 乱涂乱画BEN's animated Ado cursor. All credits go to him for the original art and Windows cursors: https://ko-fi.com/s/100d037321

# Install
Extract the root folder (the one named "Ado") on **either**:
- /home/(user)/.icons
- /home/(user)/.local/share/icons

Select the cursor and apply on System Settings -> Colors & Themes -> Cursors, *or*, select and apply with [nwg-look](https://github.com/nwg-piotr/nwg-look).

## On hyprland:
Add the following lines to **/.config/hypr/hyprland.conf**:
```
env = HYPRCURSOR_THEME,Ado
env = HYPRCURSOR_SIZE,32
exec-once = hyprctl setcursor Ado 32
```

Log out and log back in for the cursor to appear.

## IMPORTANT: FOR NVIDIA USERS
Add the following line to hyprland.conf:
```
env = WLR_NO_HARDWARE_CURSORS,1
``
