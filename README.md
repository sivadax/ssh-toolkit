# ssh-toolkit
Toolkits and scripts for SSH Life make easier

# Create SSH Keys for your github account

```
  ssh-keygen -t rsa -b 4096 -C "youremail@yourdomain.com"
  eval $(ssh-agent -s)
  ssh-add ~/.ssh/id_rsa
  clip < ~/.ssh/id_rsa.pub
```
