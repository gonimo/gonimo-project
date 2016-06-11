GONIMO
======

Initial project setup

...in a finite number of simple steps:
--------------------------------------

- install git
- install [ghc-7.10.3][1]
- clone & fork the following repos, all to a single directory (for stack)

```
git clone https://github.com/gonimo/gonimo-back
git clone https://github.com/eskimor/purescript-bridge
git clone https://github.com/eskimor/servant-purescript
git clone https://github.com/eskimor/servant-subscriber
```

- install [stack][2]

```
stack build
```

Usagage
-------

This repo will be used to provide a working setup of all master branches.

To update all sub-repositories at the moment `git checkout master` of each
sub-project and `git pull origin master` manually.

Automated workflow will eventually be provided.

[1]: https://www.haskell.org/
[2]: http://docs.haskellstack.org/en/stable/README/
