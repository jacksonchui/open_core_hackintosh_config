# My Hackintosh Pro

## Description
My OC folder (minus my serial) of my Hackintosh (Ryzen 3700x, 32GB DDR4, PowerColor Vega 64, 1TB SSG 970 Pro).
This config is based off the MacPro7,1 (the latest Mac Pro). It enables better compatibility with more GPUs, including the AMD rx5700(xt).
I am running macOS Catalina 10.15.2. I have it working in a triple boot with the other 2 OS (Windows 10 Pro, Ubuntu 19.10) installed on another SSD. I installed Windows first and then Ubuntu over it since Windows doesn't handle overwriting the Ubuntu EFI gracefully.

## Specs
CPU: Ryzen 7 3700x
Mobo: Gigabyte x570 Aorus Elite (no wifi)
RAM: Corsair Vengeance RGB Pro 3200 MHz DDR4
GPU: PowerColor AMD Vega 64
Storage: 1TB Samsung 970 Pro (2-bit MLC)

## Working:
Everything but proper sleep.

## How I Work around Sleep

Go to `System Preferences/Energy Saver` and change `Turn computer off after:` to `Never`, `disable` `put hard disks to sleep when possible`, and `disable` `Power Nap`.

I have a keyboard, mouse, and 3 cables I use for charging plugged in. Haven't had a problem with it randomly waking up in the middle of the night. I would also go about tuning the fan curve either with your Windows software or what I did in the bios. I have 6 fans and they run at under 5% under 45C (which it is at most of the time).

## My Favorite macOS Apps

Apps that I use often on my Mac. I make sure for apps like Spectacle, PDF Expert, TG Pro, and others that don't need networking to disable it through Little Snitch.

I used to run a script every time I installed everything. Now I just reinstall everything so I don't have too much on my Mac (and sometimes I will change my apps).

### Essentials
* Browser: [Microsoft Edge]()
* Package and App Manager: Brew and [Brew Cask](https://formulae.brew.sh/cask/)
* Network Monitor: Little Snitch
* Window Tiling: Spectacle
* Password manager...

### Productivity
* Terminal: iTerm2
* Terminal Utilities:
* Development Envs: Sublime Text, Vim, Xcode
* Python Manager: miniconda3 + pip
* PDFs: PDF Expert
* Todo: Things 3
* Markdown: MacDown

### Utilities (mainly hackintosh)
* TG Pro: tame the fan curve
* Nocturnal: software dimming of screen. If your monitor supports DDC/CI use [NativeDisplayBrightness](https://github.com/Bensge/NativeDisplayBrightness)
* Chatology: search through iMessage history.
* Docker
* [FCPX](https://www.apple.com/final-cut-pro/): Making home videos


## TODO
- [ ] Explore Sleep and why the kernel panics and relation to USB
- [ ] Note all of the things that I change on my system

![#macosweed2020](https://i.redd.it/983kdbevo6o11.png)
