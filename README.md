# Farm Optimizer — Static

Versão 100% estática para GitHub Pages.

- HTML + CSS + JavaScript
- Sem login
- Sem banco
- Sem backend
- Sem API
- Sem cookies/localStorage
- Todos os cálculos acontecem no navegador

## Publicar no GitHub Pages

Envie `index.html`, `style.css`, `app.js` e `favicon.svg` para um repositório e ative GitHub Pages.

## Atualizar sagas

Os dados atuais ficam no começo de `app.js`, na constante `DATA`.

Para adicionar novas sagas, desafios ou DLCs, adicione um objeto seguindo o mesmo formato.

Os cálculos atuais consideram:
- Sagas: cooldown de 30 min e uso das horas de farm.
- Desafios: 1 execução por dia.
- DLC Bardock: cooldown de 8h, limitado pelo campo "Bardock por dia" (máx. 3).
- Booster 200/300/400% multiplicam o resultado final do respectivo recurso.
- Rank, VIP e Clã são somados ao 100% base.
- Prestígio 0 = x1, Prestígio 1 = x2 etc.
