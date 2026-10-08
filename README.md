# Mobile Navigation UI

**[Live demo](https://navegacao-coeyou9mc-santoszois-projects.vercel.app)**

Exercício de UX/UI para uma barra de navegação inferior em dispositivos móveis.

## Interações

- quatro destinos principais;
- estado ativo durante a interação;
- rótulos sempre visíveis;
- feedback visual e conteúdo contextual;
- foco de teclado;
- adaptação para viewport mobile e safe area.

## Rodando localmente

```bash
git clone https://github.com/Santoszoi/navegacao.git
cd navegacao
python -m http.server 8000
```

Abra `http://localhost:8000`.

## Decisões de UX/UI

A navegação limita o número de destinos, mantém texto junto aos ícones e usa `aria-current` para comunicar a seção ativa. O exercício prioriza previsibilidade e clareza em vez de animações decorativas.

HTML, CSS e JavaScript sem frameworks.
