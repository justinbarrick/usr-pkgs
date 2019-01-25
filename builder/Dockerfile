FROM base/archlinux:2019.01.01

RUN pacman -Sy --noconfirm --force readline pacman bash gnupg libidn2 || :
RUN pacman -Sy --noconfirm --force base-devel sudo binutils cmake && useradd -m -s /bin/bash user \
      && echo "user ALL=(ALL) NOPASSWD: ALL" >> /etc/sudoers

USER user

RUN mkdir ~/.gnupg && echo keyserver-options auto-key-retrieve > ~/.gnupg/gpg.conf
