# Projeto de Site Dinâmico

Este projeto consiste na criação de um site dinâmico utilizando **HTML**, **CSS** e **JavaScript**, integrando-se com um back-end já implementado. O objetivo é desenvolver uma aplicação web que ofereça uma experiência interativa para o usuário, permitindo a visualização e manipulação de dados reais por meio de uma interface de front-end.

## Visão Geral do Projeto

O site possibilitará ao usuário acessar e manipular dados provenientes de um sistema de back-end por meio de APIs, promovendo uma compreensão prática sobre a integração de front-end e back-end. A documentação do back-end será disponibilizada, garantindo que o front-end possa se comunicar com as funcionalidades existentes.

## Tecnologias Utilizadas

- **HTML, CSS e JavaScript**: Desenvolvimento do front-end e manipulação dinâmica do conteúdo.
- **APIs REST**: Comunicação com o back-end para busca e manipulação de dados.

## Requisitos Funcionais

1. **Autenticação por Email**
   - Permitir que o usuário faça login por meio do email cadastrado.
   - Utilizar um token de sessão para autenticar e gerenciar o acesso.

2. **Alteração de Tema (Dark/Light)**
   - Oferecer a opção de alternância entre tema escuro e claro, proporcionando uma experiência de interface personalizada.

3. **Seleção de Quadro**
   - Permitir que o usuário selecione um quadro específico, dos disponíveis no sistema, para exibir os dados associados.

4. **Apresentação do Quadro**
   - Exibir o quadro escolhido com todas as colunas e tarefas relacionadas, possibilitando o acompanhamento do progresso das atividades.

5. **Listagem de Colunas do Quadro Selecionado**
   - Mostrar todas as colunas pertencentes ao quadro selecionado, com as divisões de cada uma.

6. **Listagem de Tarefas da Coluna**
   - Exibir todas as tarefas associadas a uma coluna específica dentro do quadro selecionado.

7. **Cadastro e Exclusão de Colunas no Quadro Selecionado**
   - Permitir ao usuário adicionar novas colunas ou remover colunas existentes do quadro selecionado.

8. **Criação, Atualização e Exclusão de Tarefas**
   - Possibilitar ao usuário criar, atualizar ou excluir tarefas em qualquer coluna do quadro.

## Estrutura do Projeto

- **index.html**: Estrutura principal da página.
- **styles.css**: Estilos e design do site, incluindo suporte para temas escuro e claro.
- **script.js**: Lógica de interação e conexão com o back-end via APIs.
- **auth.js**: Gerenciamento de
