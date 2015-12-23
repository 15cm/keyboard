# Mac KeyBoard Configuration

## Features

### Caps Lock to Hyper Key

- Caps Lock to Escape, hold for Hyper(Control_R)
- Double press Shift_R to Caps Lock

### Emacs Emulator

- Hyper+P/N/B/F for Up/Down/Left/Right

### Easily Change Input Source

- Switch Input Method:
    - Option_R to switch between English and Chinese (Disable 'shift to switch Chinese and English' in Baidu/Sougou Pinyin before enable this hotkey)

- Specify Input Source: Command_R(For Minila Air)/Option_L(For Other Keyboard) + a/s/d to specify input source 1st/2nd/3rd

    __Attention: This feature is implemented by `Select next source in input menu` Shortcuts of OS X.
    Here I set it as F18(CMD_R + CTRL_L + F11 -> F18 in case of conflict).__

### Adjustment for external keyboard

- Swap Option with Command on external keyboard (Adjust keyboard mapping for PC to for Mac)

    __Attetion: This feature acts on specified external keyboard(Cherry 3494, Minila Air so far). Therefore you should obtain information about your external keyboard by EventViewer(launched from the menu bar item of karabiner) and modify the corresponding code.__

### Layout for Minila Air


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

## Reference & Thanks To

- [jasonrudolph/keyboard](https://github.com/jasonrudolph/keyboard)
- [private.xml Reference Manual](https://pqrs.org/osx/karabiner/xml.html.en)
- The idea of setting hotkey for switching input source as F18 is inspired by [Sylv](https://v2ex.com/member/Sylv) in [this post on V2EX](https://v2ex.com/t/205046)
