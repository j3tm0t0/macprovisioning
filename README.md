# Mac Provisiong
use Ansible and Homebrew(+Cask) for semi-auto initial setup

You should set HOMEBREW_CASK_OPTS before execute ansible.

```
$ export HOMEBREW_CASK_OPTS="--appdir=/Applications"
$ ansible-playbook -i hosts -vv localhost.yml
```


