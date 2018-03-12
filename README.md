# KAMP-Installer-Index
This repository is hosted via Github Pages and provides the index for the KAMP Installer by Oomph.   
There are [special KAMP installer](https://github.com/MartinLoeper/KAMP-Windows-Installer) which are configured to used this index. 

### Development KAMP
In order to set up the Develpment KAMP bundle automatically, please do the following steps:

1. Start the KAMP Installer
2. Download the [Configuration.SETUP file](https://raw.githubusercontent.com/MartinLoeper/KAMP-Installer-Index/master/setups/configuration.setup)
3. Drag the downloaded .setup file into the header of the installer

The configuration file chooses the installer's correct options for you. You just have to follow the last few steps and start the installation.

After the KAMP Eclipse distribution launched, wait a few minutes for the setup to finish. There are some post install hooks running inside the fresh Eclipse workspace. They are cloning the KAMP git, running the MWE2 workflow and finally do a build job.