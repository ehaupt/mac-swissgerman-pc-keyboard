# Keyboard bundle for using a 105 key Swiss German keyboard on a Mac

## Description

If you would like to use a 105 key Swiss German keyboard on your Mac
you might want to remap some keys.

This is the keyboard bundle I am using.

The file `DefaultKeyBinding.dict` provides additional key bindings
for the `home` and `end` keys.

## How to install

* Copy `SwissGermanPC.bundle` to `~/Library/Keyboard Layouts`

* Go to `System Preferences` -> `Keyboard` -> `Input Sources`

* Click the `+` sign

* Go to `German`

* Select `Swiss German PC`

* Copy `DefaultKeyBinding.dict` to `~/Library/KeyBindings/DefaultKeyBinding.dict`

## How to make modifications

I've used [Ukelele](https://software.sil.org/ukelele/) to create the keyboard bundle.

It can be installed with:

```sh
brew install ukelele
```
