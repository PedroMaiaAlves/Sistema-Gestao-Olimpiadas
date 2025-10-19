# 🏅 Sistema de Gestão das Olimpíadas (SGO)

> 📘 **Projeto de Modelagem UML**
> Modelagem de um sistema para gerenciar as Olimpíadas — incluindo competições, inscrições, locais, resultados e relatórios de medalhas.

---

## 📖 Descrição do Sistema

Com a chegada das Olimpíadas, um novo sistema de gestão é necessário para coordenar os diferentes aspectos do evento.
O **SGO** tem como objetivo permitir o gerenciamento de **competições**, **inscrições de atletas**, **alocação de locais**, **controle de resultados** e **relatórios de medalhas**.

---

## 🧠 Regras de Negócio

1. **Cadastro de Competições**

   * Permitir o cadastro de competições com nome, modalidade, data, horário, local e lista de atletas inscritos.

2. **Inscrição de Atletas**

   * Atletas de diferentes países se inscrevem em competições específicas.
   * Um atleta pode participar de várias competições, mas só pode representar **um país por modalidade**.

3. **Alocação de Locais**

   * Um local pode receber **apenas uma competição por vez**, evitando conflitos de horário.

4. **Controle de Resultados**

   * Após a realização da competição, registrar os resultados (ouro, prata e bronze).

5. **Relatórios de Medalhas**

   * Gerar relatórios de medalhas por país, exibindo o desempenho geral (ouro, prata e bronze).

---

## 👥 Atores Principais

| Ator              | Descrição                                      |
| ----------------- | ---------------------------------------------- |
| **Administrador** | Gerencia competições, locais e relatórios      |
| **Atleta**        | Realiza inscrições e participa das competições |
| **Sistema**       | Processa dados e garante regras de negócio     |

---

## 🧩 Casos de Uso Principais

| Caso de Uso                     | Descrição                                                  |
| ------------------------------- | ---------------------------------------------------------- |
| **Cadastrar Competição**        | Administrador registra nova competição                     |
| **Inscrever Atleta**            | Atleta realiza inscrição em uma competição                 |
| **Alocar Local**                | Sistema reserva o local de acordo com o horário disponível |
| **Registrar Resultados**        | Sistema ou administrador insere resultados                 |
| **Gerar Relatório de Medalhas** | Sistema gera relatório com ranking de países               |

---

## 🧱 Estrutura do Repositório

```
📦 sistema-gestao-olimpiadas
 ┣ 📂 imagens
 ┃ ┣ Diagrama de Caso de Uso SGO.png
 ┃ ┣ diagrama-de-classes.png
 ┃ ┣ Diagrama de Pacotes.png
 ┃ ┣ diagrama-de-componentes.png
 ┃ ┗ Diagrama de Implantação.png
 ┣ 📂 modelagens
 ┃ ┣ diagrama-caso-uso.puml
 ┃ ┣ diagrama-de-classes.drawio
 ┃ ┣ diagrama-pacotes.puml
 ┃ ┣ diagrama-de-componentes.drawio
 ┃ ┗ diagrama-implantacao.puml
 ┗ 📄 README.md
```

---

## 🌍 Histórias de Usuário

| Código   | História                                                                                             |
| -------- | ---------------------------------------------------------------------------------------------------- |
| **US01** | Como **administrador**, quero cadastrar novas competições para definir o cronograma oficial.         |
| **US02** | Como **atleta**, quero me inscrever em competições específicas para poder competir.                  |
| **US03** | Como **organizador**, quero alocar locais de forma a evitar conflitos de horário.                    |
| **US04** | Como **administrador**, quero registrar os resultados das competições para determinar os vencedores. |
| **US05** | Como **usuário**, quero visualizar relatórios de medalhas por país para acompanhar o desempenho.     |

---

## 🎯 Diagramas UML

### 🧩 Diagrama de Caso de Uso

![🧩 Diagrama de Caso de Uso](https://github.com/PedroMaiaAlves/Sistema-Gestao-Olimpiadas/blob/main/imagens/Diagrama%20de%20Caso%20de%20Uso%20SGO.png)

---
### 🏗️ Diagrama de Classes

![🏗️ Diagrama de Classes]

---
### 📦 Diagrama de Pacotes

![📦 Diagrama de Pacotes](https://github.com/PedroMaiaAlves/Sistema-Gestao-Olimpiadas/blob/main/imagens/Diagrama%20de%20Pacotes.png)

---

### ⚙️ Diagrama de Componentes
![⚙️ Diagrama de Componentes]


---
### 🖥️ Diagrama de Implantação

![🖥️ Diagrama de Implantação](https://github.com/PedroMaiaAlves/Sistema-Gestao-Olimpiadas/blob/main/imagens/Diagrama%20de%20Implanta%C3%A7%C3%A3o.png)

---

## 💡 Tecnologias Utilizadas

* 🖊️ **PlantUML** → para a modelagem dos diagramas
* 🗂️ **Markdown (README.md)** → para documentação no GitHub
* 🧠 **Modelagem Orientada a Objetos (UML)**

---

## ✨ Autor

👤 **Pedro Henrique Maia**
📘 Projeto acadêmico — Engenharia de Software
💻 [GitHub](https://github.com/PedroMaiaAlves)

---
