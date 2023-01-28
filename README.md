# PPA

## Install Software from this PPA

```
curl -s --compressed -L "https://recon-tools.github.io/ppa/debian/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/my_ppa.gpg >/dev/null
sudo curl -s --compressed -L -o /etc/apt/sources.list.d/recon_tools.list "https://recon-tools.github.io/ppa/debian/recon_tools.list"
sudo apt update
```
