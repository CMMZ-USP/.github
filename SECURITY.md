# Segurança

## Relatar um problema de segurança

Se você encontrar credenciais expostas, uma vulnerabilidade em scripts ou
qualquer informação sensível da infraestrutura do CMMZ em um repositório,
**não abra uma issue pública**. Escreva para [PREENCHER e-mail] descrevendo o
que encontrou e onde.

## Práticas adotadas

- *Secret scanning* e *push protection* ativados em toda a organização.
- Documentação de infraestrutura mantida em repositório privado.
- Hook `gitleaks` via `pre-commit` nos repositórios de código e infraestrutura.
- Credenciais vazadas são revogadas e trocadas, não apenas apagadas do histórico.
