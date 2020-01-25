# pass-autotype

This script is based on the fzf-pass script by ReekyMarko
https://git.reekynet.com/ReekyMarko/fzf-pass/ but using dmenu instead of fzf,
which works on wayland without additional configuration. It uses ydotool to type
the information.

## Installation

Copy the script in a directory in the `$PATH`.

## Requirements

- pass
- ydotool
- pass-otp (optional for otp)

## Usage

Add a keybind to your Window Manager configuration.

```
bindsym $mod+p exec pass-autotype
```

If you have your Password Store in another place, set the variable `$PASSWORD_STORE_DIR`

## Contributing

Any contributions are welcome! If you find anything that can be better, open an
Issue or a PR in this repository.
