# Web-musicAI

Jednoduchá statická stránka pro poslech a stažení hudby vytvořené pomocí ElevenMusic.

## Obsah

- responzivní single-page web bez frameworku a externích závislostí
- HTML5 audio přehrávač
- přímé stažení WAV
- GitHub Pages deployment přes GitHub Actions

## Audio

Stránka očekává soubor:

\`\`\`
tracks/
└── 30let-svatby-a-je-to/
    └── 30letSvatbyAJeTo.wav
\`\`\`

Každá další skladba má vlastní adresář v \`tracks/\`.

## GitHub Pages

Workflow je v `.github/workflows/pages.yml`.

Při prvním nasazení je potřeba v GitHubu nastavit:

**Settings → Pages → Build and deployment → Source → GitHub Actions**

Potom se stránka nasazuje automaticky při pushi do `main`.
