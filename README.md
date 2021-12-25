# AC-DC Thunderstruck
AC-DC well know ThunderStruck

### USB flash drive requirements
- Must contain a base-level folder called "LightShow" (without quotation marks and case sensitive).
- The LightShow folder must contain 2 files:
  - "lightshow.fseq"
  - "lightshow.mp3" or "lightshow.wav" (wav is recommended)
- Must be formatted as exFAT, FAT 32 (for Windows), MS-DOS FAT (for Mac), ext3, or ext4. NTFS is currently not supported.
- Must **not** contain a base-level TeslaCam folder.
- Must **not** contain any map update or firmware update files.
### Running the custom light show on a vehicle
- Insert the flash drive into one of the front USB or USB-C ports, or glovebox USB port, then wait a few seconds.
- In Toybox, select Light Show and tap Start The Show. If the files on the USB flash drive meet the requirements, then the custom show will be used instead of the built-in show.
- As the custom light show loads, the status at the bottom of the popup cycles through "Loading lightshow.fseq" and "Loading light show...". When the status becomes "Light show ready!", you can exit the vehicle and the custom show will start.