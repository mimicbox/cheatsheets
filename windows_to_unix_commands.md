# Windows to UNIX Command Cheat Sheet

Windows PowerShell has several transition aliases that allow UNIX and CMD users
to use familiar command names in Windows PowerShell. The most common aliases are
shown in the table below, along with the Windows PowerShell command behind the
alias and the standard Windows PowerShell alias if one exists.

|    CMD Command    | UNIX Command |   PowerShell Command  | PowerShell Alias |
|-------------------|--------------|-----------------------|------------------|
| dir               | ls           | Get-ChildItem         | gci              |
| cls               | clear        | Clear-Host (function) | cls              |
| del, erase, rmdir | rm           | Remove-Item           | ri               |
| copy              | cp           | Copy-Item             | ci               |
| move              | mv           | Move-Item             | mi               |
| rename            | mv           | Rename-Item           | rni              |
| type              | cat          | Get-Content           | gc               |
| cd                | cd           | Set-Location          | sl               |
| md                | mkdir        | New-Item              | ni               |
| pushd             | pushd        | Push-Location         | pushd            |
| popd              | popd         | Pop-Location          | popd             |

> Source: [Compatibility Aliases](https://msdn.microsoft.com/en-us/powershell/scripting/getting-started/cookbooks/appendix-1---compatibility-aliases)
