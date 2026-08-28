# Aaron's build of dwm

Personal build of [dwm](https://dwm.suckless.org/) based on Luke Smith's LARBS fork,
customized for a Fedora Linux workstation with a USG engineering-inspired theme.

## Theme

Phosphor-green on near-black. High information density. Inspired by
[@usgraphics](https://x.com/usgraphics) — engineered for human vision, not decoration.

## Patches and features

- [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/): Gaps across all layouts.
- [xresources](https://dwm.suckless.org/patches/xresources/): Runtime color loading.
- [swallow](https://dwm.suckless.org/patches/swallow/): Terminal swallows spawned GUI apps.
- [scratchpads](https://dwm.suckless.org/patches/scratchpads/): `Super+Shift+Enter` terminal, `Super+'` calculator.
- [shiftview](https://dwm.suckless.org/patches/nextprev/): Cycle tags with `Super+G/;`.
- [stacker](https://dwm.suckless.org/patches/stacker/): Move windows up/down stack with `Super+K/J`.
- Clickable statusbar via [dwmblocks](https://github.com/lukesmithxyz/dwmblocks).
- Multiple layouts: tile, bstack, fibonacci, deck, monocle, centered master, floating.
- True fullscreen (`Super+F`), sticky windows (`Super+S`).

## Installation

```bash
git clone https://github.com/aaronbjohnson/dwm.git
cd dwm
sudo make install
```

See [config.h](config.h) for all keybindings.
