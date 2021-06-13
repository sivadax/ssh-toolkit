# tools
https://keystore-explorer.org/downloads.html

# Cloudhub Deployments

https://help.mulesoft.com/s/article/How-to-create-HTTPS-SSL-service-in-Cloudhub#:~:text=cloudhub.io%20domain.,as%20configured%20in%20the%20application.

# ssh-toolkit
Toolkits and scripts for SSH Life make easier

### Create SSH Keys for your github account

```
  ssh-keygen -t rsa -b 4096 -C "youremail@yourdomain.com"
  eval $(ssh-agent -s)
  ssh-add ~/.ssh/id_rsa
  clip < ~/.ssh/id_rsa.pub
```

### How To Set Up SSH Keys

Step 1 — Creating the Key Pair

```
ssh-keygen -t rsa -b 4096
```

or

```
ssh-keygen -t ed25519
```

output 

```
Output
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/sammy/.ssh/id_ed25519):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/sammy/.ssh/id_ed25519
Your public key has been saved in /home/sammy/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:EGx5HEXz7EqKigIxHHWKpCZItSj1Dy9Dqc5cYae+1zc sammy@hostname
The key's randomart image is:
+--[ED25519 256]--+
| o+o o.o.++      |
|=oo.+.+.o  +     |
|*+.oB.o.    o    |
|*. + B .   .     |
| o. = o S . .    |
|.+ o o . o .     |
|. + . ... .      |
|.  . o. . E      |
| .. o.   . .     |
+----[SHA256]-----+
```


