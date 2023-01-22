# BlackCatMuzzle

## Dark theme for rEFInd with a black cat muzzle on a background

[rEFInd](http://www.rodsbooks.com/refind/) is a simplistic boot manager for UEFI-based systems. This is a clean, dark and cute theme for it.

### Usage

1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind` though it will depend on where you mount your ESP and where rEFInd is installed.

2. Create a folder called `themes` inside it, if it doesn't already exist.

3. Clone this repository into the `themes` directory. To reduce size of the folder delete `screenshots`, `source`, `.git`, `LICENSE` and `README` (if not needed).

4. To enable the theme add the following line at the end of `refind.conf`:
   ```
   include themes/BlackCatMuzzle/theme.conf
   ```

5. You can change the default banner with cat to the fully black one by changing the appropriate line in `theme.conf` like this:
   ```
   banner themes/BlackCatMuzzle/bg/background_empty.png
   ```
    
### Screenshots
![Screenshot with default banner and 2 OSes displayed](screenshots/screenshot_001.bmp "screenshot")

![Screenshot with default banner and multiple boot entries from flash drive displayed](screenshots/screenshot_002.bmp "screenshot")

![Screenshot with fully black banner and 2 OSes displayed](screenshots/screenshot_003.bmp "screenshot")

![Screenshot with fully black banner and multiple boot entries from flash drive displayed](screenshots/screenshot_004.bmp "screenshot")
