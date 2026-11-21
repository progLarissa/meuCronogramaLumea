# meuCronogramaLumea

Cronograma interativo de depilação com a **Philips Lumea IPL 8000 (BRI948/00)**, seguindo a recomendação da Philips:

- **Fase inicial:** 4 sessões, uma a cada 2 semanas (margem de 3 dias antes ou depois).
- **Manutenção:** 1 sessão a cada 4 semanas, 8 vezes.
- **Depois:** retoques quando os pelos voltarem (a cada 4–8 semanas).

Áreas: pernas, coxas, braços, barriga (acessório Corpo), axilas, virilha (Biquíni), buço e queixo (Rosto).

## Como abrir

Acesse **https://proglarissa.github.io/meuCronogramaLumea/** no celular. Para usar como app, use "Adicionar à tela de início" no menu do navegador.

## Arquivos

- `index.html` — o app (HTML, CSS e JavaScript num arquivo só).
- `dados.json` — histórico inicial. Ele é carregado só na primeira vez em cada aparelho. Depois disso, o que você registra fica salvo no navegador daquele aparelho.

## Passar o histórico entre aparelhos

Na aba **Como funciona → Seus dados**: use **Copiar backup** num aparelho e **Restaurar backup** no outro. Para atualizar o histórico inicial do repositório, cole o texto do backup no `dados.json`.
