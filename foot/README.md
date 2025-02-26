# Foot

## Adding Templates

To add templates, follow these steps:

1. Copy the file `/foot.dcol` to either `~/.config/hyde/wallbash/always` or `~/.config/hyde/wallbash/theme`.
2. Run `hyde-shell reload` to generate the file.

**Note:** Ensure you have the directory `~/.config/foot/`. If it does not exist, create it with the following command:

```bash
mkdir ~/.config/foot/
```

The destination directory for the template will be `~/.config/foot/theme.ini`.

## Applying the Theme

To apply the theme, include the `theme.ini` file in your `foot.ini` configuration file.

1. Open your `foot.ini` file, usually located at `~/.config/foot/foot.ini`.
2. Add the following line to include the theme configuration:

```ini
[main]
include=~/.config/foot/theme.ini
```

**NOTE** [Foot as emulator do not support reloading the colors. ](https://codeberg.org/dnkl/foot/issues/708) So restarting the whole foot session is needed.

## Read More About Foot

- [Foot Terminal GitHub Repository](https://codeberg.org/dnkl/foot)
- [Foot Configuration Documentation](https://man.archlinux.org/man/foot.ini.5)
- [Foot on ArchWiki](https://wiki.archlinux.org/title/Foot)
