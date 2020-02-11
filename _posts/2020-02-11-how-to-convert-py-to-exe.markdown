---
layout: post
title:  "How to convert .py to .exe?"
date:   2020-02-11 02:03:36 +0530
categories: Python Windows
---
[Auto Py To Exe][auto-py-to-exe]  
A .py to .exe converter using a simple graphical interface built using [Eel][Eel-docs] and [PyInstaller][PyInstaller-docs] in Python


## Prerequisites:
* Python : Python >= 2.7 ( including 3.7 🎉 )

## Installing:
* pip install auto-py-to-exe

## Running:
* auto-py-to-exe

![Auto-py-to-exe](https://warehouse-camo.cmh1.psfhosted.org/cfa7fc5851ea165ad9a0385f06d6fc5499d47b90/68747470733a2f2f692e696d6775722e636f6d2f4575556c6179432e706e67)

## How to use:
1. Select your script location (.py) (paste in or use a file explorer)  
Outline will become blue when file exists
2. Select **One Direction** or **One File** option
3. Select orther option (icon)
4. Select additional files, folders
5. Click the big blue button at the bottom to convert
6. Find your converted files in /output when completed

**One Direction** option:
Pretty simple. When choosing "One Direction" option, auto-py-to-exe will put all dependencies in **one folder**. If you have media files like icons, images, videos, databases ..., you should choose "One Direction".

**One File** option
auto-py-to-exe will create one .exe file, containing all dependencies.

![auto-py-to-exe build](https://warehouse-camo.cmh1.psfhosted.org/d2f89e7dfcbbd3635e0f098b43dbc9df7c74b7a4/68747470733a2f2f692e696d6775722e636f6d2f663354456e5a492e706e67)

![auto-py-to-exe running](https://warehouse-camo.cmh1.psfhosted.org/a71bb45213b2285ac68eedc2994709c478deb12d/68747470733a2f2f692e696d6775722e636f6d2f4d6a644f4e63432e706e67)


[auto-py-to-exe]: https://pypi.org/project/auto-py-to-exe/
[Eel-docs]: https://github.com/ChrisKnott/Eel
[PyInstaller-docs]: http://www.pyinstaller.org/
