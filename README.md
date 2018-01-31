# Quartermaster Main Repository

Quartermaster is a suite of command line tools and build system
plugins that instruments software builds to create FLOSS compliance
documentation and support compliance decision making. It executes as
part of a software build process to generate reports about the
analysed product.

## Cloning the Quartermaster repositories using the master repository

Quartermaster uses Git submodules to combine the compliance toolchain,
the demo cases, the analysis tools and plugins and other elements in a
versioned fashion. To check out all elements of Quartermaster, clone
recursively:

	> git clone --recursive https://github.com/QMSTR/qmstr-all.git

## Repository setup

The individual repositories are configured to match the currently
checked out branch of the `qmstr-all` repository. Add another
repository this way:

	> git submodule add -b . <clone URL> <directory-for-submodule>/
