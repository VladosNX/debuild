# DeBuild V1.2
DEB-file builder for Ubuntu
***
![Screenshot](https://i.ibb.co/Qb7MccL/2022-08-31-22-28-44.png)
***
DeBuild is a program which can help you to build .deb package for Ubuntu.
## Usage
To build .deb package, run this command:
> debuild

Then enter package name, version, etc.
## Changelog
### V1.1
* Built-in editor added
### V1.2
* Now you can build XLP-packages!

## Future versions
### V2.0
* GUI will be added!

## Installing DeBuild
First you need to install XLPM. Run this command:
> wget raw.githubusercontent.com/vladosnx/xlpm/main/xlpm-1.1.2.deb; sudo dpkg -i xlpm-1.1.2.deb

After installing XLPM you can install DeBuild. Run this command:
> sudo xlpm -g vladosnx/debuild

Ready!

## Updating DeBuild
If you want do update DeBuild version, run this command:
> sudo xlpm -r debuild; sudo xlpm -g vladosnx/debuild

DeBuild will be automatically updated.
