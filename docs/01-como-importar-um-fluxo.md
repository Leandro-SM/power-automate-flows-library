# Como importar um fluxo

Este guia explica como reaproveitar os templates deste acervo no seu próprio ambiente do **Power Automate**.

> ⚠️ Os arquivos `.json` deste repositório são **descrições estruturadas genéricas** (didáticas), não exports oficiais. Use-os como **planta** para reconstruir o fluxo.

## Opção A — Reconstruir manualmente (recomendado para aprendizado)

1. Abra o [Power Automate](https://make.powerautomate.com).
2. Crie um novo fluxo do tipo indicado no README do template (automatizado, agendado ou instantâneo).
3. Siga o **passo a passo** descrito no README do template, adicionando cada ação na ordem.
4. Configure os **parâmetros** (listas, pastas, destinatários) conforme sua realidade.
5. Ajuste as **conexões** (SharePoint, Outlook, etc.) com suas próprias credenciais.

## Opção B — Importar um pacote de solução (.zip)

Caso você exporte seus próprios fluxos como solução:

1. No Power Automate, vá em **Soluções → Importar**.
2. Selecione o arquivo `.zip` da solução.
3. Mapeie as **conexões** solicitadas para as suas.
4. Conclua a importação e **ative** o fluxo.

## Checklist pós-importação

- [ ] Conexões remapeadas para o **seu** ambiente
- [ ] Parâmetros ajustados (nomes de listas, pastas, e-mails)
- [ ] Fluxo **testado** com um caso real
- [ ] Nenhum dado sensível deixado nos campos de exemplo

## Dica de segurança

Nunca versione ou compartilhe fluxos contendo **conexões reais, tokens ou dados corporativos**. Sempre generalize antes de publicar.
