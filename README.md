# PowerLess
A set of useful utility scripts that can be used to help penetration testers and windows powerusers.

## Installation
To get started, clone this repo:
```powershell
git clone https://github.com/d0minikt/PowerLess
```
To install the modules globally, simply run the `Install` script:
```powershell
.\PowerLess\Install.ps1
```
All done! Now you can use the modules whenever you open a new powershell terminal.

## Updating
In order to update **PowerLess**, all you need to do is pull the newest version of it from GitHub:
```powershell
git pull https://github.com/d0minikt/PowerLess
```

## Modules

### `Extract`
The `Extract.ps1` script extracts the data about a particular device. It outputs the result in the drive that contains a file named `data.json` in its root. The extraction process can:
 - [x] Extract wifi passwords
 - [x] Extract device information
 - [x] Extract Chrome bookmarks & history