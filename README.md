# Local devbox deployment

## Setup

    sudo apt-get install python-pip git-core
    sudo pip install ansible
    git clone git@github.com:berto-nens/devbox-blue.git
    cd devbox
    ansible-playbook -i local provision.yml -K
