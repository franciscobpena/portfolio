# Portfólio — Francisco Pena

Portfólio profissional de Francisco Pena — engenheiro de processos e IA, Black Belt Lean Six Sigma.
Mostra como venho aplicando IA junto com métodos de processo (Lean) pra escalar eficiência em operações reais.

## Stack
Site estático de página única (`index.html`): HTML + CSS inline + JS vanilla. Sem build.
- Fontes: Archivo (display), Inter (corpo), JetBrains Mono (números) via Google Fonts.
- i18n PT/EN via objeto `translations` + atributos `data-key`.
- Identidade dark (paleta LUZ). Fundo do hero gerado no Higgsfield (`images/hero-bg.webp`).
- Botão de voz clonada (click-to-play) no hero: `assets/hero-vo.mp3`.

## Rodar local
```
python -m http.server 8000
# abrir http://localhost:8000
```

## Deploy
Vercel (estático). `vercel.json` define cache imutável pra assets e revalidação pro HTML.
