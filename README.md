# Mac KeyBoard Configuration

## Caps Lock to Escape or Control

### Functions

1. Double press shift to Caps Lock
2. Caps Lock to Escape, hold for Hyper(Control_R)
3. Fake Vim : Hyper + h/j/k/l to Cursor Left/Down/Up/Right
4. Specify Input Source: Option_L + q/w/e to specify input source as English(US)/Chinese(Sougou Pinyin)/Japanese(Kotoeri)


### Set up

1. Change Caps Lock to F19(keycode:80)

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

- [private.xml Reference Manual](https://pqrs.org/osx/karabiner/xml.html.en#modifier)
