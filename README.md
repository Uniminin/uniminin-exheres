# exheres
loannaflip's paludis exheres for Exherbo Linux providing exheres for various packages

## Using This Repository
Edit `/etc/paludis/repositories/loannaflip.conf` and include the following:
```r
format = e
location = /var/db/paludis/repositories/loannaflip
sync = git+https://github.com/loannaflip/exheres.git
sync_options = --branch=main
```
Then execute `cave sync loannaflip`, Paludis should then find and update the repository.
