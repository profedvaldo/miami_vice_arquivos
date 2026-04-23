# Exercício: formulário de reserva para sessão especial de cinema

## Contexto da atividade

Você recebeu uma landing page quase pronta para divulgação de uma sessão especial de cinema.  
O site já possui identidade visual, textos promocionais, imagens e uma área reservada para a reserva de vagas.

Sua tarefa será completar a parte funcional da página, construindo o formulário e aplicando validações básicas com JavaScript.

---

## Objetivo

Desenvolver um formulário de reserva integrado à landing page existente, utilizando:

- HTML
- CSS
- JavaScript

---

## O que já está pronto

A estrutura visual da landing page já foi organizada com:

- topo da página
- banner principal
- textos promocionais
- blocos de informações da sessão
- seção “Reserve sua vaga”
- espaço visual para o formulário

---

## O que deve ser feito pelo aluno

Você deverá montar o formulário dentro da área indicada no site.

### Campos obrigatórios

Crie os seguintes campos:

- Nome completo
- E-mail
- Confirmar e-mail
- Telefone
- Botão de envio

---

## Regras de validação

O formulário deve validar:

### 1. Campos vazios
Se algum campo estiver vazio, o sistema deve informar que todos os campos precisam ser preenchidos.

### 2. Confirmação de e-mail
O campo **Confirmar e-mail** deve ser igual ao campo **E-mail**.

Se os dois forem diferentes, o sistema deve exibir uma mensagem de erro.

### 3. Mensagem final
Ao final do envio:

- mostrar mensagem de erro, se houver problema
- mostrar mensagem de sucesso, se estiver tudo correto

---

## Requisitos técnicos

### HTML
- Inserir o formulário na área indicada
- Usar `input` apropriado para cada campo
- Usar `button` para envio
- Criar um espaço para exibir a mensagem ao usuário

### CSS
- Manter o padrão visual já existente
- Organizar bem os campos
- Aplicar espaçamento e alinhamento
- Destacar visualmente o formulário sem quebrar o layout da página

### JavaScript
- Selecionar os campos do formulário
- Capturar o evento de envio
- Impedir o envio padrão com `preventDefault()`
- Verificar campos vazios
- Comparar os dois e-mails
- Exibir a mensagem final na tela

---

## Estrutura esperada

Exemplo de organização:

- `index.html`
- `style.css`
- `script.js`

---

## Critérios de avaliação

A atividade poderá considerar:

- montagem correta do formulário
- funcionamento das validações
- organização do código
- clareza dos nomes usados nas variáveis e elementos
- integração visual com a landing page
- mensagem de erro e sucesso funcionando corretamente

---

## Resultado esperado

Ao final, o site deverá apresentar:

- uma landing page visualmente pronta
- um formulário funcional
- validação de campos vazios
- validação dupla do e-mail
- retorno claro para o usuário

---

## Dica

Antes de testar o sucesso, teste os erros:

- deixe campos vazios
- digite e-mails diferentes
- preencha tudo corretamente

Isso ajuda a verificar se sua validação está funcionando de verdade.

---

## Entrega

Postar os arquivos do projeto funcionando no GitHub pages, com:

- página completa
- formulário montado
- validações implementadas
- organização final do código

---

## Desafio extra

Se terminar antes, você pode melhorar a atividade com:

- borda vermelha em campo com erro
- borda verde em campo correto
- mensagem mais elegante
- máscara simples para telefone
- responsividade melhorada no celular
