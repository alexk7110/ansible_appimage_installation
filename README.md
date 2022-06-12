# AppImage Installer and Updater

This playbook was created out of necessity of installing multiple AppImage files at once.
Finding the download page each time is a hustle since they are scattered all over the Internet.

It works on a fresh machine along with one where some of the apps were already installed.

It supports selective installation through the use of tags eg. `ansible-playbook main.yml --tags "libreoffice, manager"`

## Versions Currently Installed

Electum \
4.2.2 \
[Electrum Download Page](https://electrum.org/#download)

Keepass \
2.7.1 \
[Keepass Download Page](https://keepassxc.org/download/#linux)

Libreoffice \
7.3.1 \
[Libreoffice Download Page](https://libreoffice.soluzioniopen.com/)

Yubikey Authenticator \
5.1.0 \
[Yubikey Authenticator Download Page](https://developers.yubico.com/yubioath-desktop/Releases/)

Yubikey Manager QT \
1.2.4b \
[Yubikey Manager Download Page](https://developers.yubico.com/yubikey-manager-qt/Releases/)
