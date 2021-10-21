# hydraV2 / hydra


## Uninstallation

###### [hydrav2.exe](http://hydrav2.ml)
  1. locate the directory "HYDRA_INFO" on your Desktop
  1. follow the steps in README.txt:
      1. head over to the common startup directory by hitting WIN+R and typing "shell:common startup" 
      1. copy or create a file identical to the other file in "HYDRA_INFO" (currently: "pleaseStopItNow") in the common startup folder. 
         This process requires you to be a System Administrator.
      1. delete "caller.exe" in %localappdata%

###### [hydra.exe](http://hydraz.ml)
  1. Stop the process:
      * Option A:
          1. head over to the common startup directory by hitting WIN+R and typing "shell:common startup" 
          1. create a file named "pleaseStopIt" in the common startup folder.
            This process requires you to be a System Administrator.
      * Option B:
          1. open the powershell
          1. type "taskkill.exe /f /im hydra* ; taskkill.exe /f /im vcsUpdater*" and hit enter
  
  1. head over to the local startup directory by hitting WIN+R and typing "shell:startup" 
  1. Delete G3_Launcher.bat
  1. Delete vcsUpdater, hydra.exe and hydra.png (where you first executed hydra.exe)
