# scripts
Useful scripts 



## Installing opencv 
The script named opencv_installer.sh is a script that install the neweste version of opencv. As defualt is it installing opencv-contrib with the nonfree modules. Run the following command and the script does the rest. 
``` bash 
sudo bash opencv_installer.sh
```
This scripts creates a local folder, that can be remove after the installing is done. But the folder is need when uninstalling opencv. In order of uninstalling navigate to the subfolder build and run following command 
``` bash 
sudo make uninstall
```
