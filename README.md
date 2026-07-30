# ZMK for the Knob Goblin macropad.

This project was to configure ZMK firmware for use with a Knob Goblin macropad and Super Mini (Nice!Nano v2 clone) microcontroller.

The Knob Goblin has an adjustable layout, and this firmware is built for an ortholinear layout with two encoders and a monochrome OLED 32x128 display. There are three ZMK layers. A macropad layer targeted for use with MacOS; a numpad layer which is just a standard numpad, and a simple system layer for some hardware control. The numpad originally used "kp_" (keypad) key bindings, but it was switched to regular keyboard number keys as the keypad bindings didn't allow Bluetooth security codes to be entered.

At the time this is written ZMK is at version 0.3.

Knob Goblin macropad - https://github.com/mrT1ddl3s/KnobGoblinhttps://github.com/mrT1ddl3s/KnobGoblin

![Keyboard Layout](.github/shield-wizard-layout.svg)

Original code generate by Shield Wizard for ZMK
