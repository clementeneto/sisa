# SISA
### Sistema de Ativos do GrupoZAP

#### Mas a final para que server esse tal de SISA ??

![alt text][logo]

[logo]: https://media.giphy.com/media/3oEjHAUOqG3lSS0f1C/giphy.gif

Com esse sistema operando no grupozap, queremos mostrar que estamos preucupados com os ativos (equipamentos) da empresa,
sendo assim de nossa resposabilidade, saber onde e com quem esta alocado cada ativo (equipamento) cadastrado no sistema.

#### Seu objetivo:

* Armazenar os ativos do grupo (notebooks, desktops e monitores)
* Alocar e rastrear com quem esta determinados equipamentos

### Integração

* Servidor de AD - Junto ao active directory do nosso dominio conseguimos alocar cada usuário ao seu equipamento
* Slack bot - a cada inserção ou alteração de ativo é enviado uma notificação no nosso canal do Slack

### Como onde nasceu o sistema

O SISA nasceu atraveś do SNIPE-IT, um software de código aberto [LINK](https://github.com/snipe/snipe-it), a 
aplicação esta rodando no K8S (Kubernetes), seu dados estão sendo armazenaso em uma RDS para garantir uma boa segurança das informaçẽos.
