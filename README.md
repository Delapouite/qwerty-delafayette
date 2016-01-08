# Qwerty-Delafayette

Variant of the [qwerty-lafayette](https://github.com/fabi1cazenave/qwerty-lafayette) keyboard layout.

### About

This layout fills many `VoidSymbol` yet to be defined in the original implementation.
They're mainly located on the AltGr layer.

It also adds better support for the TypeMatrix 2030 keyboard in 106 keys mode.

Finally, the Compose Key is enabled by default.

### Install

Copy the `.xkb` dir to your home dir.

It contains both the *delafayette keymap* file and the *lafayette symbols* file ;
delafayette includes lafayette.

**Note**: the lafayette file must only contains the `symbols`, not the full file as offered on the original repo. In the future a fetch tool will be provided to do this job automagically.

Then run :

```sh
xkbcomp -w0 -I$HOME/.xkb ~/.xkb/keymap/delafayette $DISPLAY
```

### See Also

- [Awesome keyboard](https://github.com/Delapouite/awesome-keyboard)

### License

MIT
