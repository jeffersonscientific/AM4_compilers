# AM4_compilers
Scripts, templates, and other stuff too to compile AM4.

The objective of this repository is to separate the AM4 codebase from compile/installation scripts and run-scripts. It would make sense to submodule in AM4 (and we might do that later), or to just to manage AM4 separately. The main problem is that cmpile scripts can be highly platform specific, and so trying to maintain working compile scripts with the main codebase (in the `/exec` directory) muddies the waters for real collaboration, for example maintaining a working Fork. This way, we can submit PRs to fix code bugs or even Makefile modifications (ie, to better facilitate parallel compiles) without muddying the general codebase with platformspecific compile scripts.

The main AM4 codebase can be found at:
https://github.com/NOAA-GFDL/AM4

We maintain(ed) a fork of that code at:
https://github.com/jeffersonscientific/AM4

This fork might be discontinued, or at lest significantly modified in coming days.

See also:
https://github.com/jeffersonscientific/AM4_runtime

for runtime scripts and analysis codes and notebooks. 
