# Foot

## Adding Templates

To add templates, follow these steps:

1. Copy the file `/foot.dcol` to either `~/.config/hyde/wallbash/Wall-Ways` or `~/.config/hyde/wallbash/Wall-Dcol`.
2. Run `Hyde reload` to generate the file.

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
include=~/.config/foot/theme.ini
```

## Read More About Foot

- [Foot Terminal GitHub Repository](https://codeberg.org/dnkl/foot)
- [Foot Configuration Documentation](https://codeberg.org/dnkl/foot/src/branch/master/man/foot.ini.5.scd)
- [Foot on ArchWiki](https://wiki.archlinux.org/title/Foot)
