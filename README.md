# ⚡ Power Automate Flows Library

> Acervo **genérico e open-source** de modelos (templates) de fluxos automatizados para **Power Automate** — padrões reutilizáveis de automação com **Power Platform**.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Platform](https://img.shields.io/badge/Power%20Automate-0066FF?logo=powerautomate&logoColor=white)
![Status](https://img.shields.io/badge/status-ativo-brightgreen)

## 🎯 Objetivo

Reunir **modelos de fluxos reutilizáveis** e bem documentados que resolvem problemas comuns de automação — servindo tanto como **referência de aprendizado** quanto como **ponto de partida** para novas automações.

Todos os templates são **genéricos e fictícios**: sem dados, credenciais ou processos de organizações específicas.

## 🧭 Como usar este acervo

Cada template inclui:
- 📄 **README próprio** com objetivo, gatilho, pré-requisitos e passo a passo
- 🧩 **Descrição dos conectores** utilizados
- 🖼️ **Diagrama do fluxo** (Mermaid)
- ⚙️ **Parâmetros** a configurar
- 💡 **Variações e boas práticas**

> ℹ️ Os arquivos `.json` são **descrições estruturadas** dos fluxos (pseudo-definição genérica), pensados para fins didáticos — e **não** exports de ambientes reais.

## 📚 Catálogo de templates

| # | Template | Categoria | Gatilho |
|---|----------|-----------|---------|
| 01 | [Aprovação de solicitações](templates/01-aprovacao-de-solicitacoes/) | Aprovações | Novo item em lista |
| 02 | [Notificação de e-mail agendada](templates/02-notificacao-email-agendada/) | Notificações | Agendamento (recorrência) |
| 03 | [Backup de anexos em nuvem](templates/03-backup-anexos-nuvem/) | Integração/Arquivos | Novo e-mail com anexo |
| 04 | [Formulário → SharePoint](templates/04-formulario-para-sharepoint/) | Coleta de dados | Nova resposta no Forms |
| 05 | [Notificação no Microsoft Teams](templates/05-notificacao-teams/) | Notificações | Item criado/modificado |
| 06 | [Integração via HTTP com API](templates/06-integracao-http-api/) | Integração | Agendamento (recorrência) |

## 🗂️ Estrutura do repositório

```
power-automate-flows-library/
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── docs/
│   ├── 01-como-importar-um-fluxo.md
│   └── 02-boas-praticas.md
└── templates/
    ├── 01-aprovacao-de-solicitacoes/
    ├── 02-notificacao-email-agendada/
    ├── 03-backup-anexos-nuvem/
    ├── 04-formulario-para-sharepoint/
    ├── 05-notificacao-teams/
    └── 06-integracao-http-api/
```

## 📖 Documentação geral

- [Como importar um fluxo](docs/01-como-importar-um-fluxo.md)
- [Boas práticas de automação](docs/02-boas-praticas.md)

## 🤝 Contribuindo

Contribuições são muito bem-vindas! Envie novos templates seguindo o padrão em [`CONTRIBUTING.md`](CONTRIBUTING.md).

## 📄 Licença

Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE).

---

> ⚠️ Projeto **educativo e genérico**. Nenhum template contém segredos, conexões reais ou dados de organizações.
