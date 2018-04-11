# Yves Candau's Musebot Conductor #

[Executable](https://www.sfu.ca/musebots)

## version ##

08.10.16

## instructions ##

### musebot folder ###

The conductor looks for a folder named "Musebots", anywhere up in the folder tree, from the folder containing the conductor to the root.

### ensemble folder ###

The conductor looks for a folder name "Ensembles", in the same folder as the one containing the "Musebots" folder.
Ensembles files are text files


### folder structure ###

Folder #A ──┬──    //     ───── Conductor folder
            │
            ├── Musebots  ──┬── Musebot1 ──┬── info.txt
            │               │              ├── config.txt
            │               │              ├── run.command or run.vbs
            │               │              └── ...
            │               │
            │               ├──    //    ──┬── Musebot2 ── ...
            │               │              ├── Musebot3 ── ...
            │               │              └── ...
            │               └── ...
            │
            └── Ensembles ──┬── Ensemble1.txt
                            ├── Ensemble2.txt
                            └── ...

## interface ##

### examining musebots ###

### selecting musebots ###

### launching musebots ###


## platform ##

Max standalone, built from Max 7.2.5 on Windows.

## license ##

Creative Commons Share Alike

## credits ##

yves candau (October 2016)
