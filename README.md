# knox-scoop

KNOX's own personal [scoop bucket](https://scoop.sh/) of applications.

Install scoop like this:
```powershell
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

Then install this software bucket like this:
```powershell
scoop bucket add knox-scoop https://git.irs.sh/KNOXDEV/knox-scoop
```

Now you can quickly and automatically install the software registered here.
For example, to install my PowerShell console configuration, just use:
```powershell
scoop install knox-console
```

That's it! The software in this bucket should not be considered stable and may not install successfully while its a Work In Progress.