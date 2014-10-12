fedora-setup-scripts
====================

A collection of scripts that aim to get a fresh Fedora installation closer to
how I like it.

The scripts do things like:-

 - Improve the basic user experience by fixing annoyances and adding features.
 - Install and configure software that I usually use.
 - Set up development tools for projects on which I often work.

Several things are hard-coded for my personal setup. At some point I will
extract all the specific stuff to some config that can be edited before
running bootstrap.


## Installation

The bootstrap script will clone this repository into
`~/src/davidmason/fedora-setup-scripts` and run or offer to run each of the
top-level scripts to get everything set up.

```bash
wget https://raw.githubusercontent.com/davidmason/fedora-setup-scripts/master/bootstrap
chmod +x bootstrap
./bootstrap
```


