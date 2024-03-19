# How to install binjr using winget?

To install, update or remove binjr using the Windows Package Manager on Windows 10[^1] or 11, you must first ensure that the winget command line tool is available on you machine. 
You can verify that it is installed by opening a terminal window and type:
```
winget --info
```

If the winget CLI is not already installed you can install it from the [Microsoft Store](https://www.microsoft.com/p/app-installer/9nblggh4nns1) or [manually](https://github.com/microsoft/winget-cli/releases)

Then, to install binjr on your local machine:
```
winget install binjr
```

To update an installed copy to the latest version:
```
winget upgrade binjr
```

To uninstall binjr from your local machine:
```
winget uninstall binjr
```

Please refer to the [documentation on the Microsoft website](https://learn.microsoft.com/en-us/windows/package-manager/winget/) for detailed information on how to use the winget tool.


[^1]: The winget command line tool is only supported on Windows 10 1709 (build 16299) or later