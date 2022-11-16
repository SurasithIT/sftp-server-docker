# SFTP

- [emberstack/sftp docker image](https://github.com/emberstack/docker-sftp)

### generate ssh keys command

```sh
mkdir -p key
ssh-keygen -t ed25519 -f ./key/ssh_host_ed25519_key < /dev/null
ssh-keygen -t rsa -b 4096 -f ./key/ssh_host_rsa_key < /dev/null
```
