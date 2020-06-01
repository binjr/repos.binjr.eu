# How to use binjr's APT repository?

To add the binjr apt repository on a Ubuntu or Debian system:

1. Import binjr's developers public keys.
    ``` sh
    curl https://binjr.eu/openpgpkey/binjr_dev_pub_keys.asc | sudo apt-key add -
    ```
2. Add the repository.
    ``` sh
    sudo apt-add-repository 'deb https://repos.binjr.eu/apt stable main'
    ```
3. Update the information about available packages.
    ``` sh
    sudo apt update
    ```
3. Install binjr.
    ``` sh
    sudo apt install binjr
    ```