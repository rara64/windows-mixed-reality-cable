<img src='img/logo.png' width=128>

# DIY cable replacement for Windows Mixed Reality headsets [WIP]
This project focuses on allowing the replacement of the proprietary VR cable in Mixed Reality headsets.

> [!NOTE]
> I'm currently working on [replacing it with a single USB-C plug](https://github.com/rara64/windows-mixed-reality-usb-c), but here, you'll soon find a version that doesn't require a USB-C DP-capable port on your computer and allows for a direct replacement with a USB and HDMI cable.

If you're here you probably know that the proprietary cables used in these headsets are prone to failure and unavailable for purchase as a separate part.
Due to damaged cables, dozens of Mixed Reality headsets end up in the trash. I want to change that.

# Roadmap
- ✅ ~~Create a plug extender board that will extend the 30-pin connector inside the headset outside the device~~
- ✅ Create a matching PCB with USB+HDMI ports
- [-] Create an improved version ready for use

# Progress

### April 2026

![](https://github.com/rara64/windows-mixed-reality-usb-c/blob/main/img/working-headset.gif)

As it turns out, my current design works! 🎉

It really looked like a broken headset, but it behaved like this because of my Windows settings. Really annoying...
Inside Mixed Reality settings, there is an option called **"Fade to gray when positional tracking is lost"** and I just had to turn it off.

I still have to make a final usable design for the HDMI+USB combo, but the problem is that I don't have as much time as last year.
It might take me longer than expected, and I'll try to focus on the USB C version for now.

### August 2025

![](https://github.com/rara64/windows-mixed-reality-usb-c/blob/main/img/cable-replacement.jpg)

I created the plug extender and the corresponding PCB with USB and HDMI ports. Both seem to be OK, but don't fully work with the headset - there is something that resembles a testing pattern on the headset display.
My headsets for testing seem to be broken. PCB designs are available to download, but so far remain non-functional. [More here](https://github.com/rara64/windows-mixed-reality-usb-c)
