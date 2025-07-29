# hemosc-doador-app
Aplicativo para smartphone de doadores de sangue / plaquetas

Iniciando o projeto inspirado na playlist:
https://www.youtube.com/watch?v=SOHd4tNWR5s&list=PLRpTFz5_57cvJyGFOD-Jx_cYqc1t2Wjk1&index=4&ab_channel=DeividWillyan%7CFlutter

Conforme video 2 : Curso Fullstack Dart e Flutter: 02 - Organização e Arquitetura,

Criamos uma organização:
https://github.com/organizations/hemoscapp/

Com os repositorios:
- https://github.com/hemoscapp/base-backend
- https://github.com/hemoscapp/base-web
- https://github.com/hemoscapp/base-app

Trello:
- https://trello.com/b/rPLh0DQb/hemosc-app

Diagramas:
- https://app.diagrams.net/#Hhemoscapp%2Fbase-app%2Fmain%2FSistema%20Hemosc.drawio#%7B%22pageId%22%3A%22QvE5s0dXJsq5SlCrJO8p%22%7D
  - inspiracao do diagrma![image](https://github.com/wfrsilva/hemosc-doador-app/assets/8933834/1a008355-40a0-4f60-921f-6c8bc483d92b)

==================================================

Existem dois tipos de doação em SC: Doador de Sangue e Doador de Plaquetas.
As regras (intervalos entre doações) e tempo de doação (tempo que o doador fica no hemosc)são distintos.
Idéia inicial é o aplicativo atender ambos so tipos de doação.

Aplicativo web e smartphone, vinculado a redes sociais (google, facebook, etc) que pode:

- Visão do doador:
  - Cadastrar data da próxima doação (google agenda); 
  - Alerta de proximidade da data de doação (google agenda);
  - Gerar o comprovamente de doador via tela (com qr code de autenticação);
  - Gerar o comprovamente de doador via PDF  para impressão (com qr code de autenticação);
  - Pedir data disponível para futura doação, já com aplicativo respeitando os prazos de descanso após cada doação (requer confirmacao do HEMOSC);
  - Gameficação de doações, entregando informações vituais (troféus, medalhas, etc);
  - Histórico e ranking de doações;


- visão do HEMOSC:
  - Enviar aviso para doadores cadastrados da necessidade de doação para um paciente ou tipo de sangue especifico;
  - Informar locais (já georreferenciados com possibilidade de usar waze ou google maps para chegar no local) onde a doação itinerante está;
  - Confirmar doação agendada pelo doador via app/web, necessária confirmação de um funcionario HEMOSC para evitar agendamentos no mesmo horário sem equipamento disponivel;
  - Autenticar doação realizada para atualziação do cartão hemosc via tela e futura impressão do mesmo pelo doador;
  - Divulgar eventos HEMOSC via redes sociais e via app/web diretamente com os doadores;
  - Tipo especifico de sangue em baixa, avisar os doadores:
    -  Avisar os Doadores desse tipo faltante;
    -  Ja no aviso e usando as regras de intervalo entre doações e tambem a disponibilidade de equipamentos pada doação já sugerir uma possivel data de doação;
  - Formularios de entrevista, poderiam ser antecipados via app, contribuindo assim tambem com a diminuição de papel.


Nota: Meu sonho de conclusao de curso é criar um sistema de utilidade publica, sendo eu um doador pensei na ideia de um aplicativo para smartphone com possibilidade de agendar sua doação, que lhe ajudasse a cumprir as regras de prazos de doação para os doadores continuos, ou ainda avisasse para os doadores esporadicos a necessidade de uma doação especifica.


## informacoes externas:
- [Micro-FrontEnds](https://github.com/DeividWillyan/Micro-FrontEnds/)
- [Diagrama micro_core](https://github.com/DeividWillyan/Micro-FrontEnds/blob/master/architecture.png)
