# 📘 Projeto TypeScript

Projeto desenvolvido para praticar os fundamentos da linguagem **TypeScript**, explorando tipagem estática, estruturas condicionais, loops, arrays e lógica de programação.

O objetivo é compreender as principais diferenças entre JavaScript e TypeScript, principalmente o uso de tipos e a identificação de erros durante o desenvolvimento.

---

## 🚀 Tecnologias utilizadas

* TypeScript
* Node.js
* TSX
* npm

---

## 📚 Conteúdos praticados

Durante o projeto foram desenvolvidos exercícios envolvendo:

* Tipos primitivos

  * `string`
  * `number`
  * `boolean`
* Tipagem estática
* Detecção de incompatibilidade de tipos
* Estruturas condicionais

  * `if`
  * `else if`
  * `else`
* Estrutura `switch`
* Laço `for`
* Laço `while`
* Laço `for...of`
* Arrays tipados
* Operadores aritméticos
* Operadores relacionais
* Operador de módulo `%`
* Verificação de números pares e ímpares

---

## 📝 Exercícios

O projeto contém **10 exercícios** de lógica utilizando TypeScript.

### 1. Tipos primitivos

Declaração de variáveis utilizando:

```ts
string
number
boolean
```

### 2. Verificação de tipos

Teste de atribuição de um valor `string` em uma variável declarada como `number`, permitindo observar como o TypeScript identifica incompatibilidades de tipos.

Exemplo de erro:

```text
Type 'string' is not assignable to type 'number'.
```

### 3. Maioridade

Uso de `if/else` para verificar se uma idade representa uma pessoa maior ou menor de idade.

### 4. Classificação de nota

Uso de `if / else if / else` para classificar uma nota como:

* Aprovado
* Recuperação
* Reprovado

### 5. Dia da semana

Uso de `switch` para transformar números de `1` a `7` nos respectivos dias da semana.

### 6. Loop `for`

Exibição dos números de `1` até `10`.

### 7. Loop `while`

Exibição dos números pares entre `1` e `20`.

### 8. Arrays e `for...of`

Criação de um array do tipo `number[]` e soma de todos os seus elementos.

### 9. Números ímpares

Combinação de um loop `for` com uma condicional para exibir números ímpares entre `1` e `15`.

### 10. Desafio final

Criação de um array de números e utilização de loop e condicionais para identificar cada valor como:

```text
par
```

ou

```text
ímpar
```

---

## 📁 Estrutura do projeto

```text
projeto-typescript/
│
├── src/
│   └── index.ts
│
├── dist/
│   └── index.js
│
├── .gitignore
├── package.json
├── package-lock.json
├── tsconfig.json
└── readme.md
```

A pasta `src` contém o código-fonte escrito em TypeScript.

A pasta `dist` contém o JavaScript gerado após a compilação.

---

## ⚙️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Myoui-sys/projeto-typescript.git
```

### 2. Entre na pasta

```bash
cd projeto-typescript
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute diretamente com TypeScript

```bash
npm run dev
```

O projeto utiliza o **TSX** para executar o arquivo TypeScript diretamente.

---

## 🔨 Compilando TypeScript

Para transformar os arquivos `.ts` em JavaScript:

```bash
npm run build
```

O TypeScript irá compilar os arquivos da pasta:

```text
src/
```

para:

```text
dist/
```

Depois da compilação, o JavaScript pode ser executado com:

```bash
npm start
```

---

## 📜 Scripts disponíveis

```bash
npm run dev
```

Executa:

```bash
tsx src/index.ts
```

---

```bash
npm run build
```

Executa o compilador TypeScript:

```bash
tsc
```

---

```bash
npm start
```

Executa o JavaScript compilado:

```bash
node dist/index.js
```

---

## ⚠️ Observação sobre o exercício 2

O exercício 2 contém propositalmente uma atribuição de tipo incompatível:

```ts
let nomeExercicio: number = "Nome";
```

Esse código foi utilizado para demonstrar a verificação de tipos realizada pelo TypeScript.

Por isso, o compilador apresenta o erro:

```text
Type 'string' is not assignable to type 'number'.
```

Para compilar todo o projeto normalmente, basta comentar essa linha ou utilizar um valor compatível com `number`.

Exemplo:

```ts
let nomeExercicio: number = 20;
```

---

## 🎯 Objetivo

Este projeto faz parte dos meus estudos de **TypeScript** e foi criado para reforçar conceitos fundamentais da linguagem antes de avançar para assuntos como:

* Funções tipadas
* Objetos
* Type Aliases
* Interfaces
* Union Types
* Generics
* Classes
* Programação orientada a objetos

---

## 👩‍💻 Autora

**Dacyrrôse Melo**

Desenvolvedora de Sistemas | Full-Stack

[LinkedIn](https://www.linkedin.com/in/dacyrrose-melo/) • [GitHub](https://github.com/Myoui-sys)
