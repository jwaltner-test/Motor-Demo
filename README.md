# Motor-Demo
 Demo of FRC-style project controlling the Falcon shooter motor on the 2022 swerve comp bot.

# git setup

The version of VSCode which comes with the FRC tools install does not support the updated github.com security policies for username / password authentication and requires a new version of VSCode.  Installing the new version of VSCode breaks FRC library links.  Therefore, use key authentication with github.com.

## Setup ssh keys.

Use `ssh-keygen` to generate requisite ssh keys to communicate with github.  Follow the instructions and save your key to the default location provided.  These instructions will create a public/private crypto key pair. Do not share your private key with GitHub or anyone else as this is essentially your self-managed password.  The public key can be shared freely and GitHub uses it to verify data sent was actually sent from you.

Setup a key and add it to your keychain so you don't need to type the password every time with the instructions [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

## Save the public key to GitHub.

The ssh key generated above is a public / private cryptographic key combination.  Save the public key from inside `~/.ssh/id_ed25519.pub` to your GitHub profile [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).


https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls


Create a ssh key.  The email will be used as the ssh key keyname in the `*.pub` key file.  You will need to enter a password for your private key.  While it is optional, it is recommended to set a password for your key.
```
ssh-keygen -t ed25519 -C "{your.email.or.username.for.github@address.org}"
```

Windows keys are stored here:
```
C:\Users\{username}/.ssh/id_ed25519
C:\Users\{username}/.ssh/id_ed25519.pub
```

Linux / Mac OSX keys are stored here:
```
/Users/{username}/.ssh/id_ed25519
/Users/{username}/.ssh/id_ed25519.pub
```

### OSX / Linux
Follow the instructions with ssh-keygen
```
ssh-keygen -t ed25519 -C "{your.email@address.org}"
```
### OSX / Linux
Follow the instructions with ssh-keygen
```
ssh-keygen -t ed25519 -C "{your.email@address.org}"
```

### git


