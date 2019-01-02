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
* [pacaur](https://github.com/rmarquis/pacaur) AUR client
* [polybar](https://github.com/jaagr/polybar) (with i3 support) a nice bar for your WM.
* [termsyn-font](https://aur.archlinux.org/packages/termsyn-font/)
* [ttf-font-awesome-4](https://aur.archlinux.org/packages/ttf-font-awesome-4/) Font Awesome 4.
* [ttf-material-design-icons](https://aur.archlinux.org/packages/ttf-material-design-icons/) Material Design icon font
* [ttf-unifont](https://aur.archlinux.org/packages/termsyn-font/)

# TODO

* Ensure that packages are always included in repo manifests if they are in S3.
* Put a proxy in front of S3 for a better hostname.
* GPG signing.
