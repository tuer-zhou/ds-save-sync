# ds-save-sync
Homebrew software to sync save files from ds 

<img width="1448" height="1086" alt="grafik" src="https://github.com/user-attachments/assets/d44387cd-976c-459b-89ff-cbae791dd4ae" />


## 1. Introduction

This template contains code to build a project with custom ARM9 and ARM7 code.

Build it with the following command:

```bash
make
```

This should have generated a NDS ROM that you can run on any emulator or
flashcart.

To do a verbose build, run `make` like this (this also works for the Makefile
of the SDK):

```bash
VERBOSE=1 make
```

## 2. Makefile instructions

The paths in the Makefile that refer to source code, includes, graphics, data,
etc, must be inside the folder of the project. That means you can't use `..`
in a path to go one level up from the Makefile.

If you really need to use folders outside of the folder of the project, create a
symlink to the destination, or build the other code as a static library and link
it with the project.

## License

This template is licensed under the following license:

**CC0 1.0 Universal (CC0 1.0)**
**Public Domain Dedication**

You may use this code and modify it without the need to give credit in any way.
