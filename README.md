# Exercícios de DOM (Document Object Model)

## Exercício 1 – Alterando Texto

### HTML

```html
<h1 id="titulo">Bem-vindo!</h1>

<button onclick="alterarTexto()">
    Alterar Texto
</button>
```

### Desafio

Crie uma função chamada `alterarTexto()` que altere o texto do título para:

```text
JavaScript é incrível!
```

---

## Exercício 2 – Mudando Cor

### HTML

```html
<p id="mensagem">
    Clique no botão para mudar minha cor.
</p>

<button onclick="mudarCor()">
    Mudar Cor
</button>
```

### Desafio

Ao clicar no botão:

- O texto deve ficar vermelho.
- O tamanho da fonte deve aumentar para `24px`.

---

## Exercício 3 – Contador de Cliques

### HTML

```html
<h2 id="contador">0</h2>

<button onclick="somar()">
    Clique Aqui
</button>
```

### Desafio

Cada clique deve aumentar o valor mostrado:

```text
0
1
2
3
...
```

---

## Exercício 4 – Mostrar e Ocultar

### HTML

```html
<p id="texto">
    Este texto pode desaparecer.
</p>

<button onclick="ocultar()">
    Ocultar
</button>

<button onclick="mostrar()">
    Mostrar
</button>
```

### Desafio

- O botão **Ocultar** deve esconder o parágrafo.
- O botão **Mostrar** deve exibir novamente.

---

## Exercício 5 – Alterar Imagem

### HTML

```html
<img
    id="lampada"
    src="lampada-apagada.png"
    width="200"
>

<br><br>

<button onclick="acender()">
    Acender
</button>

<button onclick="apagar()">
    Apagar
</button>
```

### Desafio

Troque a imagem da lâmpada quando os botões forem clicados.

---

## Exercício 6 – Pegando Valor do Input

### HTML

```html
<input
    type="text"
    id="nome"
    placeholder="Digite seu nome"
>

<button onclick="mostrarNome()">
    Mostrar
</button>

<p id="resultado"></p>
```

### Desafio

Exibir a seguinte mensagem utilizando o nome digitado pelo usuário:

```text
Olá, João!
```

---

## Exercício 7 – Calculadora Simples

### HTML

```html
<input type="number" id="n1">
<input type="number" id="n2">

<button onclick="somar()">
    Somar
</button>

<p id="resultado"></p>
```

### Desafio

Somar os dois números digitados e exibir o resultado.

---

## Exercício 8 – Lista de Tarefas

### HTML

```html
<input
    type="text"
    id="tarefa"
    placeholder="Nova tarefa"
>

<button onclick="adicionar()">
    Adicionar
</button>

<ul id="lista"></ul>
```

### Desafio

Ao clicar no botão:

1. Ler o texto digitado.
2. Criar um elemento `<li>`.
3. Inserir o texto dentro do `<li>`.
4. Adicionar o item à lista.

---

## Exercício 9 – Tema Claro e Escuro

### HTML

```html
<button onclick="modoEscuro()">
    Escuro
</button>

<button onclick="modoClaro()">
    Claro
</button>
```

### Desafio

Criar funções para alterar o tema da página.

### Tema Escuro

```css
background: black;
color: white;
```

### Tema Claro

```css
background: white;
color: black;
```

---

## Exercício 10 – Validação de Formulário

### HTML

```html
<input
    type="text"
    id="usuario"
    placeholder="Usuário"
>

<button onclick="validar()">
    Entrar
</button>

<p id="mensagem"></p>
```

### Desafio

Se o campo estiver vazio, exibir:

```text
Digite um usuário!
```

Caso contrário, exibir:

```text
Login realizado com sucesso!
```

---

# Desafio Final ⭐

## Sistema de Cadastro de Pessoas

### Objetivo

Criar uma página que permita cadastrar pessoas e exibir os dados em uma tabela.

### Requisitos

A página deve possuir:

- Campo Nome
- Campo Idade
- Botão Cadastrar

### Funcionalidades

Ao clicar em **Cadastrar**:

1. Ler os valores dos campos.
2. Criar uma nova linha na tabela.
3. Inserir Nome e Idade.
4. Atualizar a quantidade total de cadastrados.

### Exemplo

| Nome | Idade |
|--------|--------|
| João | 18 |
| Maria | 22 |
| Pedro | 30 |

**Total de cadastrados: 3**

---

# Métodos DOM Utilizados

| Método | Descrição |
|----------|----------|
| `getElementById()` | Seleciona um elemento pelo ID |
| `querySelector()` | Seleciona o primeiro elemento encontrado |
| `querySelectorAll()` | Seleciona vários elementos |
| `innerHTML` | Altera conteúdo HTML |
| `textContent` | Altera apenas texto |
| `style` | Modifica propriedades CSS |
| `value` | Obtém valores de inputs |
| `createElement()` | Cria novos elementos |
| `appendChild()` | Adiciona elementos ao DOM |
| `addEventListener()` | Adiciona eventos aos elementos |

---

# Entrega

- Criar uma pasta para cada exercício.
- Separar os arquivos em:
  - `index.html`
  - `style.css`
  - `script.js`
- Publicar todos os exercícios em um repositório GitHub.
- Enviar o link do repositório ao professor.

Bom trabalho! 🚀
