Aqui iremos traduzir direto da fonte do Software Carpentry e depois inserir em nossa própria página já traduzida. Por enquanto, vamos apenas traduzir os documentos em `.rmd` e depois de finalizada essa tarefa compilar tudo para subir uma página traduzida.

**TL;DR**

1. Pegue seu .rmd
2. Traduza apenas o texto, mantendo a formatação (não mexa no cabeçalho, por enquanto)
3. Não precisa rodar nada, só salvar o .rmd com a sua tradução.
4. Suba o arquivo traduzido
5. Sucesso!

## Como traduzir os .rmd
Pegue o equivalente ao seu capítulo e insira o texto traduzido abaixo da linha

```
source: Rmd
---
``` 

Porém, mantenha a formatação do código para preservar os desafios e os gráficos gerados. Por exemplo, em `08-plot-ggplot2.Rmd` encontramos o seguinte:

    We need to tell `ggplot` how we want to visually represent the data, which we
    do by adding a new **geom** layer. In our example, we used `geom_point`, which
    tells `ggplot` we want to visually represent the relationship between **x** and
    **y** as a scatterplot of points:```

    ```{r lifeExp-vs-gdpPercap-scatter2}
    ggplot(data = gapminder, aes(x = gdpPercap, y = lifeExp)) +
    geom_point()


    > ## Challenge 1
    >
    > Modify the example so that the figure shows how life expectancy has
    > changed over time:


Assim, nosso exemplo seria traduzido da seguinte maneira:

    Precisamos dizer ao `ggplot` como gostaríamos de representar visualmente nossos dados, 
    o qual fazemos adicionando uma nova camada **geom**. Em nosso exemplo, nós utilizamos 
    `geom_point` que diz ao `ggplot` que queremos representar a relação entre 
    **x** e **y** através de um gráfico de dispersão.

    ```{r lifeExp-vs-gdpPercap-scatter2}
    ggplot(data = gapminder, aes(x = gdpPercap, y = lifeExp)) +
    geom_point()


    > ## Desafio 1
    >
    > Modifique o exemplo de forma que a figura mostre como a expectativa de vida
    > mudou ao longo do tempo:



