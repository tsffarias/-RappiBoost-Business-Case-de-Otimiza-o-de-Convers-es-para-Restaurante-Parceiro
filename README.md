### 🚀 **RappiBoost: Business Case de Otimização de Conversões para Restaurante Parceiro**

**Visão Geral**: *RappiBoost* é um business case desenvolvido para melhorar a eficiência e as conversões dos restaurantes parceiros na plataforma Rappi. Utilizando técnicas avançadas de análise de dados e BI, o projeto visa identificar pontos de ruptura no funil de conversão e propor estratégias práticas para aumentar a taxa de conversão e a satisfação dos usuários.

## **Objetivo** 🎯

O objetivo principal deste business case é otimizar o desempenho dos restaurantes parceiros da Rappi, e buscar aumentar a taxa de conversão das etapas críticas do funil, desde a visualização de produtos até a confirmação de pedidos.

## **Arquivos** 📂

O projeto consiste em diversos arquivos de dados que detalham sessões, conversões e outras métricas relevantes (arquivos se encontram na pasta data/):

1. **visao_geral_restaurantes_sessoes.csv**: Dados semanais sobre sessões e atividades dos usuários nos restaurantes.
2. **visao_geral_restaurantes_conversoes.csv**: Taxas de conversão semanais para os restaurantes.
3. **visao_carteira_sessoes.csv**: Dados de sessões específicos para a carteira de restaurantes.
4. **visao_carteira_conversoes.csv**: Taxas de conversão específicas para a carteira de restaurantes.
5. **sessoes_conversao_usuarios1.csv**: Dados de sessões e conversões para um grupo específico de usuários.
6. **sessoes_conversao_usuarios2.csv**: Dados de sessões e conversões para outro grupo específico de usuários.
7. **leia_me.csv**: Explicações sobre as colunas e perguntas a serem respondidas no business case.

## **Análises Realizadas** 🔍

### Comportamento dos Usuários
Análise comparativa do comportamento dos dois grupos de usuários para identificar padrões e oportunidades de melhoria.

### Funil de Conversão
Identificação de pontos de ruptura no funil de conversão, com destaque para as etapas que apresentam maiores quedas nas taxas de conversão.

### Propostas de Melhoria
Propostas específicas para melhorar a performance da carteira de restaurantes, baseadas nos insights obtidos a partir da visão geral dos restaurantes.

## **Perguntas a serem Respondidas** ❓

1. **Quais conclusões é possível chegar sobre o funil de conversões da carteira?**
   - A conversão média (SST-OPC) da carteira é de 17% e da vertical restaurantes é de 26%. Ou seja, há uma possibilidade de melhoria de até 9% da conversão mensal.
   - Há possibilidades de crescimento nas etapas:
     - "Proceder ao Checkout (PTC)" e "Pedido Solitidado (OP)" de até 17%.
     - "Pedido Solitidado (OP)" e "Pedidos Confirmados (OPC)" de até 10%.
     - "Visualizações de Produto (VPD)" e "Adições ao Carrinho (ATC)" de até 9%.

2. **Existe algum insight do funil de conversão com as input metrics?**
   - A disponibilidade de lojas na carteira de restaurantes é consistentemente alta (98%) ao longo das semanas analisadas, e acima da média da vertical restaurante. Isso indica que as lojas da carteira estão geralmente disponíveis e prontas para atender pedidos, o que pode ser uma vantagem competitiva.
   - A disponibilidade de produtos na carteira de restaurantes varia entre 82% e 91% ao longo das semanas analisadas. Isso indica que há certa variabilidade.
   - A média de "% Desconto da carteira" é 5% e da "% Vertical Restaurantes" é de 11%. Podemos aumentar a taxa de desconto para a média da vertical de restaurante para atrair novos clientes.

3. **O que você faria como proposta para crescer o funil de conversões como um todo da carteira?**
   - Realizar uma análise detalhada das causas raiz para a variabilidade na disponibilidade de produtos da carteira. Isso pode ajudar a melhorar a eficiência operacional e a satisfação do cliente (menores cancelamentos e por consequência maior conversão).
   - Em "Visualizações de Produto (VPD)", podemos melhorar as imagens de produtos e descrição dos produtos, e também pode ser feito testes A/B com diferentes imagens mais atrativas para atrair clientes a adicionar ao carrinho.
   - Analisar os pontos positivos do Usuário 1, como nas etapas de "Proceder ao Checkout (PTC)", "Pedidos Selecionados (OP)" e "pedidos confirmados (OPC)", e aplicar no Usuário 2 para aumentar a conversão e satisfação do cliente.
   - Implementar campanhas de incentivos ou descontos específicos para aumentar as adições ao carrinho e os checkouts (criar campanhas durante os jogos do brasil cada gol é mais 1% de desconto, ou campanhas de festas e feriados da região da carteira. (Usando Segmentação de Clientes com ‘Análise RFM’)
   - % Desconto da carteira é 5% e da % Vertical Restaurantes é de 11%. Podemos aumentar o desconto para atrair novos clientes.

4. **Qual seria o seu approach com o parceiro e qual proposta você faria para aumentar as conversões?**
   - Baseado nas métricas, fornecer feedback detalhado e estratégias personalizadas para cada parceiro com foco nas áreas identificadas como pontos fracos.

## **Resultados**

### Sessões
A análise revelou que a visão geral dos restaurantes apresenta valores mais altos para quase todas as métricas de sessões em comparação com a carteira de restaurantes.

### Conversões
As taxas de conversão da visão geral são superiores em várias etapas do funil, especialmente nas etapas de conversão de pedidos, indicando áreas de melhoria para a carteira.

## **Próximos Passos**

1. **Análise Detalhada dos Pontos de Ruptura**: Realizar uma análise mais profunda para identificar as causas dos pontos de ruptura no funil de conversão.
2. **Implementação de Ações Específicas**: Propor e implementar ações específicas para melhorar as métricas de sessões e conversões da carteira.
3. **Monitoramento e Ajuste Contínuo**: Monitorar continuamente as métricas e ajustar as estratégias conforme necessário para garantir a melhoria contínua.

## **Conclusão**

**RappiBoost** é um projeto crucial para elevar a performance dos restaurantes parceiros na Rappi, utilizando insights baseados em dados para tomar decisões informadas e estratégias eficazes. Com a implementação das ações propostas, espera-se um aumento significativo nas taxas de conversão e na satisfação dos usuários.

## **Links de Apoio**

1. [Dados de Apoio](https://docs.google.com/spreadsheets/d/1gZoP44Q62UbFiHnHPL6byc5TWf44KzryL2HMga908P0/edit?usp=sharing): Google sheets com dados do business case.
2. [Slides Apresentação](https://docs.google.com/presentation/d/1Z--ywI3AZ_yKAVrI41jiqOylvIslSqVvHxiEzjpYIkM/edit?usp=sharing): Slides contendo os insights extraídos da base de dados de apoio.

## **Código e Dados**

As análises detalhadas realizadas neste projeto estão contidas no notebook [./business_case_rappi.ipynb](./business_case_rappi.ipynb), que se encontra na raiz do repositório. Todos os arquivos de dados mencionados estão organizados na pasta `data/`.