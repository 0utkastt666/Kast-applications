# ORBIT apps

created by Outkastt

Downloads and update feeds for the ORBIT apps for Windows. The source code is not in this repo.

| App | What it does |
| --- | --- |
| **ORBIT** | Automatic zip backups, a galaxy of notes, developer tools and one click PC setup. |
| **ORBIT Academy** | Learn on a 3D brain, practise in Labs and take on the Dojo. |
| **ORBIT Code** | A code editor with a live preview that updates as you type. |

## Download

Get the latest version of each app from **https://fivemkastt.com/orbit/** or from the [Releases](../../releases) page here. Each release has a Setup (installs with shortcuts) and a Portable exe (runs without installing).

Once installed, the apps tell you when an update is out. Press **Update** and they install it and restart by themselves.

## First launch

Windows may show "Windows protected your PC" because the apps are not code signed yet. Press **More info**, then **Run anyway**.

## Licence

The apps are proprietary software. Using them means you accept the licence in `LICENSE.txt`, which is also shown in the installer and in each app under About. Third party open source notices ship with each app.

## For the maintainer

Releases are made by **Publish ORBIT update.bat** in the ORBIT Suite source folder. It uploads the installers to a release here and writes the update feeds to `updates/<app>/` here and on the website. This repo must stay **public** so customers can download release files without a GitHub login.
