# Etherpad
This repository is used to collect all Etherpad communications between the project manager and the respective teams.

## Structure
To keep order, the corresponding Etherpad backup files are stored according to a predefined scheme.

#### Directory Name
Each Etherpad session is stored under a special task name with date. File names are generated as follows. Please stick with this convention!

```<mvc-component><task-name>/<dd-mm-yyyy>/backup.txt```

- **mvc-component**: The corresponding module to which the Etherpad backup file belongs. (E.g. Control, View, etc.)
- **task-name**: The task named by the project manager to which the backup file belongs. (E.g. Spielplan)
- **dd-mm-yyyy**: The date, which is given in the form day-month-month-year. (E.g. 26-03-2020)

#### Directory structure
Whenever possible, please update the following directory histogram so that every viewer can get a quick overview of all Etherpad sessions.

```
|-- etherpad
    |-- Control
    |-- View
    |-- Logic
    |-- Datastore
        |-- Spielplan
            |-- 26-03-2020
                |-- backup.txt
    |-- LICENSE
    |-- README.md
```

## License
Please see the [license](https://github.com/PowerGrid/etherpad/blob/master/LICENSE) file for more information.
