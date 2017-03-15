Windows 7 (currently)
=====================
but something is caused by win10 setup, too


initial tips:
- set English as primarily
- set short name: long names will be autoshorted (at least in Win10)

Let's decide, will you use Bash on Windows or babun (cygwin).  
(it's also involve, want you standalone git, or babun's one)

I will go with chocolately and Win10.


=========  Packages =========
=============================

Utils
=====
- `+` for using in my choco script
- `e` for existing but not using
- `-` for not existing

|choco| Type        | Name                   | Description                                 | Link                           |
|-----|-------------|------------------------|---------------------------------------------|--------------------------------|
|  +  | notepad     | Notepad++              | Really useful notepad for all file types    | https://notepad-plus-plus.org/ |
|  +  | disk usage  | WinDirStat             | Disk usage statistics viewer                | https://windirstat.net/ |
| -   | path editor | WindowsPathEditor      | editor for PATH environment variable        | https://rix0rrr.github.io/WindowsPathEditor/ |
|  +  |             | RapidEnvironmentEditor | more complex editor for all env variables   | https://www.rapidee.com |
|  +  | cmake       | CMake gui              | GUI makes cmake much more user-friendly     | https://cmake.org/download/ |
|   e | git         | Git for Windows        |                                             | https://git-for-windows.github.io/ |
|   e |             | Github Desktop         |                                             | https://desktop.github.com/ |
|  +  | archiver    | WinRAR                 |                                             | http://www.win-rar.com/ |
|  +  |             | 7Zip                   |                                             | http://www.7-zip.org/ |
|  +  | system info         | Speccy          | Get you a lot of information about your hardware       | https://www.piriform.com/speccy |
|   e | process explorer    | ProcessExplorer | A bit more advanced tool than standard Task manager    | https://technet.microsoft.com/en-us/sysinternals/processexplorer.aspx |
|   e |                     | Process Hacker  |                                                        | http://processhacker.sourceforge.net/ |
|  +  | dependency explorer | depends         | Show you all dependencies of your dll file | http://www.dependencywalker.com/ |

However very useful will be (as usually) check corresponding Awesome lists:
https://github.com/Awesome-Windows/Awesome

Consoles
======== 
|choco|            |                                                                                   |                         |
|-----|------------|-----------------------------------------------------------------------------------|-------------------------|
|   ? | babun      | wrapper over Cygwin and zsh that brings your oh-my-zsh experience here to Windows | http://babun.github.io/ |
|  +  | Far        | much more than file manager :)                                                    | http://www.farmanager.com/download.php |
|     | PowerShell |

Specific tools
==============
|choco|             |             |                                       |                        |
|-----|-------------|-------------|---------------------------------------|------------------------|
|  +  | merge tool  | Meld        | merge tool with nice GUI              | http://meldmerge.org/  |
|  +  | exif reader | ExifToolGUI | parse exif files                      | http://u88.n24.queensu.ca/~bogdan/ |
| -   | health care | EyeLeo      | keep your eyes healthy (and mind too) | http://eyeleo.com/ |
|unapp| ply viewer  | MeshLab     | view files with 3D models in ply and other formats | http://www.meshlab.net/ |

Compilers
=========
- MSVC (and vcvarsall)
- Microsoft Visual C++ Redistributable 
- MinGW
- JRE

IDE
===
|                         |          |                                     |
|-------------------------|----------|-------------------------------------|
| Microsoft Visual Studio | C/C++/C# |  https://www.visualstudio.com/vs/   |
| JetBrains CLion         | C/C++    |                                     |
| JetBrains PyCharm       | Python   |                                     |

Profiling 
=============
- VLD : Visual Leak Detector (https://vld.codeplex.com/)
- Dr. Memory
- Intel VTune Amplifier

Virtualization
==============
- VirtualBox
- Docker (maybe separate version for Windows)
- Vagrant

Libs
====
Build yourself
- opencv

Let's give it to [hunter](https://github.com/ruslo/hunter):
- eigen
- gflags 
- glog
- gtest
- boost packages
- (opencv also may be comfortable with use through hunter)

Don't need now, so leave it to future
- caffe
- cuda
- cudnn  


Windows feature ?
=================
- Hyper-V
- (do you really need it?) Windows Subsystem for Linux (beta)

Video codecs
============
- K-Lite Codecs
- VLC
- realtek-hd-audio-driver ?