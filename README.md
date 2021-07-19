# ZMK config for Architeuthis Dux

## What is this?

[ZMK keyboard firmware][1] configuration for [Architeuthis Dux by Tapi][2].

![Wireless Architeuthis Dux with nice!nano controllers][3]

The [`architeuthis_dux` shield in this repository](/config/boards/shields/architeuthis_dux/) is an adaptation of the direct pin [Cradio shield by @davidphilipbarr][4].

## How do I use this firmware?

Ready-to-flash firmware files for nice!nano can be downloaded from the latest build on the GitHub "[Actions][8]" tab.

A very simple QWERTY keymap is provided which is useful for ensuring a new keyboard is functional. To make your own customisations to the keymap, simply [fork this repo][7] and modify [`config/architeuthis_dux.keymap`](config/architeuthis_dux.keymap); GitHub will then build your ready-to-flash firmware in the GitHub "Actions" tab of your own repo.

Please refer to the [ZMK docs][5] if necessary (the [troubleshooting section][6] can be particularly helpful).

## Cephalopoda

Check out the rest of Tapi's Cephalopoda collection of low profile split ergonomic mechanical keyboards at <https://github.com/tapioki/cephalopoda>.

[1]: https://zmk.dev/
[2]: https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux
[3]: https://media.discordapp.net/attachments/855822038287908864/866315666802081792/image0.jpg
[4]: https://github.com/zmkfirmware/zmk/tree/main/app/boards/shields/cradio
[5]: https://zmk.dev/docs
[6]: https://zmk.dev/docs/troubleshooting#dtlibdterror
[7]: https://github.com/dxmh/zmk-architeuthis-dux/fork
[8]: https://github.com/dxmh/zmk-architeuthis-dux/actions
