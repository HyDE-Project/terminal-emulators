# Ghostty

## Adding Templates

To add templates, follow these steps:

1. Copy the file `/ghostty.dcol` to either `~/.config/hyde/wallbash/always` or `~/.config/hyde/wallbash/theme`.
2. Run `hyde-shell reload` to generate the file.

## Applying the `theme.conf`

To apply the theme, include the `ghostty/hyde.conf` file in your `ghostty/ghostty.conf` configuration file.

1. Open your `ghostty.conf` file located at `~/.config/ghostty/ghostty.conf`.
2. Add the following line to include the theme configuration:

   ```plaintext
   include hyde.conf
   ```

   `hyde.conf` contains the default HyDE configuration including the theme.conf inclusion.

### Extra

HyDE by default uses the ghostty terminal. If you want to configure it manually,edit `~/.config/ghostty/ghostty.conf` as you see fit.

## Sources and Further Reading

For more information on configuring and theming the ghostty terminal, you can visit the following resources:
