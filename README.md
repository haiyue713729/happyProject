# happyProject
## Git Bash Connect Github Error "ssh: connect to host github.com port 22: Connection timed out"
### Add the following information to the directory file \Git\etc\ SSH \ssh_config where you installed Github
    Host github.com
    User YourEmail@163.com
    Hostname ssh.github.com
    PreferredAuthentications publickey
    IdentityFile ~/.ssh/id_rsa
    Port 443
