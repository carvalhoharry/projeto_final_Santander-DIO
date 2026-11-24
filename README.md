# DIO Agent — Mentor de Cibersegurança e AppSec

Este repositório apresenta uma evolução do **DIO Agent** (`digitalinnovationone/dio-agent`) executada no **Hermes**, transformando o agente em um mentor de análise de vulnerabilidades e validação de segurança por meio de engenharia de contexto em arquivos Markdown — sem treinamento de modelo.

## Especialização e Motivação

Agentes genéricos costumam responder de forma direta com comandos ou trechos corrigidos antes mesmo de entender o ambiente, a exposição na rede, os dados sensíveis envolvidos ou os controles já existentes.

Para atuar como um analista de segurança em cenários de estudo e revisão defensiva, o agente foi especializado para:
* **Investigar o contexto antes de agir:** fazer perguntas objetivas sobre exposição, privilégios, dados e finalidade do ambiente antes de sugerir comandos ou alterações.
* **Avaliar risco de forma estruturada:** fundamentar diagnósticos nos conceitos de vulnerabilidade, ameaça, risco e **Tríade CIA** (Confidencialidade, Integridade e Disponibilidade), classificando probabilidade, impacto e severidade.
* **Orientar correção e validação:** explicar o mecanismo da falha de forma defensiva, propor mitigação segura e ajudar a comprovar que a correção funcionou em laboratório.

## Arquivos Criados e Alterados

* **`AGENTS.md`**: adicionadas entradas na tabela de skills para que o agente identifique quando acionar as habilidades de análise de vulnerabilidades e testes de segurança.
* **`agent/persona.md`**: incluída diretriz de postura de mentor em cibersegurança/AppSec, priorizando investigação de contexto, raciocínio defensivo e clareza conceitual.
* **`agent/knowledge/security-basics.md`**: base conceitual com definições de ativo, vulnerabilidade, ameaça, risco, Tríade CIA, matriz qualitativa de severidade e princípios defensivos.
* **`skills/vulnerability-analysis/SKILL.md`**: roteiro operacional seguido pelo agente com triagem de contexto, diagnóstico técnico, avaliação de risco e orientação de remediação/validação.
* **`skills/vulnerability-analysis/README.md`**: documentação da skill voltada para leitura humana.
* **`skills/security-testing/SKILL.md`** *(melhoria escolhida)*: roteiro complementar para estruturar testes defensivos em laboratório (fluxo legítimo, falha controlada e resiliência de entrada) e validar mitigação.
* **`skills/security-testing/README.md`**: documentação da skill de testes de segurança.

## Como Rodar no Hermes

1. Clone este repositório e acesse a pasta raiz do projeto no terminal (ex.: terminal do VS Code):
   ```bash
   git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
   cd SEU-REPOSITORIO


