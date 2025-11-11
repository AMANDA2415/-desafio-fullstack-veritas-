# Desafio Fullstack Veritas - Gerenciamento de Tarefas

## Visão Geral

Aplicação web simples para gerenciamento de tarefas com funcionalidades completas de criar, editar, excluir e mover tarefas entre as colunas **"A Fazer"**, **"Fazendo"** e **"Feito"**.  
A aplicação salva os dados localmente no navegador, garantindo persistência sem necessidade de backend.

---

## Funcionalidades

- CRUD completo: criação, edição e exclusão de tarefas.  
- Arraste e solte para movimentar tarefas entre colunas.  
- Persistência de dados usando LocalStorage do navegador.  
- Interface simples, limpa e intuitiva.

---

## Como Usar

1. Clone ou baixe este repositório.  
2. Abra o arquivo `index.html` em um navegador moderno (Chrome, Firefox, Edge).  
3. Crie novas tarefas utilizando o campo de entrada.  
4. Edite ou exclua tarefas usando os botões disponíveis.  
5. Mova tarefas entre colunas arrastando e soltando.  
6. As tarefas são salvas automaticamente e permanecem ao reabrir a aplicação.

---

## Fluxo do Usuário

Usuário abre a aplicação (abre o arquivo no navegador)  
↓  
Usuário cria uma tarefa preenchendo o campo e clicando em **"Adicionar"**  
↓  
Tarefa aparece na coluna **"A Fazer"**  
↓  
Usuário pode:  
- Editar tarefa (clicar no ícone de lápis)  
- Excluir tarefa (clicar no ícone de X)  
- Mover tarefa arrastando para **"Fazendo"** ou **"Feito"**  
↓  
Mudanças são salvas automaticamente no armazenamento local do navegador  
↓  
Usuário pode fechar e reabrir a aplicação com as tarefas persistidas  

---

## Arquitetura da Aplicação

- Interface (frontend) <--> Usuário realiza ações (criar, editar, mover, excluir)  
  ↓  
- Dados são armazenados e recuperados do LocalStorage (persistência local no navegador)  
  ↓  
- Interface atualiza visualização conforme as alterações realizadas

