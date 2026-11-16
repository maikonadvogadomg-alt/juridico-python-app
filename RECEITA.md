# 🧬 Receita para recriar: Assistente IA Jurídico

_Gerada sem IA, lendo 26 arquivo(s). Serve para remontar este app como HTML modular — com qualquer IA, um arquivo por vez._

## 1. O que é

- **Nome:** Assistente IA Jurídico
- **Partes de código:** 13 (3 tela, 9 logica, 0 servidor, 0 dados, 1 estilo)
- **Tem servidor (rotas /api):** não — dá para ser só HTML
- **Peças de fora (bibliotecas):** ${t}

## 2. Estrutura modular proposta

```
index.html            ← a página; chama os módulos NA ORDEM
css/app.css           ← o visual
js/00-core.js         ← a "locomotiva": cria window.APP (registrar, guardar, avisar)
js/10-abrir.js        ← -*- coding: utf-8 -*- (era abrir.py)
js/15-commonjs-dynamic-modules-tdtrd.js← logica (era www/assets/_commonjs-dynamic-modules-TDtrdbi3.js)
js/20-vendor-i2kalhuy.js← logica (era www/assets/vendor-I2kAlhUy.js)
js/25-index-btye5xlg.js← logica (era www/assets/index-Btye5XlG.js)
js/30-mammoth-browser-bpa7y1is.js← logica (era www/assets/mammoth.browser-BPa7Y1iS.js)
js/35-pdf-gh-brlfn.js ← logica (era www/assets/pdf-gh-BrLFn.js)
js/40-ui-bfodmm-g.js  ← logica (era www/assets/ui-BFodMM-g.js)
js/45-tiptap-drvc6u7f.js← logica (era www/assets/tiptap-DRvc6u7f.js)
js/50-conserto-ia.js  ← logica (era www/conserto-ia.js)
js/55-index-btbp-g6q.js← tela (era www/assets/index-BTbp-g6q.js)
js/60-auditoria.js    ← Colador de Links — 🔗 Colador de Links (era www/auditoria.html)
js/65-www.js          ← Assistente IA Jurídico (era www/index.html)
js/99-app.js          ← o último: monta a tela com o que embarcou
```

## 3. As partes, uma por uma

| # | Era | Vira | Tipo | O que faz | Usa |
|---|---|---|---|---|---|
| 1 | `abrir.py` | `js/10-abrir.js` | logica | -*- coding: utf-8 -*- | — |
| 2 | `www/assets/_commonjs-dynamic-modules-TDtrdbi3.js` | `js/15-commonjs-dynamic-modules-tdtrd.js` | logica | — | — |
| 3 | `www/assets/vendor-I2kAlhUy.js` | `js/20-vendor-i2kalhuy.js` | logica | which | — |
| 4 | `www/assets/index-Btye5XlG.js` | `js/25-index-btye5xlg.js` | logica | — | vendor-I2kAlhUy.js, _commonjs-dynamic-modules-TDtrdbi3.js |
| 5 | `www/assets/mammoth.browser-BPa7Y1iS.js` | `js/30-mammoth-browser-bpa7y1is.js` | logica | — | vendor-I2kAlhUy.js, _commonjs-dynamic-modules-TDtrdbi3.js |
| 6 | `www/assets/pdf-gh-BrLFn.js` | `js/35-pdf-gh-brlfn.js` | logica | — | — |
| 7 | `www/assets/ui-BFodMM-g.js` | `js/40-ui-bfodmm-g.js` | logica | — | vendor-I2kAlhUy.js |
| 8 | `www/assets/tiptap-DRvc6u7f.js` | `js/45-tiptap-drvc6u7f.js` | logica | — | vendor-I2kAlhUy.js, ui-BFodMM-g.js |
| 9 | `www/conserto-ia.js` | `js/50-conserto-ia.js` | logica | lsTxt, escolherChave, linha, responder | — |
| 10 | `www/assets/index-BTbp-g6q.js` | `js/55-index-btbp-g6q.js` | tela | — | ui-BFodMM-g.js, vendor-I2kAlhUy.js, tiptap-DRvc6u7f.js, pdf-gh-BrLFn.js |
| 11 | `www/auditoria.html` | `js/60-auditoria.js` | tela | Colador de Links — 🔗 Colador de Links | manifest.json |
| 12 | `www/assets/index-B-XLeRRI.css` | css/app.css | estilo | — | — |
| 13 | `www/index.html` | `js/65-www.js` | tela | Assistente IA Jurídico | manifest.webmanifest, icon-192.png, icon.svg, app-unico.js |

