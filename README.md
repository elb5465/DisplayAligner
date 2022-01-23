# DisplayAligner
Config / Setup for various Display Alignments

- Install displayPlacer with package manager in terminal
- Open up Mac settings and change your display to desired configuration
- Use command: 'displayPlacer list' (prints out the current config details in the form of a command in your terminal)
- Create shell script, add this line to the top: '#!/bin/bash'
- Add your config details to the shell script 
i.e.: 
displayplacer "id:22C7239A-0FDE-EEC3-0284-9F3502E582D7 res:1792x1120 hz:59 color_depth:8 scaling:on origin:(0,0) degree:0" "id:51CAA4AD-9E14-1A64-0AB7-66E277FA57DE res:2560x1440 hz:59 color_depth:8 scaling:off origin:(-2560,-575) degree:0" "id:ABD7611C-4707-C5E8-651C-A070BF0638C2 res:2560x1440 hz:59 color_depth:8 scaling:off origin:(1792,-584) degree:0"
- Save it
- Right click on the file and select "Open with" -> check box "Always Open With" -> click drop-down to enable all applications -> search and select 'Terminal' -> then open
- It should now run the command in a new terminal window when you double click the file.
