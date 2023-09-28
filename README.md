# Prerequisites

Python 3   
MySql    

# dofusfashionista
The Dofus Fashionista, an equipment advisor for Dofus    
This is a fork and an attempt at putting back up the website

## Install and Run Fashionista:

Linux :     
$ git clone https://github.com/Trameurs/DofusFashionista.git fashionista  
Add "export PYTHONPATH=/home/<\<user\>>/fashionista/fashionistapulp" at the end of ~/.bashrc  
$ chmod 777 fashionista  
$ chmod 777 fashionista/fashionistapulp/fashionistapulp  
$ cd fashionista  
$ sudo ./configure_fashionista_root.py -i -s -d  
$ ./configure_fashionista.py  
$ sudo ./run_fashionista.sh  

Windows :     
$ git clone https://github.com/Trameurs/DofusFashionista.git fashionista   
Add "C:\Users\YourUsername\fashionista\fashionistapulp" to your "Environment Variables" section "User variables" with the variable name "PYTHONPATH"    
Run the "CMD" as administrator    
$ cd fashionista    
$ python configure_fashionista_root.py -i -s -d    
$ python configure_fashionista.py    
$ run_fashionista.bat    

# Reference

This is a fork of https://github.com/PiwiSlayer/DofusFashionista.git

# Note   
   
So many things are broken I can not list all prerequisites or explain all the steps for installation, I added a requirements.txt to help     
I suggest you to use Python 2 and try to get it to work with outdated packages directly from the original repository : https://github.com/PiwiSlayer/DofusFashionista.git    
This fork should be somewhat working with Python 3, up to date packages and Windows (I kept Linux compatibility), but not everything in the code is updated and expect a lot of bugs (if you can even make it to work)    
Abandonning this fork as is    

# What's next?   

Moving to https://github.com/Trameurs/DofusFashionistaVanced     
If you want to check progress or help with the project, feel free to visit the new repository for DofusFashionistaVanced !     
First step will be to put the site back up on the latest version of Dofus    
I plan on including new features like auto-build with legendary equipment, budget (price of items), Dofus retro and more    
