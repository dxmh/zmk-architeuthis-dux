# ZMK shield for Architeuthis Dux

## What is this?

[ZMK keyboard firmware][1] configuration for [Architeuthis Dux by Tapi][2].

![Wireless Architeuthis Dux with nice!nano controllers][3]

This shield is an adaptation of the direct pin [Cradio shield by @davidphilipbarr][4].

## How do I use this shield?

1. Put this shield inside your ZMK config directory. For example, clone (or copy the contents of) this repository to `~/zmk-config/config/boards/shields/architeuthis_dux/`.
2. Configure your keymap. This shield contains only [a sample keymap](/architeuthis_dux.keymap), copy it to `~/zmk-config/config/architeuthis_dux.keymap` and configure it to your liking.
3. Build your firmware for `architeuthis_dux` as you would for any other ZMK keyboard.

Please refer to the [ZMK docs][5] if necessary.

## Cephalopoda

Check out the rest of Tapi's Cephalopoda collection of low profile split ergonomic mechanical keyboards at <https://github.com/tapioki/cephalopoda>.

[1]: https://zmk.dev/
[2]: https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux
[3]: https://media.discordapp.net/attachments/855822038287908864/866315666802081792/image0.jpg
[4]: https://github.com/zmkfirmware/zmk/tree/main/app/boards/shields/cradio
[5]: https://zmk.dev/docs
