# screensht

Utility to make Hyprland screenshots look pretty

Based on https://gist.github.com/arnvgh/01b204df3229ed8c41cfd6ed847bb545

I use this for my screenshots, some people ask how I make them so here it is

## Usage

- `screensht area` for an area (or click on a window to get that window)
- `screensht full` for a full screenshot of your active display

Settings can be changed directly at the top of the script.

## Dependencies

- [`grimblast`](https://github.com/hyprwm/contrib/blob/main/grimblast/grimblast) for screenshotting
- [`hyprctl`](https://wiki.hyprland.org/Configuring/Using-hyprctl/) (part of [Hyprland](hyprland.org/)) for changing decoration settings while taking a screenshot
- [`satty`](https://github.com/gabm/Satty) for optional screenshot editing
- [`imagemagick`](https://imagemagick.org/index.php) for image processing
- [`wl-copy`](https://github.com/bugaevc/wl-clipboard) for clipboard management (`wl-clipboard` and `wl-clipboard-rs` work)
- [`libnotify`](https://gitlab.gnome.org/GNOME/libnotify) to send notifications (and a compatible notification daemon, preferabbly one with button support like [`swaync`](https://github.com/ErikReider/SwayNotificationCenter))

Here's a screenshot of screensht using screensht:

![image](https://github.com/ThatOneCalculator/screensht/assets/44733677/2f9edb94-21fc-4966-ad9e-69741aabb800)

And a screenshot of a notification of a screenshot taken with screensht taken with screensht:

![image](https://github.com/ThatOneCalculator/screensht/assets/44733677/573523df-5f1f-49d3-96c7-299c76c6c64e)
