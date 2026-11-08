# Vinícola Fensterseifer — site

Página única em HTML puro (sem dependências), pronta para o GitHub Pages.

## Estrutura
```
index.html
img/        fotos (tiradas do Instagram @vinicolafensterseifer) e logo HAF
```

## Publicar no GitHub Pages
1. Crie o repositório e envie `index.html` + a pasta `img/` (mantendo os nomes).
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Para domínio próprio: Settings → Pages → Custom domain.

## Trocar fotos
Substitua o arquivo em `img/` mantendo o mesmo nome (ex.: `img/rebo.jpg`). As fotos atuais vieram do Instagram em resolução de tela; quando chegarem os originais da vinícola, é só sobrescrever.

| Arquivo | Onde aparece |
|---|---|
| `hero-vinhedo.jpg` | Capa |
| `vinhedo-familia.jpg`, `vinhedo-maturacao.jpg` | A família |
| `panorama.jpg`, `colheita.jpg`, `cachos-sol.jpg`, `vinhedo-ceu.jpg`, `cachos.jpg`, `adega.jpg` | O vinhedo |
| `gran-reserva.jpg`, `rebo.jpg`, `super-serrano-card.jpg`, `sangiovese.jpg`, `arneis.jpg`, `gewurztraminer.jpg`, `chardonnay.jpg`, `sauvignon-blanc.jpg`, `selecao-de-familia.jpg`, `blanc-de-blancs.jpg`, `dencanto.jpg`, `ouro-verde-do-campo.jpg` | Cards dos vinhos |
| `linha-completa.jpg` | Também na linha |
| `mesa.jpg` | À mesa |
| `ig-*.jpg` | Faixa do Instagram |
| `logo-haf.png` / `logo-haf-escuro.png` | Logo (fundo escuro / fundo claro) |

## Editar rótulos
No `index.html`, procure `var VINHOS = [`. Cada item tem nome, categoria (`tinto`, `branco`, `espumante`, `azeite`), tipo, foto, descrição e harmonização. O número do WhatsApp fica em `var WHATS`.
