# Tasks over the Easter Vacation

## Software Subteam

I understand you'll be very busy over the holidays, but there's a fairly low-commitment software task that you can look into if you're bored. This should help bring you up to speed with the current state of the software and understand how relevant algorithms work.

Firstly, if you haven't yet created a github account/sent me your username please do so and let me know whether you want to work on the CNC team, field optimisation team, or both.

You'll be part of a team within the CUSBS github organisation, which will give you write access to relevant repos. Also have a look at the [igem15-sw repo](https://github.com/SynBioSoc/igem15-sw) which contains all the software written to date.

Choose one repo within your team that interests you and try to find the relevant code in igem15-sw. Your task will be to migrate this code into one of the openscope repos so it is self-contained (including adding any library/module boilerplate code). In the process, you should try to understand the structure and algorithms of the code.

The current state of the code is a bit messy, so feel free to message Will, Souradip or Ocean if you're struggling to find the code or understand it. We can send through some illuminating comments, or relevant tutorials regarding libraries we used.

You might also find it useful to install OpenCV version 3 for python. This is what we use for most image processing. It's not the most trivial package to install... here are some generic instructions, but contact Will for help if needed:

* Linux - http://docs.opencv.org/3.0-beta/doc/tutorials/introduction/linux_install/linux_install.html#linux-installation
* Windows - http://docs.opencv.org/3.0-beta/doc/tutorials/introduction/windows_install/windows_install.html#windows-installation
* Mac - install [homebrew](brew.sh), a good OS X package manager (macports/fink/... might also work); then run `brew install homebrew/science/opencv3` in the terminal
