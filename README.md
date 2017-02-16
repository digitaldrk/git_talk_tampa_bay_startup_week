# Here are the commands to copy paste for installing in Mac
## Install x-code CLI
`xcode-select --install`

## Install Homebrew
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

## Make Sure Homebrew is good to go!
`brew doctor`

## Shouldn't have to update but just incase, they say it's a good habit
`brew update`

## Install Git via Homebrew
`brew install git`

## Check Git Version
`git --version`

## Configure Git to know your name
`git config —global user.name “First Last”`

## Configure git to know your email
`git config —global user.email “email_you_want_associated@commits.com”`

## Check for existing keys
`ls -al ~/.ssh`

## Generate keys
`ssh-keygen -t rsa -b 4096 -C “email@email.com”`

## Ensure ssh-agent is enabled
`eval “$(ssh-agent -s)”`

## Add your key to the ssh agent
`ssh-add ~/.ssh/id_rsa`

## To view your public ssh key
`cat ls ~/.ssh/*.pub`

## Add your key to your GitHub Account

## Test that your ssh key is connected
`ssh -T git@github.com`

# Install on a Windows machine
https://desktop.github.com/
