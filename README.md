# Angular Github Pages Deploy

Publishing to Github Pages was removed from `@angular/cli` as of version 1.

Therefore, this script was created to handle the process.

## Installation

Open a terminal in this path.

Create user's bin directory (if it does not exist):

```
if [ ! -d ~/bin ]; then mkdir ~/bin; fi
```

Next, symlink `angular-gh-pages-deploy` to user's bin directory::

```
ln -s `pwd`/angular-gh-pages-deploy ~/bin/
```

Finally, source `.profile` again to make sure user's bin path is included in `$PATH`:

```
source ~/.profile
```

## Updates

From this path, open a terminal, run:

```
git pull
```

## License

This code is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
