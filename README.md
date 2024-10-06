# bash-duh

simple bash discord update helper for arch linux

oneshot daemon. systemd needed for current implementation. path for arch, possible to adapt for other distros though.
dependencies are curl & jq for fetching and parsing the json data from the discord endpoint

### install
```
sudo pacman -S jq
chmod +x intall.sh
sudo ./install.sh
```
### uninstall
```
chmod +x unintall.sh
sudo ./uninstall.sh
```
