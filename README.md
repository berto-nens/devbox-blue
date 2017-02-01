# Local devbox deployment

## Setup

    sudo apt-get install python-pip git-core ansible
    git clone https://github.com/berto-nens/devbox-blue
    cd devbox
    ansible-playbook -i local provision.yml -K
