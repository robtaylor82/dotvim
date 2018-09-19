# VIM Configuration Files and Plugins

Instructions taken from http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/

### Installing plugins as submodules

From the bundles folder run:

```bash
git submodule add http://github.com/name/of/repository
```

### Upgrading modules

```bash
git submodule foreach git pull origin master
```
