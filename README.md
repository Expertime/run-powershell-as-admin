# Run PowerShell as Admin

Sometimes, even if you have the administrator rights in Windows, a command has to be run 'As Administrator'.

This script is meant to do just that.

## Example
If I need to run the following powerShell command 'As Administrator'
```shell
> .\myscript.ps1 -Arg1 'arguments n°1'
```
It will look like this:
```shell
> .\run_as.ps1 -FilePath myscript.ps1 -Arguments '-Arg1 "arguments n°1"'
```
or
```shell
> .\run_as.ps1 myscript.ps1 '-Arg1 "arguments n°1"'
```
(single and double quotes are important)