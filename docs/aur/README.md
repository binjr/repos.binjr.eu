# How to install binjr from the Arch User Repository?

1. Make sure that all the necessary tools are installed by installing the [base-devel](https://archlinux.org/packages/?name=base-devel) package:
```
pacman -S base-devel
```

2. Get the build files for the binjr package for the AUR:
```
git clone https://aur.archlinux.org/packages/binjr-bin
```

3. Get the binjr developpers GPG public keys
```
curl https://binjr.eu/openpgpkey/binjr_dev_pub_keys.asc | gpg --import
```

4. Make the package and install it
```
cd binjr-bin
makepkg -si
```

Please refer the [AUR User Guidelines](https://wiki.archlinux.org/title/Arch_User_Repository) for more information.
