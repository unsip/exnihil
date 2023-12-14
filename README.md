About
=====
This is my third-party repository for [Exherbo Linux](https://www.exherbolinux.org/) distribution.

To set it up create a file `/etc/paludis/repositories/exnihil.conf`:
```
  format = e
  location = /var/db/paludis/repositories/exnihil
  sync = git+https://github.com/unsip/exnihil.git
  sync_options = --git-clone-option='--depth=1'
```
