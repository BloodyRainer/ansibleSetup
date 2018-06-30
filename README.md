# Usage
```
sudo ansible-playbook -i inventory.txt nummer4.yaml
```

use the -t option to only run tasks with a specifig tag, e.g.:
```
sudo ansible-playbook -i inventory.txt nummer4.yaml -t apt
```