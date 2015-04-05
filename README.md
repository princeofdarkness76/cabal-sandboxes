cabal-sandboxes
---------------

Cabal sandboxes for Haskell programs/libraries which I just want to use (not
hack on).

The idea:

* Create a sandbox in a subdirectory
* Install packages into the sandbox
* Symlink binaries into `~/.bin/`, which is already on my PATH.

Also you can create `cabal.config` files for if you want a specific compiler
version (see pandoc for an example).
