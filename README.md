# Notes

## Linux
### scp 
###### secure copy

```bash=
scp -r user@ip:pwd+檔案 ./ #./當前位置
```

## MongoDB
### service on
```bash=
sudo service mongod start
```
### add user(roles自尋)
```bash=
db.createUser(
{
    user: "user"
    pwd: "pwd"
    roles: [ "root" ]
})
```
