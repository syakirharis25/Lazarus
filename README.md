# Lazarus
My works related to Lazarus cross-platform visual integrated development environment (IDE) for rapid application development (RAD) using the Free Pascal compiler.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Free Pascal.](#freepascal)
4. [Starting Lazarus in Microsoft Windows environment.](#starting)
5. [Shortcuts.](#shortcuts) 
6. [GitHub notes.](#github)

<a name="introduction"></a>
## 1. Introduction.
<img src="Lazarus-cheetah.png" height="200"> 
Lazarus is a Delphi compatible cross-platform IDE for Rapid Application Development. It has variety of components ready for use and a graphical form designer to easily create complex graphical user interfaces. Delphi is an event-driven programming language based on Object Pascal and an associated integrated development environment (IDE) for rapid application development of desktop, mobile, web, and console software, currently developed and maintained by Embarcadero Technologies.
<br /><br />
Lazarus is a free cross-platform visual integrated development environment (IDE) for rapid application development (RAD) using the Free Pascal compiler. Software developers use Lazarus to create native-code console and graphical user interface (GUI) applications for the desktop, and also for mobile devices, web applications, web services, visual components and function libraries for a number of different platforms, including Mac, Linux and Windows.
<br /><br />
An application created using Lazarus on one platform can generally compile and execute on any platform for which a Free Pascal compiler exists. For desktop applications a single source can target Mac, Linux, and Windows, with little or no modification. An example is the Lazarus IDE itself, created from a single code base and available on all major platforms including the Raspberry Pi.

<a name="references"></a>
## 2. Official references websites. <br />
Lazarus official website : https://www.lazarus-ide.org <br />
Lazarus IDE installer website : https://www.getlazarus.org <br />
Lazarus forum : https://forum.lazarus.freepascal.org/index.php?action=forum <br />

Free Pascal official website : https://www.freepascal.org <br />
Free Pascal GitHub installer releases : https://github.com/LongDirtyAnimAlf/fpcupdeluxe/releases <br />

<a name="freepascal"></a>
## 3. Free Pascal.
Free Pascal Compiler (FPC) is a compiler for the closely related programming-language dialects Pascal and Object Pascal. It is free software released under the GNU General Public License, with exception clauses that allow static linking against its runtime libraries and packages for any purpose in combination with any other software license.
<br /><br />
It supports its own Object Pascal dialect, as well as the dialects of several other Pascal family compilers to a certain extent, including those of Turbo Pascal, Delphi, and some historical Macintosh compilers. The dialect is selected on a per-unit (module) basis, and more than one dialect can be used per program. Modular programming is a software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.

It follows a write once, compile anywhere philosophy and is available for many CPU architectures and operating systems (see Targets). It supports inline assembly language and includes an internal assembler capable of parsing several dialects such as AT&T and Intel style.

Separate projects exist to facilitate developing cross-platform graphical user interface (GUI) applications, the most prominent one being the Lazarus integrated development environment (IDE). Free Pascal Compiler (FPC) supported operating systems include Linux, FreeBSD, Haiku, Mac OS X/iOS/iPhoneSimulator/Darwin, DOS (16 and 32 bit), Win32, Win64, WinCE, OS/2, MorphOS, Nintendo GBA, Nintendo DS, Nintendo Wii, Android, AIX and AROS.

<a name="starting"></a>
## 4. Starting Lazarus in Microsoft Windows environment.
To start the Lazarus IDE, you should start from `C:\installation_folder\lazarus\startlazarus.exe` to avoid any conflict in the future, or **[ Mouse Double Click ]** on the created Lazarus shortcut on your desktop.

<a name="shortcuts"></a>
## 5. Shortcuts.
**[ Fn ]** + **[ F12 ]** : open form designer menu <br />
**[ Ctrl ]** + **[ Alt ]** + **[ P ]** : open command pallete <br />

<a name="github"></a>
## 4. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Lazarus.git
$ cd Lazarus/
$ git remote -v
$ git status
```

GitHub markdown-cheatsheet by tchap : https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md
