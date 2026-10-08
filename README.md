# Nicolas Schulze · Portfolio

Site estático publicado no GitHub Pages. Esta pasta contém **apenas a versão pública**.

## Duas versões

| Versão | Onde fica | Quem vê |
|---|---|---|
| **Edição / pré-visualização** | Artifact privado no Claude (com rascunhos, pendências e o botão "Visão pública") | Só você |
| **Pública** | Este repositório → `nicschulze123-sudo.github.io` | Recrutadores e clientes |

Rascunhos e pendências nunca entram neste repositório. A versão pública é gerada a partir da versão de edição por um script que remove tudo o que é privado.

## Segurança aplicada

- Content-Security-Policy restritiva: só roda o JavaScript do próprio site (por hash), sem scripts, formulários ou conexões externas.
- Fontes hospedadas no próprio site (nenhuma requisição ao Google; o visitante não é rastreado).
- Sem cookies, sem formulários, sem coleta de dados.
- Links externos com `noopener noreferrer`.
- Referrer policy `strict-origin-when-cross-origin`.

## Recomendado no GitHub (uma vez)

1. Settings → Pages → marque **Enforce HTTPS**.
2. Ative a verificação em duas etapas (2FA) na sua conta do GitHub.
3. Settings → Code security → deixe ativo o **Secret scanning** e o **Push protection**.

## Atualizar

1. Peça a atualização ao Claude (ela é feita primeiro na versão de edição).
2. Confira no botão "Visão pública".
3. GitHub Desktop → Commit to main → Push origin.
