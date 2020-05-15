Supporting material for the Paper:
#Verification of indefinite-horizon POMDPs


## Contents of this repository

* Logfiles (see subdirectory `logs` and `logs/Readme.md`)
* Model files (see subdirectory `models` and `models/Readme.md`)
* This Readme


## Storm Installation

For our experiments we consider [this](https://github.com/moves-rwth/storm/commit/b6fcdefbbb4fa33ca530f52a8f8a16222b09e71f) commit of Storm.
Please refer to the [installation guide](http://www.stormchecker.org/documentation/obtain-storm/build.html) to build storm from source.

Before the [Configuration Step](http://www.stormchecker.org/documentation/obtain-storm/build.html#configuration-step), make sure to checkout the appropriate commit using
```
git checkout b6fcdefbbb4fa33ca530f52a8f8a16222b09e71f
```

After the `make` step, the binary `$STORM_DIR/build/bin/storm-pomdp` should be available.
To see a list of possible options, simply run:
```
`$STORM_DIR/build/bin/storm-pomdp` --help
```
Example invocations are also given in the [logfiles](https://github.com/moves-rwth/indefinite-horizon-pomdps/tree/master/logs).