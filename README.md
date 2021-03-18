# my_ppa


## Source

[](https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html)

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

### Keytool

```bash
sudo apt install keytool
```
