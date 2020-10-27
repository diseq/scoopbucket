```
. $env:USERPROFILE\scoop\apps\scoop\current\bin\checkver.ps1 -Dir . -u
. $env:USERPROFILE\scoop\apps\scoop\current\bin\checkhashes.ps1 -Dir . -Update
git add -A && git commit -m "update" && git push
```