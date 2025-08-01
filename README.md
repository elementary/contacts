# contacts
[![l10n](https://l10n.elementary.io/widgets/contacts/-/svg-badge.svg)](https://l10n.elementary.io/projects/contacts)

![Screenshot](data/screenshot.png?raw=true)

See and get in touch with your contacts from elementary OS

## Building and Installation

You'll need the following dependencies:
* folks
* glib-2.0
* gobject-2.0
* granite-7
* adwaita-1
* gtk4
* meson (>= 0.57.0)
* valac

Run `meson build` to configure the build environment. Change to the build directory and run `ninja` to build

```bash
meson build --prefix=/usr
cd build
ninja
```

To install, use `ninja install`, then execute with `io.elementary.contacts`

```bash
ninja install
io.elementary.contacts
```
