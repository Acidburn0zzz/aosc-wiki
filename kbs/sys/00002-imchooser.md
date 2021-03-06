<!-- TITLE: KB-SYS-00002: Configuration of Input Methods -->
<!-- SUBTITLE: Configuring Input Methods in AOSC OS Desktop Environments -->

Several input method engines are available for use with AOSC OS:

- Fcitx, [homepage](https://fcitx-im.org/).
- IBus, [homepage](https://github.com/ibus/ibus/wiki).
- SCIM, [homepage](https://github.com/scim-im).

# Installing an Input Method

To install an input method framework and its input method plugins, use `sudo apt install` to install one of the following packages...

- Fcitx, `fcitx-base`.
- IBus, `ibus-base`.
- SCIM, `scim-base`.

# Activating an Input Method

To activate a specific input method engine for the current user, run the following command as the **current user**:

```
$ imchooser ${IM}
```

`${IM}` here could be any of the following values:

- `fcitx`, for Fcitx.
- `ibus`, for IBus.
- `scim`, for SCIM.

Finally, re-login for the changes to take effect.
