# Instalação do GitLab CE usando Shell Script
Este é um Shell Script que simplifica a instalação do GitLab Community Edition (GitLab CE) em seu servidor. O GitLab CE é uma plataforma de desenvolvimento colaborativo baseada em Git que permite hospedar repositórios de código-fonte, rastrear problemas, gerenciar projetos e muito mais.

## Instruções de Instalação
Para utilizar este Shell Script e instalar o GitLab CE, siga as etapas abaixo:

1- Abra um terminal em seu servidor e instale o curl

`sudo apt install curl git -y`

2- Copie e cole o seguinte comando no terminal e pressione "Enter":

`curl -sSL -o gitlab-ce-setup.sh https://tatehira.github.io/Gitlab-CE-Setup/ | sudo bash gitlab-ce-setup.sh`


1- O Shell Script iniciará a instalação do GitLab CE em seu servidor. Siga as instruções exibidas durante o processo de instalação.

2- Após a conclusão da instalação, o GitLab CE estará pronto para uso. Acesse o GitLab CE pelo navegador usando o endereço de IP do servidor.