## 4. Montar passo a passo (cada bloco é um pedido pronto: 📋 Copiar → colar na IA)

### Passo 0 — combinar as regras com a IA

```text
Vamos recriar o app "Assistente IA Jurídico" como HTML MODULAR, que abre pelo index.html, sem servidor e sem nada da Replit.
Regras: (1) index.html chama os arquivos js/ na ordem, antes do </body>; (2) js/00-core.js cria window.APP com APP.registrar(modulo), APP.guardar(chave, valor) em IndexedDB/localStorage e APP.avisar(texto); (3) cada arquivo js/NN-nome.js cuida de UM assunto, começa com (function (APP) { e termina com })(window.APP); (4) js/99-app.js vem por último e monta a tela com os módulos registrados; (5) textos em português do Brasil.
Vou pedir UM arquivo por vez. Responda só com o arquivo completo, sem cortar nada. Primeiro: crie index.html, css/app.css e js/00-core.js.
```

### Passo 1 — `js/10-abrir.js` (era `abrir.py`, 113 linhas)

```text
Crie js/10-abrir.js. Ele faz: -*- coding: utf-8 -*-.
No app original ele tinha estas funções/partes: Pagina, __init__, send_head, end_headers, log_message, ja_ligado, abrir_janela, main.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 2 — `js/15-commonjs-dynamic-modules-tdtrd.js` (era `www/assets/_commonjs-dynamic-modules-TDtrdbi3.js`, 2 linhas)

```text
Crie js/15-commonjs-dynamic-modules-tdtrd.js. Ele é uma parte de logica do app.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 3 — `js/20-vendor-i2kalhuy.js` (era `www/assets/vendor-I2kAlhUy.js`, 2 linhas)

```text
Crie js/20-vendor-i2kalhuy.js. Ele é uma parte de logica do app.
No app original ele tinha estas funções/partes: which.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 4 — `js/25-index-btye5xlg.js` (era `www/assets/index-Btye5XlG.js`, 222 linhas)

```text
Crie js/25-index-btye5xlg.js. Ele é uma parte de logica do app.
Ele usa o que já foi criado em: js/20-vendor-i2kalhuy.js, js/15-commonjs-dynamic-modules-tdtrd.js (pelo APP).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 5 — `js/30-mammoth-browser-bpa7y1is.js` (era `www/assets/mammoth.browser-BPa7Y1iS.js`, 221 linhas)

```text
Crie js/30-mammoth-browser-bpa7y1is.js. Ele é uma parte de logica do app.
Ele usa o que já foi criado em: js/20-vendor-i2kalhuy.js, js/15-commonjs-dynamic-modules-tdtrd.js (pelo APP).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 6 — `js/35-pdf-gh-brlfn.js` (era `www/assets/pdf-gh-BrLFn.js`, 13 linhas)

```text
Crie js/35-pdf-gh-brlfn.js. Ele é uma parte de logica do app.
O original usava as bibliotecas ${t}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 7 — `js/40-ui-bfodmm-g.js` (era `www/assets/ui-BFodMM-g.js`, 53 linhas)

