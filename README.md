# ansible-dev-rails

## execute playbook
Run ```ansible-playbook -i hosts/dev -v site.yml```.

## execute a particular part with a tag
```
$ ansible-playbook -i hosts/dev -v site.yml --tags "postgres"
```
