A bunch of the Arch packages that I use so that I don't have to build them from scratch every time.

# Setup

To configure, set the following in your `/etc/pacman.conf`:

```
[usr]
SigLevel = Optional TrustAll
Server = https://codesink-arch.sfo2.digitaloceanspaces.com/
```

# Packages

* [cower](https://aur.archlinux.org/packages/cower/) (pacaur dependency)
* [frame](https://aur.archlinux.org/packages/frame/)
* [geis](https://aur.archlinux.org/packages/geis/)
* [grail](https://aur.archlinux.org/packages/grail/)
* [hone](https://github.com/justinbarrick/hone) A build tool
* [keybase-bin](https://aur.archlinux.org/packages/keybase-bin/)
* [libreswan](https://aur.archlinux.org/packages/libreswan/)
* [minidcos](https://github.com/dcos/dcos-e2e)
* [pacaur](https://github.com/rmarquis/pacaur) AUR client
* [polybar](https://github.com/jaagr/polybar) (with i3 support) a nice bar for your WM.
* [ppp](https://www.archlinux.org/packages/core/x86_64/ppp/)
* [pxz-git](https://aur.archlinux.org/packages/pxz-git/)
* [python35](https://aur.archlinux.org/packages/python35)
* [signal-desktop-bin](https://aur.archlinux.org/packages/signal-desktop-bin/)
* [termsyn-font](https://aur.archlinux.org/packages/termsyn-font/)
* [touchegg](https://aur.archlinux.org/packages/touchegg)
* [ttf-font-awesome-4](https://aur.archlinux.org/packages/ttf-font-awesome-4/) Font Awesome 4.
* [ttf-material-design-icons](https://aur.archlinux.org/packages/ttf-material-design-icons/) Material Design icon font
* [ttf-unifont](https://aur.archlinux.org/packages/termsyn-font/)
* [zoom](https://aur.archlinux.org/packages/zoom)
* [eclipse-mat](https://aur.archlinux.org/packages/eclipse-mat) Eclipse Memory Analysis Tool

# TODO

* Ensure that packages are always included in repo manifests if they are in S3.
* Put a proxy in front of S3 for a better hostname.
* GPG signing.
