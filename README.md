# Mac KeyBoard Configuration

## Features

### Caps Lock to Hyper Key

- Double press shift to Caps Lock
- Caps Lock to Escape, hold for Hyper(Control_R)

#### Vim Emulator with Hyper

- Hyper + h/j/k/l to Cursor Left/Down/Up/Right
- Hyper + f/b to PgDn/PgUp

### Specify Input Source

- Specify Input Source: Option_L + a/s/d to specify input source 1/2/3
    __Attention:__ This feature is implemented by `Select next source in input menu` Shortcuts of OS X. Here I set it as cmd+ctrl+F11. Besides, since the input buffer cannot be clean when change from input source like Chinese,a 3rd input source is needed to flush the current buffer. Therefore if the number of your input source is not 3, some problem may occur when using this feature.   

### Adjustment for external keyboard

- Swap Option with Command on external keyboard (Adjust keyboard mapping for PC to for Mac)
    __Attetion:__ This feature is implemented by specified the external keyboard on which "Swap Option with Command" takes effect. Therefore it's you should obtain information about your external keyboard by EventViewer(launched from the menu bar item of karabiner) and modify the corresponding code.

## Set up

1. Change Caps Lock to F19(keycode: 80)

2. Clone this repo and create a soft link
    ```
    git clone https://github.com/15cm/keyboard.git
    ln -s $PWD/keyboard/Karabiner/private.xml ~/Library/Application Support/Karabiner
    ```

3. Click `Reload XML` on 'Change Key' Board of Karabiner

## Dependencies

* [Karabiner](https://pqrs.org/osx/karabiner/)
* [Seil](https://pqrs.org/osx/karabiner/seil.html.en)

## Reference

- [jasonrudolph/keyboard](https://github.com/jasonrudolph/keyboard)
- [private.xml Reference Manual](https://pqrs.org/osx/karabiner/xml.html.en)
