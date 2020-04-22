# Elastic Stack
Vagrant Box Ubuntu 18.04 com a versão corrente do elasticsearch, logstash e kibana.

## Requisitos
* VirtualBox 5.2.20+
* Vagrant 2.2.6+

## Ubuntu
Usuário: vagrant
Senha: vagrant

## Vagrant
Criar e/ou iniciar uma instância na VM
```
$ vagrant up
```

Conectar a maquina via SSH
```
$ vagrant ssh
```

Desligar a instância na VM
```
$ vagrant halt
```

Remover e apagar tudo dessa instância na VM
```
$ vagrant destroy
```

## Kibana
Acessar o painel
'''
http://localhost:5601/
'''

## Referência
* [https://www.virtualbox.org/]
* [https://www.vagrantup.com/]
* [https://www.elastic.co/]