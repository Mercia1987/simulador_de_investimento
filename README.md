# simulador_de_investimento

##Sobre a planilha

Esta planilha ajuda a calcular e simular quanto um investimento mensal pode acumular ao longo do tempo e sugere como dividir o aporte entre tipos de Fundos de Investimento Imobiliário (FIIs), conforme o perfil escolhido.

## 1. O que a ferramenta responde e onde encontrar as respostas

Na aba Planilha1:

*Qual é o salário informado? — na célula D12.
*Qual é o rendimento mensal estimado da carteira? — na célula D13.
*Quanto seria 30% do salário como sugestão de investimento? — na célula D14.
*Quanto investir por mês e por quantos anos? — preencha as células D17 e D18.
*Qual taxa mensal será usada na simulação? —  célula D19.
*Quanto o investimento pode acumular ao final do período? — resultado em D20.
*Quanto esse patrimônio poderia gerar de dividendos mensais, usando o rendimento configurado? — resultado em D21.
*Quanto poderia acumular em 2, 5, 10, 20 e 30 anos? — tabela *Cenários* valores na coluna C.
*Qual é a divisão sugerida do aporte por tipo de FII para cada perfil?  — escolha o perfil em C31. A coluna C mostra o percentual sugerido; a coluna D mostra o valor estimado em reais para cada tipo. D41 mostra a soma dos valores distribuídos.

Para usar a planilha, altere as células de entrada conforme necessário. Evite apagar as células com fórmulas, pois elas calculam os resultados automaticamente.

## 2. Como VF e PROCV entram nos cálculos

- VF (Valor Futuro) calcula uma estimativa de quanto os aportes mensais podem acumular ao longo do tempo, considerando a taxa mensal e o número de meses. Na planilha, é usada para o patrimônio em D20 e para os cenários de 2, 5, 10, 20 e 30 anos na coluna C.
- PROCV procura na aba *Planilha2* o percentual associado à combinação de *perfil + tipo de FII*. A fórmula monta uma chave e a procura na tabela. O percentual encontrado aparece na coluna C da distribuição.
- Depois, a planilha multiplica o percentual sugerido pelo valor mensal a investir para calcular o valor em reais de cada tipo de FII na coluna D.
- O dividendo mensal estimado é calculado multiplicando o patrimônio pelo rendimento da carteira configurado em D13.

## 3. Intervalos nomeados

A planilha contém estes nomes definidos, que tornam as fórmulas mais fáceis de entender.

## 4. Percentuais por perfil e origem

Os percentuais estão cadastrados na aba *Planilha2*, nas colunas *Perfil*, *tipo de FII* e *%*. 



