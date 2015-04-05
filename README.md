cabal-sandboxes
---------------

Cabal sandboxes for Haskell programs/libraries which I just want to use (not
hack on).

The idea:

* Create a sandbox in a subdirectory
* Install packages into the sandbox
* Symlink binaries into `~/.bin/`, which is already on my PATH.

Also you can create `cabal.config` files for if you want a specific compiler
version. For example, pandoc has:

```
with-compiler: /opt/ghc/7.8.3/bin/ghc
```

because it doesn't yet build with ghc 7.10.
