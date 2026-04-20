<image src=https://github.com/de-things/.github/blob/main/profile/banner-v4.png />

## A gist...
...is to make each IoT device decentralized and self-contained without a need of communication through world-wide China-like server (Hi Aqara, Tuya and etc. etc.). So you can assemble your own smart things using this project.

It has alternatives like a **[Home Assistant](https://github.com/home-assistant/)**, but it's too complicated for me, as well as I wanted to implement an IoT environment with my own knowledge, so I did a thing... a *de:thing*, basically, ha-ha.

## Core
**[delib](https://github.com/de-things/delib)** - is the core lib for the whole stuff here. You include it into your ESP32 controller to let it work as decentralized client<>server device with a simple communication based on !commands.

You need your custom frontend as well as firmware for each device to make your own decentralized IoT. **[delib](https://github.com/de-things/delib)** is just a light-weight lib to simplify firmware you write for your ESP32 controller.

🐳
