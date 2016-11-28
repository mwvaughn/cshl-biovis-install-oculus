# Configuring Your Oculus Development Environment

As part of this workshop, you will create accounts at several services. Please use an email address you will always have access to (we recommend using your professional email) and please also choose a very strong, unique password for each service. In some cases (Unity and Oculus especially) you may (optionally) link your account to a means of payment for purchases. Thus, you want to protect those accounts as strongly as possible.

## Oculus Home

Oculus Home is an application for interacting with "officially sanctioned" Oculus applications and for configuring/testing Oculus hardware components.

1. Create an [Oculus Home account](https://secure.oculus.com/sign-up/?login_redirect_uri=https%3A%2F%2Fwww.oculus.com%2F)
2. Download the Oculus Home installer. There is also a copy in your computer's *Installers* directory.
3. Click on *OculusSetup.exe* and follow the on-screen directions.
4. Towards the end of the process, you will put on the Oculus headset and use the Oculus Remote, so make sure to have them nearby and ready.

## Oculus Software Development Kit


## Leapmotion Orion

"Orion" is the working name for Leapmotion's detection and response software on Windows.

1. Download [Orion](https://www.leapmotion.com/setup) from the Leapmotion web site. There is also a copy of the installer (Leap_Motion_Setup_Win_3.1.3.exe) in your local Installers directory.
2. Click on the Installer and follow the on-screen instructions.

## Leapmotion Software Development Kit

1. Go to the [Leapmotion Developers' Site](https://developer.leapmotion.com/get-started)
2. Download [Orion Beta](https://central.leapmotion.com/users/sign_in?use_iframe=true&developer=1) software development kit. You will be asked to provide account information. If you did not create a Leapmotion account as part of setting up the Leapmotion system, you should do so now. There is a copy of the Orion Beta SDK installer (Leap_Motion_SDK_Windows_3.1.3.zip) in your Installers directory.

## Unity3D

[Unity](http://unity3d.com) is a popular, user-friendly software platform for building rich, interactive games and multimedia experiences. In recent years, it has been enhanced to empower you to develop multi-platform VR and AR applications.

1. Go to the Unity3D home page. Click on the profile icon in the top right corner and follow the instructions to create a Unity ID. This user account will hold your (free) Unity license and will be a gateway towards publishing and using "assets" on the Unity Store. It is also needed if you choose to upgrade your Unity license with additional functionality in the future.
2. Click on the *Unity Download Assistant* (currently UnityDownloadAssistant-5.4.3f1) and follow the instructions
3. Launch Unity3D and install the licence locally (instructions TBD). This ensures that even if you don't have Internet access you will be able to develop using Unity3D.

## Steam and SteamVR

[Steam](https://store.steampowered.com/) is a gaming platform. [SteamVR](https://steamcommunity.com/steamvr) is an extension to it enabling installation and usage of games that support HTC Vive (Steam's HMD of choice), Oculus Rift, and possibly other systems in the future. It's not needed for much in our workshop, save to activate the VR function of ChimeraX, but we need to install it anyway.

1. Sign up for a [Steam account](https://store.steampowered.com/join/?)
2. Install Steam and enter your account credentials
3. Configure SteamVR from within the Steam applications.
4. Search the library for *DEMO*, load it into Steam, and ensure that you're able to activate SteamVR functions.

## Firefox Nightly

Firefox is a free and open web browser developed by the [Mozilla Foundation](https://www.mozilla.org/en-US/foundation/) and its associated community. It currently offers the best implementation of the emergent [WebVR](https://webvr.info) standard via its *Firefox Nightly* product. Nightly is a "bleeding edge" release of Firefox that includes bug fixes, new features, etc. that have been added to the Firefox source code in the last day or two. Eventually, code that tested in Firefox Nightly becomes part of the [official Firefox release](https://www.mozilla.org/en-US/firefox/products/) used by the general public.

1. Download the 64-bit Firefox Nightly Installer for Windows from the [Nightlies site](https://nightly.mozilla.org/). The version from 11/27/2016 is available in your Installers directory as well.
2. Install Firefox Nightly
3. Open the *Options* panel [Screenshot](assets/ff1.png)
4. Un-check the box that reads "Enable multi-process Nightly" [Screenshot](assets/ff2.png)
5. Set Firefox Nightly as the default browser for Windows [Screenshot](assets/ff3.png)

### Activating Firefox Nightly + Oculus Integration

Because WebVR, Firefox, and Oculus are independent (and in some cases  very early-stage) software projects, compatibility can be a challenge. As of 11/27/2016, here's the sequence of events needed to initialize a Firefox WebVR session.
* Close Firefox Nightly
* Close Oculus Home and re-open it
* Put on the Oculus Rift headset long enough to display the Home application
* Re-launch Firefox Nightly and navigate to a WebVR site you want to explore. We suggest this example to verify that the headset and browser are working together: URL
* Click the [Enter VR] button and put on the Oculus headset.
* To swap between WebVR sites, you should be able to take off the headset and navigate to another WebVR application. If that fails for some reason, follow this checklist again.

_Don't get discouraged. The tools surrounding WebVR development are aimed at professionals who are well aware of the technology's quirks and annoyances but... better integration and improved ease of use is coming. After ~2m headsets show up over the winter holidays, expect a lot more incentive and effort focused on user experience._

## GitHub Desktop

We will use [GitHub](https://github.com) for collaborative coding and development. To streamline the experience for newer developers, we are using a desktop client for Git called *GitHub Desktop*.

1. Sign up for (if you don't have one) a [GitHub account](https://github.com/join?source=header-home)
2. Download the [GitHub Desktop installer](https://github-windows.s3.amazonaws.com/GitHubSetup.exe). A recent version is also available in the Installers directory on your computer.
3. Click the *GitHubSeup.exe* file and follow the instructions.
4. Launch the GitHub Desktop program and configure it by logging into your GitHub account and setting your local name and email address [Screenshot 1](assets/git1.pmg) [Screenshot 2](assets/git2.png)

## Atom Code Editor

[Atom](https://atom.io) is a free, extensible text editor that a lot of people use for writing software for the web. It supports syntax highlighting, which is really helpful when one is learning a new language or framework, and integrates with GitHub.com. It's also better than using Notepad.exe for developing software - please never do that!

1. Go to the [Atom home page](https://atom.io) and sign in with your GitHub account
2. Download the [Atom installer for Windows](https://atom.io/download/windows). There is a local copy in your Installers folder as well.
3. Click on the *AtomSetup.exe* application and follow the instructions to install it.
4. Launch Atom application and poke around. There is a set of plugins to choose from, including some that let you change the color scheme for Atom to suit your preference.

## Python language

[Python](https://www.python.org/) is a very useful language for data processing and manipulation, as well as for general computation, and it's very commonly used in science. You can even use it for writing GUI applications and web applications!

Python has two major versions: 3.5 and 2.7. If you're new to Python, jump in and learn 3.5. If you are an old hand or have extensive Python 2.7 code, you can use 2.7. The two versions are largely similar, but 3.5 has a lot of new functions and has fixes (that break backwards compatibility) for some of the weird or annoying aspects of 2.7. We'll use Python 2.7 in this workshop, but we've tried hard to make the code forward-compatible.

On Mac OS X or Linux, Python is installed by default. On Windows, it must be installed as an application. Python itself is free and open source, but many people use the "Anaconda" distribution from [Continuum Analytics](https://www.continuum.io/) because it adds extra functionality (like being able to easily install Python modules and having an IDE).

1. Download the Windows 64-bit installer from Continuum Analytics. There is also a copy of each in your Installers folder. Links: [Python 2.7](https://repo.continuum.io/archive/Anaconda2-4.2.0-Windows-x86_64.exe) | [Python 3.5](https://repo.continuum.io/archive/Anaconda3-4.2.0-Windows-x86_64.exe)


## Applications and Utilities

Copies of all these downloads are in the Installers folder on your workshop computer.

### ChimeraX



### 3d Slicer

[3D Slicer](https://www.slicer.org/) is a free cross-platform open-source medical image processing and visualization system. It has been supported by multiple grants from the US National Institutes of Health (NIH) over almost two decades, and brings powerful medical image processing, visualization, and data analysis tools within reach of everyone.

* Download [Slicer-4.6.2-win-amd64.exe](http://download.slicer.org/bitstream/561640)

### Meshlab

[MeshLab](http://meshlab.sourceforge.net/) is an open source, portable, and extensible system for the processing and editing of unstructured 3D triangular meshes. The system is aimed to help the processing of the typical not-so-small unstructured models arising in 3D scanning, providing a set of tools for editing, cleaning, healing, inspecting, rendering and converting this kind of meshes.

At minimum, it's a useful converter for:
* import:PLY, STL, OFF, OBJ, 3DS, COLLADA, PTX, V3D, PTS, APTS, XYZ, GTS, TRI, ASC, X3D, X3DV, VRML, ALN
* export:PLY, STL, OFF, OBJ, 3DS, COLLADA, VRML, DXF, GTS, U3D, IDTF, X3D

* Download [MeshLab_v133_64bit.exe](http://downloads.sourceforge.net/project/meshlab/meshlab/MeshLab%20v1.3.3/MeshLab_v133_64bit.exe?r=http%3A%2F%2Fmeshlab.sourceforge.net%2F&ts=1480338802&use_mirror=heanet)

### Blender3D

[Blender](https://www.blender.org/) is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, even video editing and game creation.

* Download [blender-2.78a-windows64.msi](http://ftp.nluug.nl/pub/graphics/blender/release/Blender2.78/blender-2.78a-windows64.msi)

### Docker for Windows (Optional)






Last Updated: 11/27/2016
