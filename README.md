# Submodule test

This is a test, this is only a test.

This repo is going to have another repo as a submodule, and then I'm going to rename the
submodule's default branch in GitHub and see what happens when I run `git submodule update`. Logs
below.

```shell
git submodule add https://github.com/carols10cents/miss-pickles miss-pickles
git commit -am "Adding a submodule with branch master"
# changed a file in miss-pickles

```