# Learn Github
## Git Bash Connect Github Error "ssh: connect to host github.com port 22: Connection timed out"
   Add the following information to the directory file \Git\etc\ SSH \ssh_config where you installed Github </br>
   * Host github.com </br>
   * User YourEmail@163.com </br>
   * Hostname ssh.github.com </br>
   * PreferredAuthentications publickey </br>
   * IdentityFile ~/.ssh/id_rsa </br>
   * Port 443

### Unfinished
