# ChocolateyFile

## install chocolatey
```
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```

## install chocolatey packages
```
choco install ChocolateyFile/choco_pkg.config
```


