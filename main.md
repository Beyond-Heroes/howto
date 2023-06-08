# Setting up GIT

## Requirements
 - Install <a href="https://git-scm.com/download/win" target="_blank">GIT</a> on yur computer :-)
 - Optional: <a href="https://git-scm.com/downloads/guis" target="_blank">Get a frontend</a> (We will use https://tortoisegit.org/download/ for this tutorial)
 
## Configuration
### Generate a key pair
 - GIT authenticates using a private and a public key pair. The public part is known to our git server and the porivate key is *secret*. **Never give away your private key to anyone!**

#### using tortoisegit
 - You will be asked to provide your name and an e-mail address at first run

![grafik](https://github.com/Beyond-Heroes/howto/blob/main/config.png)
- Now generate a new key pair and save public and private key!
![grafik](https://github.com/Beyond-Heroes/howto/blob/main/Config2.png)
- Copy the public key from the textbox and continue with "Add your key to the Gitea account"

### Add your key to the Gitea account
 1. Navigate to the <a target="_blank" href="https://giteabh.srv-bw.beyond-heroes.com/">Gitea instance hosted by us</a>
 2. Login with your account
 3. Navigate to <a target="_blank" href="https://giteabh.srv-bw.beyond-heroes.com/user/settings/keys">your key settings page</a>
 4. Add your private key (you can find it inside the ```.pub``` file at ```%homedrive%%homepath%/.ssh/``` or you just copied it from the generator)
 5. Your access is now configured!
 
### Clone a project
 1. At the website navigate to the project of your choice
 2. For our projects: Activate git-lfs by opening a bash window and execute ``` git lfs install ``` (see https://youtu.be/09McJ2NL7YM?t=325)
 3. Copy the clone link (ssh one!)
 ```
 git@giteabh.srv-bw.beyond-heroes.com:BeyondHeroesGameDevelopment/Game.git
 ```
 3. Open the context menu and select "Clone"
 ![grafik](https://github.com/Beyond-Heroes/howto/blob/main/clone.png)
 4. Paste the clone link from the website and select your private key
 ![grafik](https://github.com/Beyond-Heroes/howto/blob/main/clone2.png)
 5. Clone time!

# Sync with the remote repository
See <a target="_blank" href="https://tortoisegit.org/docs/tortoisegit/tgit-dug-pull.html">LINK</a>

# Sending changes to the repository
See <a target="_blank" href="https://tortoisegit.org/docs/tortoisegit/tgit-dug-commit.html">LINK</a> and <a target="_blank" href="https://tortoisegit.org/docs/tortoisegit/tgit-dug-push.html">LINK</a>
