# Cantor Keyboard Remix (36 keys)
This is a modified version of the [Cantor](https://github.com/diepala/cantor) keyboard, designed by [diepala](https://github.com/diepala).

![Cantor Keyboard](assets/cantor-remix.jpg)


## Changes
This version has only 2 changes over the original:
- 36 Keys: removed the outer column while keeping the original schematic
- Custom Silkscreen: removed details from the silkscreen layer and added a geometric pattern (I tried to camouflage the Blackpills a bit)

I followed the process documented on [this Ben Vallack's video](https://www.youtube.com/watch?v=JqpBKuEVinw) - it was quite simple. You can do the same if you want to change the silkscreen. 


## Firmware / Keymap
The 36 keys of this version are ideal for running [Miryoku](https://github.com/manna-harbour/miryoku), an ergonomic, minimal, orthogonal, and universal keyboard layout.

The original Cantor is already supported, so all you have to do is running the following command:
```
qmk flash -kb cantor -km manna-harbour_miryoku
```

Please note that as of 06/2022, an update for Miryoku is [pending review](https://github.com/qmk/qmk_firmware/pull/16482) - if you want to have the latest version you can merge the PR branch locally, or follow instructions discussed [here](https://github.com/manna-harbour/miryoku/discussions/89).


## Build Guide
Grab the `pcb/gerber.zip` and use your service of choice to order it! I used [JLCPCB](https://jlcpcb.com/), and there's a tag for them to print the order number in the silkscreen layer. 

Make sure to follow the original [Cantor Build Guide](https://github.com/diepala/cantor/blob/main/doc/build_guide.md). 

## Support Cantor
Consider supporting the original [Cantor](https://github.com/diepala/cantor)! Please refer to the original repository for more information.


