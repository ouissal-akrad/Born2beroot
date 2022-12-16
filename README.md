# Born2beroot
Study record
Virtual Machine :
  . Software that emulates another computer in a virtual environment that behaves like a computer within a computer.
  . Born to use one physical server more efficiently.
  . The software used is limited by the environment and resources provided by the virtual machine and cannot escape from the virtual world.
  . All functions of all parts are implemented in software. Best in versatility.
  . A technology that enables multiple operating systems to run on a single physical server.
  . Provides a UI to a virtual machine that is similar to, but not identical to, the underlying hardware and software.
  . If you want to run two or more different operating systems on one computer at the same time.
Difference between Rocky and Debian :
  . Rocky :
    . Rocky Linux is a free distribution for Linux, which is based on Red Hat Enterprise Linux and is intended to replace CentOS.
    . Linux distribution.
    . Supported by RedHat.
    . Since it is open source, updates are slow. Technical support too.
    . No easy GUI.
  . Debian :
    . Operating system as an open source component.
    . Created and distributed by online communities.
    . Linux as Kernel.
    . has many packages.
    . Ease of upgrade.
    . It has a desktop-friendly GUI.
 Difference between apt and aptitude :
  . apt :
    . apt is used to download and install packages from online repositories.
    . Actually apt works with dpkg. However, most package management tasks such as searching for necessary software, downloading, installing, upgrading, and checking can be done with apt alone.
    . Free, open-source software that gracefully handles software installation and uninstallation.
    . Initially designed for Debian, but made compatible with RPM package managers.
  . dpkg :
    . dpkg is commonly used to control .deb files on cdrooms or other disk devices. The dpkg command has options used to set up or install system software and get information about it. It runs at a lower level than apt. apt uses dpkg internally to manage Ubuntu's software. Usually, the apt command is sufficient, but the dpkg command is needed to perform tasks such as checking which packages contain certain files on the system.
  . aptitude :
    . In the case of dpkg and apt, more knowledge is required to use them properly. In comparison, aptitude makes it easier because it automates key packaging workflows to make things as easy as possible. It can also automatically remove unused packages. In addition to apt-get, tools such as apt-chche and apt-mark are also used. aptitude provides alternatives in case of conflicts during installation, uninstallation or update process. apt just says no.
    . High-level package manager.
    . Suggests appropriate action in case of conflict during package installation or deletion.
    . Automatically remove unused packages.
 What is APPArmor :
  . AppArmor is an application that allows system administrators to limit a program's capabilities per program profile. 
  . App Armor allows which applications can access which files/paths through policy files.
  . A Linux kernel security module that allows system administrators to limit a program's capabilities per program profile.
  . Products like CentOS and derivatives use SELinux, most others use APPArmor.
  . There are two modes, enforce mode and complain mode. Enforce mode denies access to unauthorized files, complain mode does not actually provide security, and App Armor leaves a log when the application does something other than what it should do.
  . Concentrate on protecting individual applications and implement an application-level security model.

