# Mac KeyBoard Configuration (Deprecated)

[How it looks](http://www.keyboard-layout-editor.com/#/gists/46614c15dc4edfb98667)

__Moved to__ [dotfiles](https://github.com/15cm/dotfiles/tree/master/.config/karabiner)

## Features

### Caps Lock to Hyper Key

- Caps Lock to Escape, hold for Hyper(Control_R)
- Double press Shift_R to Caps Lock

### Emacs Emulator

- Hyper + P/N/B/F for Up/Down/Left/Right
- Hyper + Command_L + P/N to Page Up/Dn
- Hyper + H/D to Delete/Forward_Delete

### Easily Change Input Source

- Specify Input Source: SUPER(For Minila Air)/Option_L(For Other Keyboard) + a/s/d to specify input source 1st/2nd/3rd
HYPER
    __Attention: This feature is implemented by `Select next source in input menu` Shortcuts of OS X.
    Here I set it as F18(CMD_R + CTRL_L + F11 -> F18 in case of conflict).__

### Adjustment for external keyboard

- Swap Option with Command on external keyboard (Adjust keyboard mapping for PC to for Mac)

    __Attetion: This feature acts on specified external keyboard(Cherry 3494, Minila Air so far). Therefore you should obtain information about your external keyboard by EventViewer(launched from the menu bar item of karabiner) and modify the corresponding code.__

### Layout for Minila Air
- Space to Space, hold for SUPER(VK Modifier)
- SUPER + 1-12 to F1-F12
- App + 1-12 for Media Control(Fn + F1-F12 for me)

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
