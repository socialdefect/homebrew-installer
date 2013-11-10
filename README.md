homebrew-installer
==================

Graphical Installer that helps you set-up the HomeBrew or TigerBrew channels on your Mac OSX installation. Using HomeBrew/TigerBrew you'll have access to thousands of Free Open Source Apps to extend your OS. 

This is not an official Homebrew application but just a little tool that will manage
the *Brew installation on your system. It is not a GUI package manager app, after the install
you still need to use the brew terminal commands to install/remove/update software from the
Homebrew repository.

WHY THIS INSTALLER?:

I got a lot of questions from people on how to install tigerbrew. Since this seemed to be
quite difficult to a lot of people (specialy when something goes wrong) I thought; 
why not just make a single click installer to make their lives a little easier. 
The installer also takes care of installing the correct *Brew for your architecture. 
This way you don't have to know if you are using a PowerMac (G3/G4/G5) and therefor 
need TigerBrew or if you are running an x86 based system (Intel) and therefor need HomeBrew.

If you know your architecture and are comfortable using the terminal there is no real need
to use this app.


ONLINE DOCUMENTATION:

The official HomeBrew site: http://brew.sh
HomeBrew GitHub page: https://github.com/mistydemeo/homebrew

The TigerBrew Page: http://www.mistydemeo.com/?p=69
TigerBrew GitHub page: https://github.com/mistydemeo/tigerbrew



INSTALL & USAGE:

To install HomeBrew or TigerBrew just click the .app and wait until it says it's done
installing and running the initial set-up.

Once it's installed open a terminal window (type: terminal in Spotlight) and run:

	brew update   # This will update the repository (do this once a day every time you install an app)

	brew search package-name  # This will search the repo for a package named: package-name

	brew install package-name  # This will install the package named: package-name

	brew upgrade  # Will upgrade all installed brews

	brew upgrade package-name # Will upgrade only package-name
