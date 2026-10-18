# ml-callback

Página estática usada como **Redirect URI** do OAuth do Mercado Livre. Ela só lê `?code=...&state=...` da URL e mostra o código para você copiar. Não envia, salva nem registra nada.

Redirect URI cadastrada: `https://felipe-qa.github.io/ml-callback/` (a string deve ser **idêntica** em todos os lugares, inclusive a barra final).

## Publicar (grátis, GitHub Pages)
1. No GitHub, crie um repositório **público** chamado `ml-callback` (conta `Felipe-QA`).
2. Envie só o arquivo `index.html` desta pasta (botão *Add file → Upload files*, ou `git`).
3. Em *Settings → Pages*: *Deploy from a branch*, branch `main`, pasta `/ (root)` → *Save*.
4. Em ~1 minuto abra `https://felipe-qa.github.io/ml-callback/`. Deve aparecer "Nenhum código recebido…".

## Segurança
- O código de autorização é de uso único e de vida curta; só é trocável por quem tem o **client secret** (que fica apenas no seu computador).
- Não coloque App ID, secret nem tokens neste repositório (ele é público).
