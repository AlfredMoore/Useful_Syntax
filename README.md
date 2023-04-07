# Ubuntu_Useful_Syntax
Learning skills from daily projects_Unscheduled update

Unzip
======
```
unzip -n src_path -x dest_path
```
-n: extract not existing.

When unzip a very large file(like 30+GB), use this to continue extracting in case of "not enough memory"

-x: dest path

Wget
=====
```
!wget -O dataset/fma_metadata.zip -nc https://os.unil.cloud.switch.ch/fma/fma_metadata.zip 
```
-O: directed dest, including file name
-nc: not covering existing files

Goole Colab
=====
* link to google drive
```
from google.colab import drive
import os
root_path = "/content/drive/MyDrive/dest_path"
drive.mount('/content/drive')
os.chdir(root_path)
```
the bash commands below are now all under root_path
```
!ls
!pwd
!git clone
```

