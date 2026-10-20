# Definição do problema

Para construir uma definição sólida e bem fundamentada, este trabalho se pauta em quatro critérios:

1. **Público-alvo:** quem é a pessoa ou grupo afetado pelo problema?
2. **Dificuldade concreta:** qual é o obstáculo ou dor específica enfrentada?
3. **Relevância:** por que essa dificuldade é importante e exige uma solução?
4. **Enquadramento temático:** em que área do conhecimento o problema e sua solução se inserem?

## (i) Público-alvo

O problema afeta os microcomerciantes: pessoas que produzem e vendem por conta própria, em pequena escala. Nesse grupo estão vendedores ambulantes de doces e pequenos alimentos, artesãos e quem fabrica itens em casa para vender em marketplaces, como eBay, Mercado Livre e Shopee. Em geral, atuam sem apoio técnico, muitas vezes na informalidade, e acumulam ao mesmo tempo os papéis de produtor, vendedor e gestor do próprio negócio.

## (ii) Dificuldade concreta

A principal dificuldade é definir o preço de venda. Na prática, o preço costuma ser fixado de forma intuitiva: copiando concorrentes, somando uma margem arbitrária ao custo ou aplicando descontos sem previsão de resultado. O vendedor não consegue estimar como uma mudança no preço altera a quantidade vendida e, por consequência, o lucro final. Isso fica ainda mais difícil quando entram o custo de produção e as taxas cobradas, seja a comissão da plataforma, seja a taxa da maquininha de cartão.

## (iii) Relevância

Para o microcomerciante, a margem de lucro é pequena e o resultado das vendas impacta diretamente a renda familiar. Um erro de precificação tem efeitos concretos. Um desconto pode aumentar as vendas e, ainda assim, reduzir o lucro. Um preço baixo demais faz o vendedor trabalhar mais para ganhar menos. Um preço alto demais afasta clientes. Como esse público raramente pode "testar no próprio bolso" sem prejuízo, uma ferramenta simples, capaz de prever esses efeitos antes da decisão, tem valor prático imediato.

## (iv) Enquadramento temático

O problema se insere na área de Administração, mais especificamente em precificação e gestão de pequenos negócios, com fundamentos de Economia ligados à relação entre preço e demanda. Do ponto de vista matemático, a demanda será modelada por uma função exponencial, e a função logarítmica será usada para estimar os parâmetros do modelo a partir de dados reais de venda e para calcular variações de preço necessárias para atingir metas.

## Pergunta central

> **Dado o custo do produto, as taxas envolvidas e o histórico de vendas, qual preço maximiza o lucro do microcomerciante, e qual o impacto de um desconto ou aumento sobre as vendas e o lucro?**

## Hipóteses simplificadoras

Para que o problema possa ser tratado por um modelo matemático simples e acessível, adotamos algumas hipóteses simplificadoras. Consideramos que a quantidade vendida depende apenas do preço praticado. Por isso, o modelo não contempla:

- picos e quedas de demanda causados por sazonalidade ou datas comemorativas, como Natal, Dia das Mães e Black Friday;
- reações da concorrência, como um concorrente que reduz o preço em resposta;
- efeitos de divulgação, anúncios pagos ou avaliações de clientes;
- variações no custo unitário de produção conforme o volume produzido.

Apesar dessas simplificações, o modelo foi pensado para ser extensível. Com novos recursos computacionais e ferramentas matemáticas e estatísticas mais robustas, ele poderá ser aperfeiçoado para incorporar fatores hoje desconsiderados, como a sazonalidade e a concorrência, aproximando-se cada vez mais da realidade do microcomerciante.