# uniminin-exheres
uniminin's paludis exheres for Exherbo Linux providing exheres for various packages

## Using This Repository
Edit `/etc/paludis/repositories/uniminin.conf` and include the following:
```bash
format = e
location = /var/db/paludis/repositories/uniminin
sync = git+https://github.com/Uniminin/uniminin-exheres.git
```
Then execute `cave sync`, Paludis should then find and update the repository.