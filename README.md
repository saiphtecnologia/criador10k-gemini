# Criador 10K · Máquina de Conteúdo para Gemini

Habilidade editorial para criar, estruturar, adaptar e revisar copies de carrosséis para Instagram com o método Criador 10K.

## O que faz

A Habilidade conduz briefing, headlines, espinha dorsal, copy por slide, fechamento e revisão editorial.

A montagem visual, imagens e identidade final permanecem na Máquina de Conteúdo:

https://maquina.criador10k.com.br

## Instalação no Gemini

1. Acesse https://gemini.google.com no computador.
2. Abra **Configurações → Habilidades**.
3. Clique em **Criar → Fazer upload**.
4. Selecione **arquivos** na janela de envio.
5. Selecione o arquivo `criador10k-gemini-skill.zip`.
6. Revise a habilidade.
7. Clique em **Criar** (ou **Salvar habilidade**, conforme a interface).

O ZIP contém um `SKILL.md` na pasta principal, conforme o formato oficial de upload do Gemini.

Use o arquivo de `dist/` ou da release, sem extraí-lo. O ZIP automático **Code → Download ZIP** do GitHub inclui arquivos do repositório e não é o pacote de instalação. A disponibilidade de Habilidades varia conforme a conta.

Para empacotar com Python, a partir da raiz do repositório:

```sh
python -m zipfile -c dist/criador10k-gemini-skill.zip SKILL.md references
```

## Exemplos

- "Quero transformar um conteúdo existente em carrossel."
- "Tenho um insight e quero criar uma narrativa."
- "Revise esta copy com o método Criador 10K."

## Estrutura

```text
SKILL.md
references/
  01-metodo-editorial.md
  02-modelos-e-densidade.md
  03-qualidade-e-revisao.md
```

## Privacidade

A Habilidade não possui MCP, API externa, autenticação própria, tracking ou coleta de dados.

Mantido pela Saiph Tecnologia para o Criador 10K.
