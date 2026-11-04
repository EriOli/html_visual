# Visuais personalizados para Power BI em HTML

Este repositório reúne gráficos e elementos visuais personalizados feitos com HTML e CSS para uso em relatórios do Power BI. A proposta é servir como uma coleção de referências e componentes que podem ser adaptados para criar apresentações de dados com mais controle sobre layout e estilo.

## Conteúdo

- [`Sales_by_time.htm`](./Sales_by_time.htm): exemplo de gráfico de vendas ao longo do tempo, com comparação entre a semana atual e a anterior. O visual inclui valores de destaque, linhas de tendência, área preenchida e detalhes exibidos ao passar o mouse sobre os dias.
- [`summary_page_quarter.htm`](./summary_page_quarter.htm): página de resumo trimestral por área, com foco no forecast do Q3 2025. Apresenta uma narrativa visual para destacar o impacto de cada área nos resultados.
- [`four_cards_with_hover.htm`](./four_cards_with_hover.htm): painel de forecast com quatro cartões de indicadores. Ao passar o mouse sobre um cartão, ele vira e exibe informações complementares, como variação, confiança e tendências.
- [`card_revenue.htm`](./card_revenue.htm): cartão de KPI de receita que mostra o valor, a variação percentual e a comparação com o mês anterior.

## Como usar

Os arquivos são trechos HTML/CSS e não necessariamente páginas HTML completas. Para utilizá-los, copie o conteúdo do visual para uma solução ou visual do Power BI que aceite a renderização de HTML. A compatibilidade e os recursos disponíveis — como CSS, SVG e interações ao passar o mouse — dependem do visual utilizado e das configurações de segurança do ambiente.

## Personalização

O exemplo atual contém valores, rótulos, datas e estilos definidos diretamente no HTML. Edite esses elementos para adequá-los ao relatório. Para que o visual reflita os dados do modelo automaticamente, será necessário integrar o HTML a uma solução que faça essa vinculação; o arquivo atual, por si só, é estático.
