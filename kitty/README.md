# Kitty

## Adding Templates

To add templates, follow these steps:

1. Copy the file `/kitty.dcol` to either `~/.config/hyde/wallbash/always` or `~/.config/hyde/wallbash/theme`.
2. Run `hyde-shell reload` to generate the file.

## Applying the `theme.conf`

To apply the theme, include the `kitty/hyde.conf` file in your `kitty/kitty.conf` configuration file.

1. Open your `kitty.conf` file located at `~/.config/kitty/kitty.conf`.
2. Add the following line to include the theme configuration:

   ```plaintext
   include hyde.conf
   ```

   `hyde.conf` contains the default HyDE configuration including the theme.conf inclusion.

### Extra

HyDE by default uses the Kitty terminal. If you want to configure it manually,edit `~/.config/kitty/kitty.conf` as you see fit.

## Sources and Further Reading

For more information on configuring and theming the Kitty terminal, you can visit the following resources:

- [Kitty Wiki](https://sw.kovidgoyal.net/kitty/)
- [Kitty Theming Guide](https://sw.kovidgoyal.net/kitty/conf/#theming)
