# Setting up GIT

## Requirements
 - Grab a copy of [GIT](https://git-scm.com/download/win)
 - Optional: [Get a frontend](https://git-scm.com/downloads/guis) (We will use https://tortoisegit.org/download/ for this tutorial)
 
## Configuration
### Generate a key pair
 - GIT authenticates using a private and a public key pair. The public part is known to our git server and the porivate key is *secret*. **Never give away your private key to anyone!**

#### using tortoisegit
 - You will be asked to provide your name and a e-mail address at first run

![grafik](https://github.com/Beyond-Heroes/howto/blob/main/config.png)
- Now generate a new key pair and save public and private key!
![grafik]([https://github.com/Beyond-Heroes/howto/blob/main/config.png](https://github.com/Beyond-Heroes/howto/blob/main/Config2.png))
- Copy the public key from the textbox and continue with "Add your key to the Gitea account"

### Add your key to the Gitea account
 1. Navihate to the [Gitea instance hosted by us](http://giteabh.srv-6cores.batiswar.fr/)
 2. Login with your account
 3. Navigate to [your key settings page](http://giteabh.srv-6cores.batiswar.fr/user/settings/keys)
 4. Add your private key (you can find it inside the ```.pub``` file at ```%homedrive%%homepath%/.ssh/``` or you just copied it from the generator)
 5. Your access is now configured!
 
### Clone a project
 1. At the website navigate to the project of your choice
 2. Copy the clone link (ssh one!)
 3. Open the context menu and select "Clone"
 ![grafik](https://github.com/Beyond-Heroes/howto/blob/main/clone.png)
 5. Paste the clone link from the website and select your private key
 ![grafik]([https://github.com/Beyond-Heroes/howto/blob/main/clone.png](https://github.com/Beyond-Heroes/howto/blob/main/clone2.png))
 6. Clone time!

# Sync with the remote repository
See https://tortoisegit.org/docs/tortoisegit/tgit-dug-pull.html

# Sending changes to the repository
See https://tortoisegit.org/docs/tortoisegit/tgit-dug-commit.html and https://tortoisegit.org/docs/tortoisegit/tgit-dug-push.html
