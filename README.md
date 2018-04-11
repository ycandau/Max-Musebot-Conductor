# Musebot Conductor

> A Musebot Conductor to launch and control musebots, either individually or as predefined sets.

The conductor adds a number of features:

- launch a musebot
- launch a set
- filter the musebot selection by type, messages sent, or messages received
- examine musebots and sets
- open their `info.txt`, `config.txt`, `run.command` (Mac) or `run.vbs` (Windows) files directly from the conductor

For more see [musicalmetacreation.org/musebots/](https://musicalmetacreation.org/musebots/)

![Max_Musebot_Conductor.png](/Max_Musebot_Conductor.png)

## Version

08.10.16

## Instructions

### Musebot folder

The conductor looks for a folder named "Musebots", anywhere up in the folder tree, from the folder containing the conductor to the root.

### Ensemble folder

The conductor looks for a folder name "Ensembles", in the same folder as the one containing the "Musebots" folder.
Ensembles files are text files


### Folder structure

```
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
```
