![alt text](https://github.com/brunoleite/onde-me-amam/blob/master/resources/marcaweb.png "Onde Me Amam")

# Onde Me Amam

Este é um projeto para classificar lugares para o público LGBT.

## Motivação

O projeto nasceu no evento Rails Girls BH 2015. O intuito é criar uma aplicação onde o público LGBT seja capaz de classificar, positivamente ou negativamente, locais onde frequentam.

## Instalação

### Pré-requisitos
* [VirtualBox](https://www.virtualbox.org/wiki/Download_Old_Builds_4_3) - 4.3.30
* [Vagrant](https://www.vagrantup.com/downloads.html) - 1.7.4 ou superior
* [ansible](http://www.ansible.com/) - 1.9.3 ou superior

### Instalação
- Faça o clone desse repositório para seu disco local:
```
git clone git@github.com:brunoleite/onde-me-amam.git
```

- Vá para o diretório /onde-me-amam:
```
cd onde-me-amam
```

- Instale as dependência do Ansible:
```
ansible-galaxy install -r requirements.txt
```

- Crie uma máquina virtual utilizando o Vagrant (pode demorar): 
```
vagrant up
```

- Acesse a máquina virtual:
```
vagrant ssh
```

- Vá para o diretório /app:
```
cd app
```

### Iniciando o servidor

- Execute a aplicação:
```
npm start
```

A aplicação deveria estar disponível em `localhost:8000`, acessada da sua máquina local.

### Iniciando o cliente

- Vá para o diretório /client:
```
cd client
```

- Execute a aplicação:
```
ionic serve
```

Os dados para acesso a aplicação mobile será exibida no console.

## Testes

Descrever como será os testes.

## Integração Contínua

Esse projeto usa [Snap-CI](https://snap-ci.com/) para Integração Contínua, você pode ver o [pipeline](https://snap-ci.com/brunoleite/onde-me-amam/branch/master). 

## Produção

Descrever como será o acesso a produção.

## Contribuições

1. Faça o fork do projeto
2. Crie sua feature branch (`git checkout -b my-new-feature`)
3. Faça commit das suas mudanças (`git commit -am 'Adiciona uma feature'`)
4. Faça o push para a branch (`git push origin my-new-feature`)
5. Crie um novo Pull Request

Caso tenha alguma sugestão, por favor, registre em [github issues](https://github.com/brunoleite/onde-me-amam/issues)

## License

Este projeto utiliza a licença [MIT](https://opensource.org/licenses/MIT).
