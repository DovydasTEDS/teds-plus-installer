# TEDS Plus Installer
  
You can finally install TEDS Plus with the vanilla launcher automatically!
You can use TEDS Plus installer (which installs itself to your device for future versions), to install TEDS Plus. NOTE: For windows, download the .msi file!

## How to install:
- Download and install TEDS Plus Installer from the releases tab on the right
- Run TEDS Plus installer and select the version to install
- After the installation is complete, open Minecraft Launcher and select TEDS Plus 1.XX.X (Minecraft Version)

## Development Documentation
- Fork this and replace all instances of cdn.tedps.tk with your webserver
- Host a site, using Cloudflare or Github Pages is recommended. DO NOT USE NETLIFY.
- Host these files in the root of your website / http server: [modpacks.json](https://github.com/DovydasTEDS/files/blob/main/modpacks.json) and modpackid-version.mrpack (use [https://github.com/DovydasTEDS/files](https://github.com/DovydasTEDS/files) for reference)
- Build using GitHub actions
  
  # Technical / readme from fork: 

- Multi platform support (Linux, Windows, MacOS)
- Use of mrpack format

[![Build app](https://github.com/dovydasteds/teds-plus-installer/actions/workflows/build.yml/badge.svg)](https://github.com/dovydasteds/teds-plus-installer/actions/workflows/build.yml)

![modpack-installer_gW84mhcolI](https://user-images.githubusercontent.com/35953244/152230478-72eaca95-5cb9-444d-a88a-dcfa4aeb29aa.gif)

![image](https://user-images.githubusercontent.com/35953244/161287776-df9f2cb5-177d-40f0-98d6-aa2def54a6a9.png)

![msiexec_IHxAm26psT](https://user-images.githubusercontent.com/35953244/208211201-80de2308-2611-485a-83f3-88fe2ae8e807.gif)