```text
Crie js/40-ui-bfodmm-g.js. Ele é uma parte de logica do app.
Ele usa o que já foi criado em: js/20-vendor-i2kalhuy.js (pelo APP).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 8 — `js/45-tiptap-drvc6u7f.js` (era `www/assets/tiptap-DRvc6u7f.js`, 142 linhas)

```text
Crie js/45-tiptap-drvc6u7f.js. Ele é uma parte de logica do app.
Ele usa o que já foi criado em: js/20-vendor-i2kalhuy.js, js/40-ui-bfodmm-g.js (pelo APP).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 9 — `js/50-conserto-ia.js` (era `www/conserto-ia.js`, 192 linhas)

```text
Crie js/50-conserto-ia.js. Ele é uma parte de logica do app.
No app original ele tinha estas funções/partes: lsTxt, escolherChave, linha, responder, manda, esforco, ementas, historico, processar, refinar, chatLivre.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 10 — `js/55-index-btbp-g6q.js` (era `www/assets/index-BTbp-g6q.js`, 727 linhas)

```text
Crie js/55-index-btbp-g6q.js. Ele é uma parte de tela do app.
Ele usa o que já foi criado em: js/40-ui-bfodmm-g.js, js/20-vendor-i2kalhuy.js, js/45-tiptap-drvc6u7f.js, js/35-pdf-gh-brlfn.js, js/30-mammoth-browser-bpa7y1is.js, js/25-index-btye5xlg.js (pelo APP).
Ele chamava estes endereços: https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${s.gemini_api_key}, https://api.openai.com/v1/chat/completions, https://api.perplexity.ai/chat/completions, ${s.demo_api_url}/chat/completions, /api/code/run, /api/tts, /api/voice-chat, /api/doc-templates/upload-docx, /api/export/word-with-template, /api/jurisprudencia/buscar, /api/code-assistant, /api/upload/transcribe, /api/ai/process, /api/ai/refine, /api/upload/extract-text, /api/git-push, ${d}/chat/completions, /api/jwt/status, /api/jwt/generate, /api/datajud/consulta. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 11 — `js/60-auditoria.js` (era `www/auditoria.html`, 797 linhas)

```text
Crie js/60-auditoria.js. Ele faz: Colador de Links — 🔗 Colador de Links.
No app original ele tinha estas funções/partes: uid, ler, gravar, nomeLista, nomeDe, pintar, fixar, tirar, mover, recarregar, pintarJanela, iniciar, montar, salvar, daLista, contar, pintarListas, caixaDe.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 12 — `js/65-www.js` (era `www/index.html`, 35 linhas)

```text
Crie js/65-www.js. Ele faz: Assistente IA Jurídico.
Ele usa o que já foi criado em: js/50-conserto-ia.js (pelo APP).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 13 — `js/99-app.js` e conferir

```text
Crie js/99-app.js: ele olha APP.modulos e monta o menu/abas com um botão para cada módulo. Depois, me mande o index.html atualizado com todos os <script src="js/…"> na ordem certa: js/00-core.js, js/10-abrir.js, js/15-commonjs-dynamic-modules-tdtrd.js, js/20-vendor-i2kalhuy.js, js/25-index-btye5xlg.js, js/30-mammoth-browser-bpa7y1is.js, js/35-pdf-gh-brlfn.js, js/40-ui-bfodmm-g.js, js/45-tiptap-drvc6u7f.js, js/50-conserto-ia.js, js/55-index-btbp-g6q.js, js/60-auditoria.js, js/65-www.js, js/99-app.js.
```

## 5. Conferir no final

- [ ] Abrir o index.html na prévia: aparece a tela sem erro (▤ console vazio)?
- [ ] Cada botão abre a sua parte?
- [ ] Fechar e abrir de novo: os dados continuam?
- [ ] Nada com "replit", "REPL_", "@workspace" no código (🏗️ Preparar confere).
- [ ] 📱 PWA → deixar instalável; 📦 APK ou 🖥️ .exe.
