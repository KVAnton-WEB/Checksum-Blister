# Checksum-Blister
KDE Dolphin Service Menus

The Service Menu to **show**, **create file** and **check** the **sha512**, **sha256**, **sha1** and **md5** checksums via right-clicking on any file.

Any of these actions - copies the received **checksum values** to the **clipboard**.

Now you can also perform all these actions with multiple files at the same time. (just select multiple files)


## Installation
Copy the file ```checksum_blister.desktop``` to ```~/.local/share/kservices5/ServiceMenus/``` and ```checksum_blister```(bash) to ```/usr/local/bin/```:

```
cp ./checksum_blister.desktop ~/.local/share/kservices5/ServiceMenus/
sudo cp ./checksum_blister /usr/local/bin/
```

>Of course, you can edit the checksum_blister.desktop to change the location of the bash-script.

## Requires
"*libnotify-tools*", "*xsel*" and the respective *checksum programs*.  


#### Install dependencies in Debian/Ubuntu:
```
sudo apt install libnotify-bin
sudo apt install xsel
```

## Translations
You can help me translate the menu entry to other languages by sending a Pull Request.
