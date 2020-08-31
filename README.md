# xbee-arduino

Arduino library for communicating with XBees in API mode, with support for both Series 1 (802.15.4) and Series 2 (ZB Pro/ZNet). This library Includes support for the majority of packet types, including: TX/RX, AT Command, Remote AT, I/O Samples and Modem Status. This was originally on googlecode and now github. I will attempt to keep both repos in sync. See https://code.google.com/p/xbee-arduino/ for documentation 

## About this fork

We forked https://github.com/andrewrapp/xbee-arduino on 2020-08-31 because hadn't been updated since 2016-12-31.
More specifically, we forked tag `v0.6.0` (1bfd365f4392dbd9a3e448b2faa7e40595dc1165), creating the new
`xbee3` branch in the https://github.com/dancullen/xbee-arduino repo. We made some changes to make this library
compatible with the XBee 3 RF Modules.

The reason we forked `v0.6.0` instead of HEAD was that `v0.6.0` is what is available by default through
the Arduino IDE Library Manager. We already had already started working with this code so that's what
we decided to fork as our starting point.
