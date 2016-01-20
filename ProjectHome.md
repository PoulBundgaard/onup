**_onup_** is the abbreviation for "online updater", current release is version 0.0.7.

**function:**

online updating the installed programs and folders.

**documentation(wiki):**

  * [ONUP lysee with ONUP (simpified chinese)](http://code.google.com/p/onup/wiki/onup_lysee_sc)
  * [ONUP lysee with ONUP (english)](http://code.google.com/p/onup/wiki/onup_lysee) **_not completed!_**

**features:**

  1. update changed files or install new files.
  1. unzip downloaded zip files.
  1. execute shell commands.
  1. detailed progress notification.
  1. supports english, simplified chinese and other languages.
  1. supports Linux, Unix, Windows, Mac and more other operating systems.
  1. free and open source: GPL2 + LGPL.

**history:**

| **version** | **date** | **main changes** |
|:------------|:---------|:-----------------|
| 0.0.7       | 2009/04/22 | fix logical mistakes of command **_gotof_** and **_gotot_** |
| 0.0.6       | 2009/04/22 | add _label_ and more commands: **_alert_**, **_confirm?_**, ... |
| 0.0.5       | 2009/04/11 | add command **_subject_** and fix some bugs |
| 0.0.4       | 2009/04/08 | add command **_rmdir_** and **_delete_** |
| 0.0.3       | 2009/04/07 | change **_onup.file.txt_** into a batch command file |

**commands:**

| **command** | **description** | **version** |
|:------------|:----------------|:------------|
| alert       | show modal a message box | 0.0.6       |
| check       | update a file already exists or install a new file | 0.0.3       |
| confirm?    | show modal a confirmation box | 0.0.6       |
| delete      | delete a file or directory | 0.0.4       |
| execute     | execute a downloaded file | 0.0.6       |
| exists?     | test if a file or directory exists | 0.0.6       |
| goto        | goto a label    | 0.0.6       |
| gotof       | goto a label when the latest command result is false | 0.0.6       |
| gotot       | goto a label when the latest command result is true | 0.0.6       |
| isdir?      | test if a directory exists | 0.0.6       |
| isfile?     | test if a file exists | 0.0.6       |
| mkdir       | create directory | 0.0.3       |
| prompt      | set current prompt | 0.0.6       |
| reboot      | stop updating and reboot the computer | 0.0.6       |
| regsvr      | register COM DLL server (windows only) | 0.0.6       |
| rmdir       | remove directory including its sub directories and files | 0.0.4       |
| shell       | execute shell command line | 0.0.3       |
| stop        | stop updating progress | 0.0.3       |
| subject     | set subject label | 0.0.5       |
| unregsvr    | unregister COM DLL server (windows only) | 0.0.6       |
| unzip       | unzip a ZIP file to its location | 0.0.3       |

**development:**

**_onup_** is being developed with **_[Lazarus](http://www.lazarus.freepascal.org/)_** (**_[Free Pascal](http://www.freepascal.org/)_**).

**contact:**

find me **_[here](http://www.lysee.net/author.html)_** or email to [libudi@hotmail.com](mailto:libudi@hotmail.com), everything is welcome!