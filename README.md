# Personal Playbook

Project that stores playbook and roles oriented to the distribution configuration that I use in person.

## Requirements

- Python >=3.5
- Vagrant

## Installation

1.  Checkout the project and create a virtualenv and install the dependences:

```shell
$ git clone ...
$ cd personal_playbook
$ python3 -m venv .venv
$ source .venv/bin/activate

(.venv)$ pip install -r requirements.txt
```

2.  Run the playbook:

```shell
$ ansible-playbook -i hosts -K playbook.yml
```
