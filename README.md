# GitInstallationParameters
My custom Git Installation Parameters

## How to use it

1. Download Git from https://git-scm.com/download/win
2. Open a shell with wget program into the folder where the git installer has beed downloaded
3. Get installation options with:
```bash
wget https://github.com/Supermanuu/GitInstallationParameters/blob/af03a18851e1bf4ae361934c3f9245ec66a06645/gitInstallationParameters.ini
```
4. Start Git installation program with command line using `Powershell`:
```powershell
.\Git-XXXXXX.exe /LOADINF="gitInstallationParameters.ini" /SAVEINF="gitInstallationParameters.ini"
```
5. Check the "Show only new options" checkbox in the Git installer window
6. Finish the installation

## New option available

Could be that in the step 5 you see Next instead of Finish, this is due a new option has been added into the git installation process. You then must copy the contents of 
`gitInstallationParameters.ini` into the repo to sync that new option
