# setup-scripts

Scripts to get my systems setup.

## MacOS

```sh
git clone https://github.com/jakebottrall/setup-scripts.git
cd setup-scripts
./setup_mac.sh
```

## Ubuntu

```sh
sudo apt update
sudo apt upgrade -y
sudo apt install git -y
git clone https://github.com/jakebottrall/setup-scripts.git
cd setup-scripts
./setup_ubuntu.sh
```

## Arch

Steam desktop needs the following:

```toml
Exec=env DRI_PRIME=0 steam
```
