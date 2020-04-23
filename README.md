# Ansible Manjaro i3

## Usage

0. Install [Manjaro i3][manjaro].
0. Upgrade system: `$ yay`
0. Install Ansible: `$ yay ansible`
0. Clone this repository: `$ git clone https://github.com/thled/ansible-manjaro-i3.git`
0. Change to project directory: `$ cd ansible-manjaro-i3`
0. Run the Ansible Playbook: `$ ansible-playbook --ask-become-pass playbook.yml`
0. Add SSH keys manually to `~/.ssh/`
0. Reboot.

[manjaro]: https://manjaro.org/downloads/community/i3/
