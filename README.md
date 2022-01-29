# Brightness Script
Small bash script to set brightness of a backlight via the command line
## How to install
Download with 
```
$ wget https://raw.githubusercontent.com/Legati0/brightness/main/brightness -P /usr/bin/
$ chmod +x ./usr/bin/brightness
```
open the file with your favored text editor and change the `device` variable according to your needs
## Usage
### Get current brightness
Print current brightness and max brightness value 
```
$ brightness
```
### Set brightness
Sets brightness to value x
```
$ brightness x
```
Add/Sub value from brightness (will not go below 0 or exceed max value)
```
$ brightness +x
$ brightness -x
```
