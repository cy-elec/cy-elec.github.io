# HydraV2 / Hydra


## Uninstalling

###### Hydrav2.exe
  1. locate the directory "HYDRA_INFO" on your Desktop
  1. follow the steps in README.txt:
    1. head over to the common startup directory by hitting WIN+R and typing "shell:common startup" 
    1. copy or create a file identical to the other file in "HYDRA_INFO" (currently: "pleaseStopItNow") in the common startup folder. 
    1. This process requires you to be a System Administrator.
    1. delete "caller.exe" in %localappdata%

###### Hydra.exe
  1. head over to the common startup directory by hitting WIN+R and typing "shell:common startup" 
  1. create a file named "pleaseStopIt" in the common startup folder.
     This process requires you to be a System Administrator.
  1. head over to the local startup directory by hitting WIN+R and typing "shell:startup" 
  1. Delete G3_Launcher.bat
  1. Delete vcsUpdater, hydra.exe and hydra.png
