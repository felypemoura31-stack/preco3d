# Preço 3D

App web (PWA) para calcular o preço de peças impressas em 3D. Funciona no celular, tablet e PC, instala na tela inicial e roda offline.

## Como calcula

- **Material** = gramas usadas × (preço do rolo ÷ peso do rolo)
- **Energia** = (watts ÷ 1000) × horas × preço do kWh
- **Desgaste da máquina** e **mão de obra** = valor por hora × tempo
- **Margem de falhas** (%) sobre material + energia
- **Lucro** (%) sobre o custo total
- **Taxa/imposto** (%) descontada do preço final

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `preco3d`) e envie estes arquivos para a branch `main`.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em ~1 minuto o app estará em `https://SEU-USUARIO.github.io/preco3d/`.

## Instalar no celular

- **Android (Chrome):** menu ⋮ → *Instalar app*.
- **iPhone (Safari):** Compartilhar → *Adicionar à Tela de Início*.

## Dados

Ficam salvos no navegador de cada aparelho (localStorage). Use **Config → Exportar/Importar** para levar os dados para outro dispositivo.
