#strato

[![BlockApps logo](http://blockapps.net/img/logo_cropped.png)](http://blockapps.net)

Note- If you cloned this repository using git, it will be missing important components.  You need to clone this repository using "mgit" (read below for information)

Instructions for building Strato:
====================================

1. Install prerequisites:
  1. Install stack (see https://github.com/commercialhaskell/stack) -> http://docs.haskellstack.org/en/stable/install_and_upgrade/
     * sudo apt-get install cabal-install
  2. mgit: tool at http://github.com/blockapps/mgit.  After the installation, you will have a command line tool called "mgit".
```
  > git clone https://github.com/blockapps/mgit.git
  > cabal configure && cabal build && cabal install
```  
  3. Postgresql
  4. LevelDB

2. Run the following commands

```
    > mgit clone http://github.com/blockapps/strato
    > cd strato
    > stack install
```
