# Setting up GIT

## Requirements
 - Grab a copy of [GIT](https://git-scm.com/download/win)
 - Optional: [Get a frontend](https://git-scm.com/downloads/guis)
 
## Configuration
### Generate a key pair
 - GIT authenticates using a private and a public key pair. The public part is known to our git server and the porivate key is *secret*. **Never give away your private key to anyone!**

#### Using command line
 - Open a new (git) terminal and type
```
ssh-keygen -t ed25519
```
 - You will get asked some questions. Just continue (optional: provide a passphrase to secure your key).

#### Add your key to the Gitea account
 1. Navihate to the [Gitea instance hosted by us](http://gitea_bh.srv-6cores.batiswar.fr/)
 2. Login with your account
 3. Navigate to [your key settings page](http://gitea_bh.srv-6cores.batiswar.fr/user/settings/keys)
 4. Add your private key (you can find it inside the ```.pub``` file at ```%homedrive%%homepath%/.ssh/```)
 5. Your access is now configured!
 
### Clone a project
 1. TODO