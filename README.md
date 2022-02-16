# The Kissat Extras SAT Solver

This is a fork of Armin Biere's Kissat SAT Solver ([arminbiere/kissat]). Kassat
Extras aims to provide additional functionality currently not available in the
upstream version of Kissat.

[arminbiere/kissat]:https://github.com/arminbiere/kissat

## New functionality

Not much so far, this is a work in progress.

  * `compile_commands.json` generation from `./configure`

## Why a Fork?

Currently, the upstream project does not accept external contributions. This
makes a fork the only option.

## Source Code Formatting

Note that I reformatted all source files before I added any new functionality.
While I usually try to follow existing conventions when working on an existing
project, I make an exception for the GNU code style used by the upstream
project.

Besides reformatting, I also adjusted the `make indent` target to use `astyle`
instead of GNU `indent`. If it becomes necessary, it should be possible to
mostly automate conversion of individual patches from one style to another.

## Original Readme

Kissat is a "keep it simple and clean bare metal SAT solver" written in C.
It is a port of CaDiCaL back to C with improved data structures, better
scheduling of inprocessing and optimized algorithms and implementation.

Coincidentally "kissat" also means "cats" in Finnish.

Run `./configure && make test` to configure, build and test in `build`.
