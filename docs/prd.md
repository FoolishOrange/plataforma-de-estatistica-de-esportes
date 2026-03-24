# 📄 Product Requirements Document (PRD) - PlaceHolder

## 1. Visão Geral e Objetivo

O **PlaceHolder** é uma aplicação web que simula um site de estatísticas e banco de dados de partidas profissionais de jogos online.

**O grande diferencial (Regra de Negócio Principal):** Ao contrário dos bancos tradicionais modernos, o Roubank cobra **taxas abusivas** para absolutamente qualquer operação que o cliente realize. O objetivo do sistema é registrar as movimentações financeiras do usuário sempre subtraindo uma porcentagem ou valor fixo sob o pretexto de "taxas de manutenção" ou "impostos do banco".

## 2. Atores do Sistema

- **Administradores:** Responsável por garantir que as informações disponíveis no site estejam corretas.
- **Visitante:** Usuário não autenticado que deseja acessar as estatisticas de um time ou partida.
- **Cliente:** Usuário autenticado que deseja acessar além das estatisticas de um time ou partida, interagir no chat e comentar sobre a partida.

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (Minimum Viable Product), escritas sob a perspectiva do usuário final.

### Épico 1: Autenticação e Conta

- **US01 - Criação de Conta:** Como um Visitante, quero preencher um formulário com meus dados pessoais (Nome, Email, Senha) para criar uma nova conta no PlaceHolder.
  - _Critérios de Aceitação:_ O Email deve ser validado; todos os campos são obrigatórios; 

### Épico 2: Vizualição

- **US02 - Visualizar Time:** Como um Visitante ou Cliente, quero ver meu time, seus jogadores e suas ultimas partidas.
- **US03 - Vizualizar histórico de partidas** Como um usuário, quero ver uma lista de partidas recentes para acompanhar resultados.
- **US04 - Vizualizar estatísticas de uma partida:** Como um Visitante ou Cliente, quero entrar em uma partida que aconteceu e ver as estatísticas daquela partida.

### Épico 3: Cliente

- **US01 - Interação em chat:** Como um Cliente, quero poder interargir em um chat em tempo real com outros Clientes.
