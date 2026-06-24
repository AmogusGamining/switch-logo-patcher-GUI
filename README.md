# Switch Logo Patcher

Creates the IPS patches needed to replace the Switch logo on boot.

The logo you want to change the Switch logo to must be the same size as the original logo, which is 308x350. Anything else and the program won't let you progress.

You don't need to dump the original logo to use this, but if you don't specify the original logo, each patch will be 400+ KiB.<br>
<br>

## Tkinter GUI Usage:
<br>

Download GenP_GUI.exe from [here](https://github.com/AmogusGamining/switch-logo-patcher-GUI/releases/tag/GenP_GUI). <br>
Put the logo in the same directory as .exe file<br>
Run the .exe file <br>
<img width="464" height="224" alt="image" src="https://github.com/user-attachments/assets/e3639ebd-9dc3-48a8-8bd9-7b8139b17334" /><br>
enter the name of the logo in the entry box and press enter<br>
<br>
This will create a folder "logo" in the directory, copy this folder to atmosphere/exefs_patches to change the boot screen<br>
<br>
<br>

## CLI Usage:

```
usage: gen_patches.py [-h] [-o OLD_LOGO] patches_dir new_logo

positional arguments:
  patches_dir           The directory where the generated patches will be
                        dumped
  new_logo              The new logo image

optional arguments:
  -h, --help            show this help message and exit
  -o OLD_LOGO, --old_logo OLD_LOGO
                        The original logo image
```
