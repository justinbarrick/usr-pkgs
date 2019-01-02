A bunch of the Arch packages that I use so that I don't have to build them from scratch every time.

# Setup

To configure, set the following in your `/etc/pacman.conf`:

```
[usr]
SigLevel = Optional TrustAll
Server = https://codesink-arch.sfo2.digitaloceanspaces.com/
```

# Packages

* polybar
* cower
* pacaur
* termsyn-font
* ttf-font-awesome-4
* ttf-material-design-icons
* ttf-unifont

# TODO

* Ensure that packages are always included in repo manifests if they are in S3.
* Put a proxy in front of S3 for a better hostname.
* GPG signing.
