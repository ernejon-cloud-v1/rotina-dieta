# Controle de Dieta e Treinos

Arquivos:
- `index.html`: aplicativo mobile.
- `Dieta.xlsx`: fonte dos dados.

## Publicar no GitHub Pages
1. Envie `index.html` e `Dieta.xlsx` para a raiz do mesmo repositório.
2. No GitHub, abra **Settings > Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch (normalmente `main`) e a pasta `/ (root)`.
5. Abra a URL gerada pelo GitHub Pages no Android.

## Atualizar a rotina
Edite `Dieta.xlsx`, mantendo a aba `Dieta` e as colunas:
`Dia`, `Horário`, `Refeição`, `Comida simples`.

Depois faça commit/push do novo `Dieta.xlsx`.
O HTML lê o arquivo a cada abertura/recarregamento.

## Observação
Os checks ficam salvos no `localStorage` do navegador e são separados por semana.
Ao começar uma nova semana, os novos checks começam vazios.
