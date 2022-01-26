# Documentation for my Ansible installation in my personal infrastructure

## First steps and verification



I am using Ubuntu Server 20.
The first thing i do before install an app, is execute a update command.


```sh
$ sudo apt update
```



I can check my Python version using this command:

```sh
$ sudo python --version
```


Maybe you have old version of python, but, you can check if was installed the new version:

```sh
$ phyton3 --version
```


## Next steps

> Now you can proceed with the next step of installation




```sh
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```


> If you want, you can install other version of python, for example: 
```sh
$ sudo apt install python3-pip
```

So, in this case you must install ansible inside this python version:

```sh
$ sudo pip3 install ansible
```


## Now verify the installation

> Check your ansible version

```sh
$ ansible --version
```

And you can use the ping module of ansible:
```sh
$ ansible localhost -m ping
```

This is the complete [code](Command.sh)
