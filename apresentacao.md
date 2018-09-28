# SISA
### Sistema de Ativos do GrupoZAP

#### Mas a final o que é esta tal de SISA ??

![alt text][logo]

[logo]: https://media.giphy.com/media/3oEjHAUOqG3lSS0f1C/giphy.gif

Como esse sistema operando em nosso gruppo, queremos mostrar que estamos precupados com os ativos (equipamentos) da empresa,
sendo assim de nossa resposabilidade saber onde e com quem esta cada ativo (equipamento) cadastrado no sistema.

#### Seu objetivo:

* Armazenar os ativos do grupo (notebooks, desktops e monitores)
* Alocar e rastrear com quem esta determinado equipamento

### Integração

* Servidor de AD - Junto ao active directory do nosso dominio conseguimos alocar cada usuário ao seu equipamento
* Slack bot - a cada inserção ou alteração de ativo é enviado uma notificação no nosso canal do Slack

### Como onde nasceu o sistema

O SISA nasceu atraveś do SNIPE-IT, um software de código aberto [LINK](https://github.com/snipe/snipe-it)
Relizamos a implantação da aplicação junto ao K8S, seu banco de dados esta rodando em uma RDS
para garantir uma boa segurança dos dados



