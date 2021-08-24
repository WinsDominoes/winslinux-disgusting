# Win's Linux
An indev debian-based linux distribution / respin!
## About
I started this project like 2 months ago by watching YouTube videos from [eznix (Shoutout to him!)](https://www.youtube.com/channel/UCQrSHD-tv9nkssrD4nNGcMw)
and the official debian ISO customization docs [Debian Docs](https://live-team.pages.debian.net/live-manual/)
## Install
You can get the ISOs from the GitHub Releases Page or to the official website download link [Win's Linux Official Website](http://winslinux.winscloud.net)
## Build
To build the distro, I recommend you to visit the `winsdebian-build/docs` directory because it has all of the details (all of these files are written by eznix)
If you want to build (now), follow the steps here
- 1. Clone this repository (`git clone https://github.com/WinsDominoes/winslinux`)
- 2. Instal `live-build`
- 3. Run `sudo bash bldwinsdebian-build` **make sure to use sudo**
- 4. Wait
- 5. You will get another folder called `winsdebian-output` and your files are in there
- 6. There should be an iso called `live-image-amd64-hybrid.iso`
- 7. Done!
### Rebuild
If you want to rebuild it, rm -rf / delete the `winsdebian-output`
*If you get an error saying "Operation not permitted" from some files, please execute this command in root `chattr -i winsdebian-output/chroot/etc/*`
Then redo the 6 steps above!

## Credits
I would like to thank eznix for providing all of the resources [visit his project!](https://sourceforge.net/projects/eznixos/)
