# ansible-common
Common ansible infrastructure management utilities organized in a way to allow distributing roles, playbooks and tasks together.


## How to start
Add this repository as a sub-module of your ansible repository, e.g. as `./run`:

```shell
$ git submodule add git@github.com:Provizanta/ansible-common.git playbooks/run
```

Follow the sub-module addition with the installation of all requirements from the `requirements.yaml` file:

```shell
$ ansible-galaxy install -r ./playbooks/run/requirements.yaml 
```
