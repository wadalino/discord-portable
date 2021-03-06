# Changelog

## 0.0.300-22 (2018/02/11)

* Move ia32/x64 to win32/win64 for arch def
* Remove nupkg file

## 0.0.300-21 (2018/02/11)

* Disable host updates (Issue #10)

## 0.0.300-20 (2018/02/08)

* Ability to pass custom args to the portable process

## 0.0.300-19 (2018/01/13)

* Rebuild electron.asar to push data directly in `data` subfolder
* No need to override USERPROFILE environment variable anymore
* Allow multiple instances (Issue #6)

> :warning: **UPGRADE NOTES**
> * Move everything in `data\AppData\Roaming\discord\*` to `data` folder and remove folder `data\AppData`.

## 0.0.300-18 (2018/01/12)

* New release of Discord : 0.0.300

## 0.0.299-17 (2017/12/14)

* New release of Discord : 0.0.299

## 0.0.298-16 (2017/11/21)

* Move app to a subfolder
* Reduce dependencies to avoid heuristic detection
* Add UPX compression

> :warning: **UPGRADE NOTES**
> * Delete all files and folders in root folder except `data` folder.

## 0.0.298-15 (2017/11/19)

* Move repository to [Portapps](https://github.com/portapps) org

## 0.0.298-14 (2017/11/11)

* New logger
* Switch to [Golang Dep](https://github.com/golang/dep) as dependency manager
* Upgrade to Go 1.9.1

## 0.0.298-13 (2017/09/04)

* Override USERPROFILE env var instead of using symlink to APPDATA to store data
* Do not migrate old data folder from APPDATA
* Reduce dependencies and system calls to avoid heuristic detection

> :warning: **UPGRADE NOTES**
> * Move the content of `data\*` in `data\AppData\Roaming\discord\`
> * Remove symlink `%APPDATA%\discord`

## 0.0.298-12 (2017/08/26)

* Discord voice error (Issue #4)
* Heuristic detection (Issue #3)
* Upgrade to Go 1.9
* Add support guidelines

## 0.0.298-10 (2017/08/09)

* New release of Discord : 0.0.298

## 0.0.297-7 (2017/07/20)

* Admin privileges not required for Setup (Issue #1)
* Small refactoring

## 0.0.297-4 (2017/05/14)

* Provide the nupkg file in the release

## 0.0.297-2 (2017/05/14)

* Move log
* Update go libs

## 0.0.297-1 (2017/05/14)

* Initial version
