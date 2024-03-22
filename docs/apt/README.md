# How to use binjr's APT repository?

To add the binjr apt repository on a Ubuntu or Debian system:

1. Import binjr's developers public keys.
    ``` bash
    curl https://binjr.eu/openpgpkey/binjr_dev_pub_keys.asc | sudo tee /usr/share/keyrings/binjr.asc
    ```
2. Add the repository.
    ``` bash
    echo 'deb [arch=amd64 signed-by=/usr/share/keyrings/binjr.asc] https://repos.binjr.eu/apt stable main' | sudo tee /etc/apt/sources.list.d/binjr.list
    ```
3. Update the information about available packages.
    ``` bash
    sudo apt update
    ```
3. Install binjr.
    ``` bash
    sudo apt install binjr
    ```