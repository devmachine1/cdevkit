# cdevkit - Barebones for your Windows C Development Setup

PLEASE READ THE WHOLE README FILE !!!
NOT RECOMMENDED FOR BEGINNERS!!! LEARN LINUX AND C BEFORE USING THIS!!!

cdevkit is a barebones development enviroment which you can configure to your likings. The terminal (cmder) and the editor (neovim) can be configured. Please note that this setup uses tcc instead of GCC/Clang because tcc is way lighter, faster and has all I need as a casual programmer. You can get GCC/Clang binaries from [winlibs](https://winlibs.com/) and replace the binaries with the TCC ones, or you could install the binaries system wide by adding the winlibs binaries to path(there are other possibilities too).

## List of Softwares being used
* [GOW (Linux Commandline Applications)](https://github.com/bmatzelle/gow)
* [cmder (Console Emulator)](https://cmder.app/)
* [TCC (C Compiler)](https://bellard.org/tcc/)
* [Neovim (Editor)](http://neovim.io/)

I strongly recommend to checkout these softwares and what they do. If you are totally unaware of cmder and/or neovim, read the documentation in their specific websites. I recommend [SpaceVim](https://spacevim.org/) as the neovim config as it is easy to install and easy to use. 

## Build this on your own

As I am only going to do monthly updates, i recommend downloading the latest release and then patching it. This can be done by replacing the old files with the new ones, ex. when the cmder version gets outdated, I would download the latest release from their website (the mini version) and just drag the files inside the extracted cdevkit release, then the old files will be automatically replaced with the new ones. Its the same for GOW and TCC, only difference is that you put them in the bin folder(So copy all the files in the bin folder in GOW and paste it into the cdevkit bin folder and for TCC/GCC/Clang just copy the whole binaries extracted zip file and paste it into the cdevkit/bin folder).
