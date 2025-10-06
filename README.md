# LOO9_Anhanguera

# Linguagem Orientada a Objetos: Tratamento de Exceções e Submissão ao GitHub

Este repositório contém o material de apoio e o roteiro da atividade prática da disciplina de **Linguagem Orientada a Objetos (LPO/LOO)**. O foco principal é no desenvolvimento de aplicações com **Tratamento de Exceções** (Checked e Unchecked) em Java e na utilização do **GitHub** para a submissão dos trabalhos.

---

## 1. Conteúdo da Atividade Prática

O arquivo **`RAP_S1 (1).pdf`** (Roteiro de Aula Prática - Unidade 3 | Seção 1) é o guia principal para a atividade de codificação.

### 1.1. Objetivos da Prática

* **Desenvolver** uma aplicação completa utilizando o conceito de **Tratamento de Exceção**.
* **Criar as suas próprias exceções** em Java, tanto de forma **checada** (`Checked Exception`) quanto **não-checada** (`Unchecked Exception`).
* Reforçar o conhecimento na utilização da plataforma **GitHub** para versionamento de código.

### 1.2. Cenário de Implementação: Equação do 2º Grau

A prática centraliza-se no desenvolvimento de métodos que calculam as raízes de uma equação do 2º grau.

* **Métodos Chave (Java):** O roteiro propõe a implementação de quatro métodos principais para retornar as raízes, diferenciando-os pelo tipo de exceção lançada:
    * `raizEq2GrauX1_E()` e `raizEq2GrauX2_E()`: Lançam exceções **Checadas** (`NaoTemRaizesReaisException`).
    * `raizEq2GrauX1_RT()` e `raizEq2GrauX2_RT()`: Lançam exceções **Não-Checadas** (`NaoTemRaizesReaisRuntimeException`).

### 1.3. Implementações de Classes

O aluno deve criar e gerenciar as seguintes classes para cumprir o roteiro:

| Classe | Descrição |
| :--- | :--- |
| `NaoTemRaizesReaisException` | Classe de exceção personalizada que **HERDA `Exception`** (Checked). Usada quando não há raízes reais. |
| `NaoTemRaizesReaisRuntimeException` | Classe de exceção personalizada que **HERDA `RuntimeException`** (Unchecked). Usada para o mesmo cenário, mas como exceção de tempo de execução. |
| `AulaPratica1` | Classe principal para testar os métodos que lançam exceções **Checadas**. Deve obrigatoriamente usar blocos **`try-catch`** para manipulação da exceção. |
| `AulaPratica2` | Classe principal para testar os métodos que lançam exceções **Não-Checadas**. |

---

## 2. Guia de Submissão e Uso do GitHub

O arquivo **`aula8.pptx`** (Encontro 05) complementa o material, detalhando o processo de como enviar o código desenvolvido para este repositório.

### 2.1. Objetivos do Encontro

O foco desta aula é configurar o ambiente e a ferramenta de controle de versão:

* Criar conta no **GitHub**.
* Criar um **repositório público**.
* Gerar um **Token de Acesso Pessoal (PAT)**.
* Executar e testar o código (mencionando o Google Colab como ambiente de execução).
* **Compartilhar o link do repositório** com o professor.

### 2.2. Passos de Submissão (Resumo da Apresentação)

1.  **Desenvolvimento:** Implementar todo o código Java da atividade prática (`RAP_S1 (1).pdf`).
2.  **Configuração Git:** Inicializar o Git localmente ou configurar o ambiente (ex: Google Colab) para acessar o GitHub.
3.  **Criação do Repositório:** Criar um novo repositório público no GitHub.
4.  **Autenticação:** Usar o Personal Access Token para autenticar a conexão.
5.  **Push:** Enviar (fazer *push* de) todos os arquivos de código (`.java`) e o `README.md` atualizado para este repositório.

---

## 3. Requisitos para Execução

Para rodar o projeto, você precisará dos seguintes recursos:

* **Java Development Kit (JDK):** Versão compatível com o IDE.
* **IDE (Ambiente de Desenvolvimento Integrado):** Sugestões no roteiro: **NetBeans, Eclipse ou IntelliJ IDEA**.
* **Conta GitHub:** Para versionamento e submissão do trabalho final.
