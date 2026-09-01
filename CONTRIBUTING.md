# Contribuindo

Obrigado pelo interesse em contribuir com a **Power Automate Flows Library**! 🎉

Este é um acervo **educativo, open-source e agnóstico de organização**.

## 🧭 Princípios

- **Conteúdo genérico**: sem dados, credenciais ou processos de organizações específicas.
- **Segurança**: nunca inclua segredos, tokens, conexões reais ou dados corporativos.
- **Exemplos fictícios**: sites, e-mails e listas devem ser claramente fictícios (ex.: `exemplo.com`).
- **Documentação**: todo template deve ser autoexplicativo.

## 📦 Padrão de um novo template

Crie uma pasta em `templates/NN-nome-do-template/` contendo:

```
templates/NN-nome-do-template/
├── README.md              # Objetivo, gatilho, conectores, passo a passo, diagrama
└── flow.example.json      # Descrição estruturada GENÉRICA do fluxo (fictícia)
```

O `README.md` do template deve incluir:
- [ ] 🎯 Objetivo
- [ ] ⚡ Gatilho
- [ ] 🧩 Conectores utilizados
- [ ] 🖼️ Diagrama (Mermaid)
- [ ] ⚙️ Tabela de parâmetros
- [ ] 📝 Passo a passo
- [ ] 💡 Variações e boas práticas

## 🌿 Fluxo de contribuição

1. Faça um **fork** do repositório.
2. Crie uma branch: `feat/template-nome` ou `docs/...`.
3. Adicione seu template seguindo o padrão acima.
4. Atualize o **catálogo** no `README.md` principal.
5. Abra um **Pull Request** descrevendo o caso de uso.

## ✅ Conventional Commits

Exemplos:
- `feat: adiciona template de sincronização SharePoint`
- `docs: melhora passo a passo do template 02`

## 🔐 Checklist de segurança (obrigatório)

- [ ] Nenhum segredo, token ou senha
- [ ] Nenhuma conexão real ou ID de ambiente
- [ ] E-mails/sites/listas fictícios
- [ ] Diagrama e documentação presentes

Toda contribuição é bem-vinda! 🙌
