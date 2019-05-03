# Plex Trash Fixer


[![made-with-python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%203-blue.svg)](https://github.com/l3uddz/plex_autoscan/blob/master/LICENSE.md)

---

Fixes the issue in Plex Media Server when emptying trash does not get rid of the trash icons.


## Dependencies

Debian based distros:

```
sudo apt-get install python3
```


## Install


1. Clone project:

   ```
   git clone https://github.com/l3uddz/plex_trash_fixer /opt/plex_trash_fixer
   ```

1. Set permissions:

   ```
   chmod a+x /opt/plex_trash_fixer/plex_trash_fixer.py
   ```

## Usage

- Plex Media Server: Empty trash and optimize library. Then shut down Plex Media Server. 

- Run script: `python3 /opt/plex_trash_fixer/plex_trash_fixer.py`

