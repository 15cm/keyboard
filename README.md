# Mac KeyBoard Configuration

## Caps Lock to Escape or Control

### Functions

1. Double press shift to Caps Lock
2. Caps Lock to Escape, hold for Hyper(Control_R)
3. Fake Vim : Hyper - h/j/k/l to Cursor Left/Down/Up/Right

...

### Future Features

1. Hot key to specify input source

### Set up

1. Change Caps Lock to F19(keycode:80)
2. ```
    git clone https://github.com/15cm/keyboard.git
    ln -s $PWD/keyboard/Karabiner/private.xml ~/Library/Application Support/Karabiner
    ```
...

## Dependencies

* [Karabiner](https://pqrs.org/osx/karabiner/)
* [Seil](https://pqrs.org/osx/karabiner/seil.html.en)

## Document

- [private.xml Reference Manual](https://pqrs.org/osx/karabiner/xml.html.en#modifier)
