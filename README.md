# Minim

A minimalist black and white theme for Omarchy Linux.

**Status:** Maintained

## Features

- Pure black background (`#000000`)
- White and light gray color scheme
- Soft red accent color for menu selections (`#e84545`)
- Ultra-minimal design philosophy

## Installation

To install on your laptop or other machines:

```bash
cd ~/.config/omarchy/themes/
git clone https://github.com/jbondata/minim.git
omarchy-theme-set minim
```

## Customization

You might also want to copy your custom Hyprland settings (1px gaps and white borders) to those machines:

Edit `~/.config/hypr/looknfeel.conf` and add:
```conf
general {
    gaps_in = 1
    gaps_out = 1
    border_size = 1
}
```

And if you want the white active window border:
```conf
$activeBorderColor = rgb(ffffff)
$inactiveBorderColor = rgb(333333)
```

## Recommended IDE Extensions

To complete the minimalist experience in your code editor, install **Monochromator** by Josias Beem:

- **VS Code:** Monochromator (josias-beem.monochromator)
- **Cursor IDE:** Monochromator (josias-beem.monochromator)
- **Antigravity:** Monochromator (josias-beem.monochromator)

This distraction-free monochrome coding theme perfectly complements the minim system theme, maintaining the black and white aesthetic across your entire development environment.

## Screenshots

[Add screenshots here]

## Colors

- Background: `#000000` (Pure black)
- Foreground: `#e8e8e8` (Light gray)
- Accent: `#ff0000` (Red, for borders/highlights)
- Walker Selection: `#e84545` (Soft red, for menu items)
- Active Border: `#ffffff` (White)
- Inactive Border: `#333333` (Dark gray)