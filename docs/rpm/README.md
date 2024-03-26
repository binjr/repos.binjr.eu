# How to use binjr's RPM repository?

To add the binjr repository on a RHEL, Centos or Fedora system:

1. Add the repository.
    ``` bash
    curl https://repos.binjr.eu/rpm/binjr.repo | sudo tee /etc/yum.repos.d/binjr.repo
    ```

2. Install binjr.
    ``` bash
    sudo dnf install binjr
    ```