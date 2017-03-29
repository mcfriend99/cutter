# Iaitō

> The GUI that ~~radare2~~ humans deserve

A Qt and C++ GUI for radare2 reverse engineering framework

## Disclaimer

Iaitō is not aimed to the already existing radare2 user, it is focused on those whose are not yet radare2 users because of the learning curve, because they don't like CLI applications or because of the difficulty/inestability of radare2.

## The code sucks

Yes, the code sucks. Hopefully we will be able to remove this statement from the README one day, but I had never coded Qt nor C++ until I started Iaitō, so obviously the code is ugly and not well designed.

## Requirements

- **Radare2**: It is important that all Iaitō developers use the same version of radare2. For that purpose all developers must install radare2 from [this fork](http://github.com/hteso/radare2-iaito). Install radare2 with the following command:
```
sys/install.sh
```
- The **www-p**: Once you have radare2 installed use the following [r2pm](https://github.com/radare/radare2#package-manager) command to install this webUI:
```
r2pm -i www-p
```
- QtCreator and Qt: Right now, Iaitō uses Qt 5.3 so the latest QtCreator needs to be installed and Q t5.3 added during the installation:
    - Download: https://www.qt.io/ide/
    - Add Qt 5.3: http://doc.qt.io/qtcreator/creator-project-qmake.html

## Platforms

Iaitō is developed and tested in OS X and Linux, Windows will be added soon. The first release for users will include installers for all three platforms.

## Documentation

Proper documentation and website will be created before the first release.
