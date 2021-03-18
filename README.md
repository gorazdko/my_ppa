# my_ppa


## How to install

```bash
curl -s --compressed "https://gorazdko.github.io/my_ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://gorazdko.github.io/my_ppa/my_list_file.list"
sudo apt update
```

### Seedtool

```bash
sudo apt install seedtool
```
