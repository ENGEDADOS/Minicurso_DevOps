# Minicurso: Introdução a DevOps - WCIT 2025

Este repositório contém o material de apresentação do minicurso "Introdução a DevOps", lecionado durante o IV Workshop de Ciência, Inovação e Tecnologia (WCIT 2025), evento realizado no campus da UFC em Itapajé.

O objetivo deste minicurso foi introduzir os participantes aos conceitos, à cultura e às ferramentas essenciais que formam o pilar do desenvolvimento de software moderno, capacitando-os a aplicar práticas de automação e colaboração em seus projetos.

## Elaboradores/Ministrantes

* Nelson Felipe Andrade Araújo
* José Levy Rodrigues da Silva

## Conteúdo Abordado

A apresentação foi estruturada em quatro módulos principais, guiando os participantes desde os fundamentos teóricos até a aplicação prática de tecnologias-chave.

### 1. Fundamentos de DevOps e Ciclo de Vida do Software

* **Definição de DevOps:** Introdução ao DevOps como uma cultura que visa unificar o Desenvolvimento (Dev) e as Operações (Ops) para encurtar o ciclo de vida de desenvolvimento e promover a entrega contínua de software com alta qualidade.
* **Ciclo de Vida de um Software:** Apresentação das fases do desenvolvimento de software: coleta de requisitos, análise e projeto, implementação, testes, implantação e manutenção.
* **Modelos de Desenvolvimento:** Comparação entre o modelo tradicional em Cascata (Waterfall) e as metodologias ágeis modernas como Scrum, Kanban e XP.

### 2. Versionamento de Código com Git e GitHub

* **Git:** Explicação sobre o que é o Git, um sistema de controle de versão open-source, e por que seu uso é fundamental para o trabalho colaborativo, backup e rastreabilidade do código.
* **GitHub:** Apresentação do GitHub como a principal plataforma de hospedagem para repositórios Git, facilitando a colaboração por meio de recursos como *Issues*, *Pull Requests* e *Branches*.
* **Guia Prático:** O módulo inclui um guia passo a passo para a instalação e configuração do Git, além de uma lista com os comandos básicos e essenciais para o dia a dia (git init, add, commit, push, pull, etc.).

### 3. Automação com Integração e Entrega Contínua (CI/CD)

* **Conceitos de CI/CD:** Definição de Integração Contínua (CI) como a prática de integrar o código de vários desenvolvedores em um repositório central de forma automatizada, e Entrega Contínua (CD) como a automação do processo de lançamento do software para produção.
* **GitHub Actions:** Apresentação do GitHub Actions como ferramenta nativa do GitHub para criar pipelines de CI/CD. O minicurso detalha a estrutura de um workflow, explicando seus componentes, como gatilhos (on), tarefas (jobs) e passos (steps).

### 4. Conteinerização com Docker

* **Introdução ao Docker:** O módulo explica como o Docker resolve o problema "na minha máquina funciona", permitindo empacotar aplicações e suas dependências em ambientes isolados e portáteis chamados *containers*.
* **Ecossistema Docker:** São detalhados os conceitos fundamentais da ferramenta:
    * **Imagem:** O "molde" read-only que define um container.
    * **Container:** A instância executável e isolada de uma imagem.
    * **Dockerfile:** O arquivo de texto com instruções para construir uma imagem Docker.
    * **Volumes:** Para persistir dados mesmo após o container ser removido.
    * **Portas:** Para expor a aplicação do container para o mundo externo.

## Como Utilizar este Repositório

Sinta-se à vontade para baixar o arquivo PDF da apresentação para consulta e estudo. Este material serve como um guia de referência para os conceitos e comandos abordados durante o minicurso. O repositório utilizado para aplicar os conceitos mostrados pode ser encontrado [neste link](https://github.com/NelsonFelipe/To-do-list-for-DevOps-concepts).