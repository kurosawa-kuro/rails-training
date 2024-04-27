# README

```
bundle
```


```
rubocop -A
```

```
rails db:migrate
```


```
rails s
```


```
New-Item -Path 'tmp\cache' -ItemType Directory

$acl = Get-Acl "tmp\cache"
$permission = "Users","FullControl","Allow"
$accessRule = New-Object System.Security.AccessControl.FileSystemAccessRule $permission
$acl.SetAccessRule($accessRule)
Set-Acl "tmp\cache" $acl
```