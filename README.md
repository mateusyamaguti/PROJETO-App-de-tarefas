# PROJETO - App de Tarefas (Python)

> Status do Projeto: Finalizado ✅

## 🎯 Objetivo

O repositório **PROJETO-App-de-tarefas**, desenvolvido por **Mateus Yamaguti**, tem caráter **educativo**, sendo um **projeto didático voltado para o ensino de lógica de programação em Python**, com foco em **modularização, funções, estruturas de decisão, repetição e manipulação de dados**.

A aplicação foi construída para **simular um sistema simples de gerenciamento de tarefas via terminal**, permitindo que estudantes compreendam, na prática, como organizar um programa em etapas lógicas, dividir responsabilidades entre módulos (`.py`) e aplicar boas práticas de desenvolvimento.  

---

## 🧠 Conceitos Educacionais Envolvidos

- Estrutura sequencial, condicional e de repetição  
- Manipulação de listas e dicionários  
- Modularização com múltiplos arquivos Python  
- Estruturação de código por **funções**  
- Interação com o usuário via terminal  
- Organização de código e reuso de funções  

---

## 🗂️ Estrutura do Projeto

PROJETO-App-de-tarefas/
│
├── etapas[1, 2, 3].py # Contém as etapas lógicas do funcionamento da aplicação
├── main.py # Arquivo principal responsável por executar o programa
└── README.md # Documento descritivo do projeto


---

## ⚙️ Descrição das Etapas do Projeto

O código foi dividido em módulos para facilitar o aprendizado e a leitura do programa:

### `etapas[1, 2, 3].py`

Este arquivo contém **funções modulares** que representam cada parte do funcionamento da aplicação.  
As principais responsabilidades deste módulo são:

- **Definir funções** que executam etapas específicas, como:
  - Exibir o menu principal
  - Adicionar novas tarefas
  - Listar tarefas existentes
  - Concluir ou remover tarefas
- **Separar a lógica** de execução do programa da interface com o usuário, promovendo clareza e reutilização de código.
  
Essa abordagem é didaticamente importante, pois ensina aos alunos o **conceito de modularização** — dividir um programa em partes menores e independentes para facilitar a manutenção, teste e reutilização.

### `principal.py`

Arquivo responsável por **inicializar o programa**.  
É nele que as funções de `etapas[1, 2, 3.py` são chamadas, definindo a **sequência de execução** da aplicação.

Ele pode conter, por exemplo:
- Um **loop principal** que mantém o programa em execução até que o usuário decida sair.  
- Chamadas às funções de manipulação de tarefas (definidas em `etapas[1, 2, 3.py`).

---

## 🧩 Funcionalidades da Aplicação

- Criar e registrar novas tarefas  
- Listar tarefas pendentes  
- Marcar tarefas como concluídas  
- Remover tarefas  
- Encerrar o programa com segurança  

Cada funcionalidade é tratada de forma independente nas funções modulares, o que facilita a compreensão do fluxo lógico e a reutilização do código.

---

## 🚀 Como Rodar a Aplicação

### 1️⃣ Clonar o repositório

No terminal, execute:

```bash
git clone https://github.com/mateusyamaguti/PROJETO-App-de-tarefas.git
```

### 2️⃣ Acessar o diretório do projeto
```bash
cd PROJETO-App-de-tarefas
```
### 3️⃣ Executar o programa principal

Certifique-se de ter o Python 3.x instalado e rode o arquivo principal:
```bash
python main.py
```



## Desenvolvedores/Contribuintes :octocat:

Liste o time responsável pelo desenvolvimento do projeto

| [<img src="https://avatars.githubusercontent.com/u/104587996?s=400&u=3566cc0da3b05b02e8cd36bed3c709d0046f5b61&v=4" width=115><br><sub>Mateus Yamaguti</sub>](https://github.com/Diana-ops) |  
| :---: | :---: | :---: 

## Licença 

The [MIT License]() (MIT)

Copyright :copyright: 2025

