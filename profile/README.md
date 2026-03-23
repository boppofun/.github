![a tablet with 10 buttons in two rows of 5](tablet.png)

<p align="center">
<a href="https://boppo.com">boppo.com</a> | <a href="https://developer.boppo.com">Developer Docs</a>
</p>

## Boppo, the Screen-free Tablet for Fun and Learning

Boppo is a tablet with 10 light up buttons and a speaker.

Boppo ships with over 40 activities that come included for free on the tablet
and Toppos can go on top of the tablet to add more activities over time.

We are making an open source SDK for activity development which we are working
on shipping.

## The Specifications

Boppo's 10 light up buttons contain 4 individually addressable RGB LEDs.
The buttons are quality custom ordered mechanical keyboard switches.

Boppo is powered by an [ESP32-S3] which is a microcontroller that has:

* a dual-core CPU running at 240 Mhz
* 512 kB SRAM
* 2 MB PSRAM
* 16 MB Flash
* Wifi and Bluetooth communication

Boppo also has:

* a 3.5 Watt (max) speaker
* an NFC antenna that can read supported NFC tags
* a rechargable lipo battery
* a USB-C port (for recharging and possibly future features that require data transfer)
* a 3.5mm headphone jack

# The SDK API

The current activities and API are programmed in the  [Rust] programming
language. Additional language integration is possible in the future.

Easy to use functions and structs for receiving input and changing the button
colors are provided.

I also developed a custom audio playback library called [awedio] to support
streaming multiple sounds with effects simultaneously on an ESP-32 which is used
in the SDK.

## Share with Others

Made an activity that you think others will like? Let us know and we will
consider including it in the global list shipped to all devices.

## Security

The device does not have any microphones or cameras and does not collect
sensitive user information.

Boppo source code is manually verified before being deployed to tablets.

## Open

The [awedio] audio playback library has been open sourced and the SDK will be
open sourced in the future. We want to open up more the platform over time,
if there is anything you are particularly interested in please reach out.

## Feature Requests

Vote for your [favorite next feature] for us to work on with a thumbs up or
post a new feature request.

## Questions or Comments?

Check out our [FAQ], post a question in our [reddit thread] or email me at
ben@boppo.com

[boppo]: https://boppo.com
[Rust]: https://rust-lang.org
[awedio]: https://github.com/10buttons/awedio
[ESP32-S3]: https://www.espressif.com/en/products/socs/esp32-s3
[favorite next feature]: https://github.com/boppofun/feature_requests/issues
[FAQ]: https://boppo.com/pages/faq
[reddit thread]: https://www.reddit.com/r/boppo/comments/1eqmc9v/got_a_question_ask_here/
