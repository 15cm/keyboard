# Mac KeyBoard Configuration

## Features

### Caps Lock to Escape or Control

- Double press shift to Caps Lock
- Caps Lock to Escape, hold for Hyper(Control_R)
- Fake Vim : Hyper + h/j/k/l to Cursor Left/Down/Up/Right

### Specify Input Source

- Specify Input Source: Option_L + q/w/e to specify input source 1/2/3
    __Attention:__ This feature is implemented by `Select next source in input menu` Shortcuts of OS X. Here I set it as cmd+ctrl+F11. Besides, since the buffer cannot be clean when change from input source like Chinese, `shift` is used to change the input method between Chinese and English. Therefore some problem may exists in this feature.   

### Adjustment for external keyboard

- Swap Option with Command on external keyboard

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
