# ShowImageLive

Show the latest image of a device saved in the scan data, and update it every second.
This is useful when you want to see the live image taken during a scan, like a camera GUI.
HTU team uses this code to look at .tif images Phasics takes during a scan.

## How to run
Open the script, give appropriate scan date folder (dir_date) and device name of images you want to see (device_name) in the main function.
Run with python. Commandline: `python ScanInfoTable.py`, or right click the file and choose **open with python**.

* Or you can also directly use a function `showimg_live(dir_date, device_name)`.

updated on May 11, 2020
Fumika Isono fisono@lbl.gov, fumika21@gmail.com
