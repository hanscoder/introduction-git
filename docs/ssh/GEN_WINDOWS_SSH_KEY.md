# How to set up an SSH key in windows

## Git Bash

Git Bash is automatically installed while installing Git for windows. 

### Generating an SSH key

First read the recommendation. Then, in Git Bash run the command **ssh-keygen** and follow the instructions.

```shell
$ ssh-keygen
```

The result is a public/private key pair which you can find in the hidden directory .ssh located in your home directory.
One can find two files, the private key (id_rsa) and the public key (id_rsa.pub).

The **.ssh** directory should look like the following example:
````shell
.ssh
├── id_rsa
├── id_rsa.pub
└── known_hosts
````

> #### Recommendation
> 
> - Never share your private key with anyone else. This is your secret.
> - Use the default name for the generated files
> - Enter a passphrase for your private key
> - Use other names if you already have a public/private key pair


