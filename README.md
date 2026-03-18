# 📚 Sistema de Biblioteca em C

Projeto desenvolvido em linguagem C com foco no aprendizado de lógica de programação, estruturas de dados, modularização e manipulação de memória.

---

## 🚀 Funcionalidades

* 📖 Cadastro de livros
* 📋 Listagem de livros cadastrados
* 🔄 Controle de disponibilidade (disponível ou emprestado)
* 👤 Registro de empréstimos
* 📑 Listagem de empréstimos realizados

---

## 🛠️ Tecnologias e Conceitos

* Linguagem C
* Structs (estruturas de dados)
* Arrays
* Alocação dinâmica de memória (`calloc`)
* Ponteiros (passagem por valor e por referência)
* Modularização com funções
* Manipulação de strings (`fgets`, `strcspn`)
* Controle de fluxo (`switch`, `while`)

---

## 🧠 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar:

* Organização de código em múltiplas funções
* Separação de responsabilidades (código mais limpo e reutilizável)
* Manipulação segura de entrada de dados
* Gerenciamento de memória em C
* Simulação de um sistema real simples (biblioteca)

---

## 📂 Estrutura do Projeto

O sistema é dividido em funções responsáveis por cada parte da aplicação:

* `main` → controla o fluxo do programa (menu)
* `cadastrarLivro` → adiciona novos livros
* `listarLivros` → exibe os livros cadastrados
* `realizarEmprestimos` → registra empréstimos
* `listarEmprestimos` → exibe os empréstimos
* `liberarMemoria` → libera memória alocada

---

## 📌 Observações

* O sistema funciona em memória (os dados não são salvos em arquivo).
* Limite de livros e empréstimos definido por constantes no código.
* Projeto voltado para fins educacionais.

---

## 📈 Próximas Melhorias

* [ ] Implementar devolução de livros
* [ ] Remoção de livros
* [ ] Persistência de dados em arquivo (`.txt`)
* [ ] Melhorias na interface do terminal

---

## 👨‍💻 Autor Márcio Moraes

Desenvolvido por você durante os estudos de Engenharia de Software 🚀