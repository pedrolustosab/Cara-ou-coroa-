# Cara ou coroa?

<img src="CaraCoroa.jpg" width=500>

## Distribuição de Bernoulli

A distribuição de Bernoulli é um modelo fundamental na teoria da probabilidade e estatística, pois descreve o resultado de um único experimento binário. Esta distribuição é frequentemente usada para modelar experimentos com apenas dois possíveis resultados, como o lançamento de uma moeda ou a resposta a uma pergunta sim/não.

Por exemplo, quando lançamos uma moeda justa, a probabilidade de obter "cara" (sucesso) é $$p = 0.5$$, e a probabilidade de obter "coroa" (fracasso) é $$1 - p = 0.5$$. Usamos a notação $$X \sim Ber(p)$$ para indicar que uma variável aleatória $$X$$ segue uma distribuição de Bernoulli com parâmetro $$p$$.

## Simulação de Lançamentos de Moeda

Podemos simular lançamentos de moeda usando a distribuição de Bernoulli com a biblioteca `scipy.stats` do Python. Em particular, mostramos como gerar uma série de resultados de lançamentos de moeda e como encontrar a maior sequência de "cara" ou "coroa" nessa série.

Para garantir que os resultados da simulação sejam replicáveis, discutimos a importância de definir uma semente para o gerador de números aleatórios. Isso pode ser feito usando a função `np.random.seed` da biblioteca `numpy`.

## Viés de Seleção

O viés de seleção ocorre quando os resultados de um experimento ou estudo são distorcidos devido à maneira como os dados são coletados ou selecionados. No exemplo que você deu, o locutor no estádio só pediu para as pessoas que obtiveram dez "caras" em dez lançamentos para se manifestarem. Isso pode dar a impressão de que obter dez "caras" é um evento comum, quando na verdade é bastante raro.

No entanto, se continuarmos a fazer perguntas diferentes ou a aplicar diferentes modelos aos dados, eventualmente encontraremos algo que parece interessante puramente por acaso. É por isso que é tão importante entender os conceitos de probabilidade e estatística ao interpretar os resultados de um experimento ou estudo.

## Aprofundando os Tópicos

### **Probabilidade**
A probabilidade é uma medida quantitativa da incerteza associada a um evento. Ela é expressa como um número entre 0 e 1, onde 0 indica que o evento certamente não ocorrerá e 1 indica que o evento certamente ocorrerá. A probabilidade é usada para quantificar a incerteza associada a eventos em um universo conhecido, o espaço amostral. 

### **Variável Qualitativa Nominal**
As variáveis qualitativas nominais são usadas para categorizar ou rotular. Elas não têm uma ordem ou hierarquia inerente. Por exemplo, a cor dos olhos (azul, verde, castanho) é uma variável qualitativa nominal. Não faz sentido dizer que "azul" é maior que "verde". Em análises estatísticas, essas variáveis são frequentemente codificadas como variáveis dummy, que são variáveis binárias indicando a presença ou ausência de uma categoria.

### **Variável Aleatória**
Uma variável aleatória pode ser pensada como uma função que associa um número real a cada resultado em um espaço amostral. Ela é chamada de "aleatória" porque seu valor é determinado pelo resultado de um experimento aleatório. Existem dois tipos de variáveis aleatórias: discretas e contínuas. As variáveis aleatórias discretas têm um número contável de possíveis valores. As variáveis aleatórias contínuas podem assumir qualquer valor em um intervalo contínuo.

### **Variável Aleatória de Bernoulli**
A variável aleatória de Bernoulli é uma variável aleatória discreta que toma o valor 1 com probabilidade $p$ e o valor 0 com probabilidade $1-p$. Ela é usada para modelar experimentos com exatamente dois possíveis resultados. Por exemplo, em um lançamento de moeda, podemos definir "cara" como sucesso (X=1) e "coroa" como fracasso (X=0).

### **Viés de Seleção e Viés de Amostragem**
O viés de seleção e o viés de amostragem são dois tipos de erros sistemáticos que podem distorcer os resultados de um estudo. O viés de seleção ocorre quando a maneira como os participantes são selecionados para um estudo cria uma amostra que não é representativa da população. O viés de amostragem ocorre quando a amostra coletada para um estudo não é representativa da população total.
