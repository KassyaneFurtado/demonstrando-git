# Demonstração Git

Este repositório é um diário pratico para a demonstração das minhas habilidades no uso do Git para versionamento de código e colaboração.

## Objetivo

O objetivo deste projeto é demonstrar de forma clara e visual o meu conhecimento sobre o fluxo de trabalho essencial do Git, incluindo:

- Inicialização e configuração de um repositório.
- O ciclo de `add`, `commit` e `push`.
- A criação e gerenciamento de branches para desenvolvimento de features.
- A integração de branches usando `merge`.
- A sincronização com um repositório remoto (`fetch` e `pull`).
- A simulação de um fluxo de trabalho colaborativo através de Pull Requests.

## Fluxo de Trabalho Adotado

1. **Configuração Inicial:** O repositório foi iniciado localmente com `git init` e conectado a um repositório remoto no GitHub.
2. **Desenvolvimento em Branch:** Uma nova funcionalidade (`feature-adiciona-fluxo-trabalho`) foi desenvolvida em um branch separado para isolar o trabalho do código principal (`master`).
3. **Merge Local:** O branch da funcionalidade foi mesclado ao `master` localmente para simular uma integração simples.
4. **Simulação de Colaboração (Pull Request):** Criei um Pull Request.
5. **Sincronização:** Demonstrei como `git fetch` e `git pull` são usados para manter o repositório local atualizado com as mudanças remotas.

## Comandos Praticados

Neste projeto, utilizei ativamente os seguintes comandos:

| Comando | Descrição |
| :--- | :--- |
| `git init` | Inicia um repositório. |
| `git status` | Mostra o status dos arquivos. |
| `git add` | Adiciona alterações à staging area. |
| `git commit` | Salva as alterações no histórico. |
| `git push` | Envia os commits para o repositório remoto. |
| `git pull` | Puxa e mescla alterações do repositório remoto. |
| `git fetch` | Baixa alterações remotas sem mesclar. |
| `git diff` | Verifica as diferenças entre arquivos. |
| `git branch` | Cria e gerencia branches. |
| `git checkout` | Navega entre branches. |
| `git merge` | Integra as mudanças de um branch em outro. |

