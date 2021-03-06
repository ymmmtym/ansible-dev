# ansible-mgmt

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/3fd9480b4f45452e9ffedfa32e980e5b)](https://www.codacy.com/gh/ymmmtym/ansible-mgmt/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ymmmtym/ansible-mgmt&amp;utm_campaign=Badge_Grade)
![Ansible](https://github.com/ymmmtym/ansible-mgmt/workflows/Ansible/badge.svg?event=pull_request)

## Requirements

- python>=3.6

### Install brew and python3 for Mac

If your mac is not installed python3.X, execute follow procedure.

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install python
echo "export PATH=/usr/local/bin:$PATH" > ~/.bash_profile
source ~/.bash_profile
```

## Usage

activate ansible env

```shell
git clone git@github.com:ymmmtym/ansible-mgmt.git
cd ansible-mgmt
python3 -m venv --clear .venv
. .venv/bin/activate
pip install -r requirements.txt
```

### Setup any hosts

Setup all

```shell
ansible-playbook site.yml
```
