# How to use binjr's RPM repository?

To add the binjr repository on a RHEL, Centos or Fedora system:

1. Import binjr's developers public keys.
    ``` sh
    sudo rpm --import https://binjr.eu/openpgpkey/binjr_dev_pub_keys.asc
    ```

 2. Add the repository.
    ``` sh
    sudo curl -o /etc/yum.repos.d/binjr.repo https://repos.binjr.eu/rpm/binjr.repo
    ```

3. Install binjr.
    ``` sh
    sudo dnf install binjr
    ```
