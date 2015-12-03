# gitexplore
repo to explore features of git


put this file in home directory
~/.gitconfig
```
[user]
        email = joshua.calloway@gmail.com
        name = Joshua Calloway
[core]
        autocrlf = input
[filter "awsRdsBotKeys"]
        clean = sed -e 's/accessKey = .*/accessKey = ''/' -e 's/secretKey = .*/secretKey = ''/'
        smudge = sed -e 's/accessKey = .*/accessKey = 'GARBAGE'/' -e 's:secretKey = .*:secretKey = 'GARB//AGE':'
```
