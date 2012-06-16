# buster-mode

buster-mode is a minor mode for emacs to speed up development when writing tests
with [Buster.js](http://busterjs.org).

## Keybinding

All keybindings in buster-mode start with `C-c C-b` and then a two-letter mnemonic shortcut.

* `td`: toggle-deferred will toggle // in the name of the current test.

## Development

To fetch the test dependencies:

    $ cd /path/to/buster-mode
    $ git submodule init
    $ git submodule update

Run the tests with:

    $ ./util/ecukes/ecukes features
