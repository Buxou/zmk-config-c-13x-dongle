ZMK firmware for the C-13x keyboard, for the wireless keyboard, the wireless keyboard with a dongle, and the wired keyboard.
Everything is also configured for graphical keyboard layout settings.
Sorry for my poor language skills; English isn't my native language.

The firmware is in the testing stage, because I don’t have enough nice!nano v2 yet.

- Variant with dongle:
  - board: nice_nano_v2:
    - shield: c-13x_dongle: tested, fully functional.
    - shield: c-13x_central: tested, fully functional.

- Variant without dongle:
    - board: nice_nano_v2: 
    - shield: c-13x: tested, fully functional.

- Wired option:
  - board: adafruit_kb2040
    - shield: c-13x: checked, problems with the layout.
  

<img width="875" height="424" alt="image" src="https://github.com/user-attachments/assets/3f893f0e-f72b-45be-97f3-608652085af9" />
