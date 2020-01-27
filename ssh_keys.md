## generate ssh key on computer 

used for making a secure communication tunnel between two devices

```bash
ssh-keygen
```

home/minnalis/.ssh/ is the path to the keypair (public/private)
id\_rsa is the private file/key (often with .pem extension)
id\_rsa.pub is the public file/key


after pressing three times <enter>, the file is generated in the directory that were working on

only share the public key with 3rd party

## view public key

```bash
cat .ssh/id_rsa.pub
```

then copy the whole output to the ssh configuration that you'll use
the last comment on the ssh file is this thing ...@... - which means $USER @ $HOSTNAME

uwu
