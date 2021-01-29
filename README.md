# Auto Setup

My tentative of making my machine setup easier and documented.

## Macbook

    $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

    $ brew install ansible

    $ ansible-playbook macbook.yml

## WSL

    $ apt update && apt upgrade -y

    $ apt install ansible

    $ ansible-playbook wsl.yml
