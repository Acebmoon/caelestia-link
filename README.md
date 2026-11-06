# caelestia-link

Página estática que abre o app **Caelestia Stream** a partir de um link `https://`.

Os apps de conversa (WhatsApp, Telegram) não deixam links `caelestiastream://` clicáveis. Esta página recebe o convite depois do `#`
e redireciona para o app.

## Formato do link

```
https://acebmoon.github.io/caelestia-link/#ip=100.x.x.x&pin=1234&name=NOME-DO-PC&ts=CHAVE
```

- `ip`, `pin`: obrigatórios. `name` e `ts` (chave de entrada da VPN): opcionais.
- Tudo fica depois do `#`: o navegador não envia essa parte ao servidor, então nada do convite passa pelo GitHub.
- A página não guarda dados e não carrega nada de fora.

## Publicar

Settings → Pages → Deploy from a branch → `main` / `(root)`.
