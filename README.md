# opencilk-feedstock

This repository is a feedstock for distributing OpenCilk through `conda`. Since OpenCilk is currently not uploaded to Conda Forge, you can instead build it
yourself and install locally.

To do this:
1. Clone the repository.
2. Run `conda mambabuild opencilk-feedstock`.
3. Run `conda install opencilk-compiler --use-local`.

This feedstock currently only supports linux64.
