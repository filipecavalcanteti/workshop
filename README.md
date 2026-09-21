# Workshop — Técnicas de OSINT na Prática

Site estático com os slides e as aulas em vídeo do workshop, publicado no GitHub Pages.

Site: https://filipecavalcanteti.github.io/workshop/

## Estrutura

- `index.html` — página com o player das aulas e o link dos slides
- `assets/style.css` — estilos
- `*.mp4` — aulas em vídeo
- `*.pdf` — slides
- `.github/workflows/pages.yml` — deploy automático a cada push na `main`

## Publicação

Em **Settings → Pages**, defina **Source: GitHub Actions**. Depois disso, cada push na `main` publica o site.

Para rodar localmente:

```bash
python3 -m http.server 8000
```
