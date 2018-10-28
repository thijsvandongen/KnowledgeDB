# Install of LAMP via a script

The easiest way to install is using a script

See <https://github.com/teddysun/lamp>

In a terminal in Linux

Via

```shell
su sudo
apt-get -y install wget screen git
git clone https://github.com/teddysun/lamp.git
cd lamp
chmod +x *.sh
screen -S lamp
./lamp.sh
```

This will take about 30 minutes to be completed

## Lamp Command

Command    Description
lamp add    create a virtual host
lamp list    list all virtual host
lamp del    remove a virtual host