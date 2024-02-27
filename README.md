# Cara ou coroa?

## Distribuição de Bernoulli

A distribuição de Bernoulli é um modelo fundamental na teoria da probabilidade e estatística, pois descreve o resultado de um único experimento binário. Esta distribuição é frequentemente usada para modelar experimentos com apenas dois possíveis resultados, como o lançamento de uma moeda ou a resposta a uma pergunta sim/não.

Por exemplo, quando lançamos uma moeda justa, a probabilidade de obter "cara" (sucesso) é $$p = 0.5$$, e a probabilidade de obter "coroa" (fracasso) é $$1 - p = 0.5$$. Usamos a notação $$X \sim Ber(p)$$ para indicar que uma variável aleatória $$X$$ segue uma distribuição de Bernoulli com parâmetro $$p$$.

## Simulação de Lançamentos de Moeda

Podemos simular lançamentos de moeda usando a distribuição de Bernoulli com a biblioteca `scipy.stats` do Python. Em particular, mostramos como gerar uma série de resultados de lançamentos de moeda e como encontrar a maior sequência de "cara" ou "coroa" nessa série.

Para garantir que os resultados da simulação sejam replicáveis, discutimos a importância de definir uma semente para o gerador de números aleatórios. Isso pode ser feito usando a função `np.random.seed` da biblioteca `numpy`.

## Viés de Seleção

O viés de seleção ocorre quando os resultados de um experimento ou estudo são distorcidos devido à maneira como os dados são coletados ou selecionados. No exemplo que você deu, o locutor no estádio só pediu para as pessoas que obtiveram dez "caras" em dez lançamentos para se manifestarem. Isso pode dar a impressão de que obter dez "caras" é um evento comum, quando na verdade é bastante raro.

No entanto, se continuarmos a fazer perguntas diferentes ou a aplicar diferentes modelos aos dados, eventualmente encontraremos algo que parece interessante puramente por acaso. É por isso que é tão importante entender os conceitos de probabilidade e estatística ao interpretar os resultados de um experimento ou estudo.

