# Como contribuir com os repositórios do CMMZ-USP

Obrigado por contribuir! Estas regras valem para todos os repositórios da
organização que não tenham um `CONTRIBUTING.md` próprio.

## Fluxo de trabalho

1. **Não faça commits diretamente na `main`.** Crie um branch com nome
   descritivo: `protocolo/extracao-pinos-secos`, `fix/script-trimming`.
2. Faça commits pequenos, com mensagens claras no imperativo:
   "Adiciona etapa de lavagem com EDTA", "Corrige caminho do genoma de referência".
3. Abra um **pull request** usando o modelo e peça revisão de alguém do team
   responsável.
4. Após aprovação, o PR é integrado por quem revisou.

## Ao criar um repositório novo

- Use **sempre** o modelo [template-cmmz](https://github.com/CMMZ-USP/template-cmmz)
  (botão *Use this template*).
- Preencha README, `CITATION.cff`, `codemeta.json` e `.zenodo.json`.
- Aplique os topics: tema (`museomics`, `protocolos`, `bioinformatics`…) e
  **todos os financiamentos envolvidos** (ex.: `fapesp-2022-11560-6`). Veja
  [FINANCIAMENTO.md](FINANCIAMENTO.md).

## Versões e DOIs

Protocolos e pipelines estáveis devem ganhar uma *release* com versionamento
semântico (`v1.0.0`). Com a integração Zenodo ativa, cada release recebe um
DOI citável. Registre a mudança no `CHANGELOG.md`.

## Nunca envie para o GitHub

- Senhas, tokens, chaves SSH ou de API, certificados.
- Endereços IP internos, nomes de máquinas, mapas de rede, nomes de usuários
  dos servidores.
- Dados pessoais de terceiros.
- Arquivos de sequenciamento brutos (FASTQ, BAM) — eles vão para o storage e
  para repositórios públicos de dados (SRA/ENA), não para o Git.

Se algo sensível for enviado por engano, **avise imediatamente** quem
administra a organização: apagar o arquivo em um commit novo não basta, a
credencial precisa ser trocada.

## Idioma

Documentação em português; README com resumo em inglês quando o material
tiver interesse internacional. Código e comentários podem ser em inglês.
