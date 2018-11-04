# Oficina de Docker

## Instruções de Instalação

#### Instalação no Windows
> Windows 10 64bit Pro, Enterprise ou Education:
> [*Download Docker for Windows*](https://store.docker.com/editions/community/docker-ce-desktop-windows)

> Outras versões do Windows:
> [*Download Docker Toolbox for Windows*](https://download.docker.com/win/stable/DockerToolbox.exe)

#### Instalação no macOS
> macOS El Capitan 10.11 ou mais nova:
> [*Download Docker for Mac*](https://store.docker.com/editions/community/docker-ce-desktop-mac)

> Outras versões do macOS:
> [*Download Docker Toolbox for Mac*](https://download.docker.com/mac/stable/DockerToolbox.pkg)

#### Instalação no Linux

> [*Instruções para Fedora*](https://docs.docker.com/install/linux/docker-ce/fedora/)

> [*Instruções para CentOS*](https://docs.docker.com/install/linux/docker-ce/centos/)

> [*Instruções para Ubuntu*](https://docs.docker.com/install/linux/docker-ce/ubuntu/)

> [*Instruções para Debian*](https://docs.docker.com/install/linux/docker-ce/debian/)

Após finalizar a instalação no Linux, execute os comandos:
```
###/Cria grupo docker caso não exista
sudo groupadd docker

### Adiciona o usuário atual ao grupo docker.
### Isso garante que o usuário atual tenha permissão para executar comandos do docker sem o sudo
sudo usermod -aG docker $USER

### Faz o download do docker-compose
sudo curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

### Torna o docker-compose executável
sudo chmod +x /usr/local/bin/docker-compose
```
