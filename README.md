# Installer

# Install

## Ubuntu Server

1. Add a deployer user 

    ```bash
    adduser deployer --ingroup sudo
    su deployer
    ```
    
2. Then run script with deployer user.

    ```bash
    wget --no-check-certificate -a  -O "$path/src/installer" https://raw.github.com/lab2023/installer/master/ubuntu_server
    chmod +x installer
    ./installer 
    ```

## Mint Desktop

# License

Installer is Copyright © 2010-2012 lab2023 - internet technologies. It is free software, and may be redistributed under the terms specified in the LICENSE file.
