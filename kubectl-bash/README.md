# kubectl-django
Provide various shell entrypoints to work with Django pods in Kubernetes.

## Usage
```
$ k django -h
Exec into the django pod of the current namespace...
kubectl django [-b]	 ...using bash (default if no option)
kubectl django -s	 ...using sh
kubectl django -m	 ...using manage.py shell_plus
kubectl django -o	 ...using manage.py shell
kubectl django -d	 ...using manage.py dbshell or pgcli if present

Requires kubens for namespace selection
```

## Installation
```shell
git clone git@github.com:itsolutionsfactory/kubectl-plugins.git
cd kubectl-plugins/kubectl-django
./install
```
