
src = source (ou código fonte)
 
dentro da src -> Seu código fonte 
fora da src -> Arquivos de configuração


Server que sustenta uma aplicação 

Conceito de arquitetura N-layer

camadas:
- Controllers: controlar quem acessa e controlar as respostas de devolução (requests e responses)

- Rotas: Quem vai o apontamento de endereços para os nossos controllers

- Model: é a forma de entrada/saída de dados no seu servidor

- Config: server para colocar configurações de outras aplicações (aplicações de terceiros) e dados não sensíveis

- Configurações não embarcadas (.env):server para isolar dados sensíveis 
