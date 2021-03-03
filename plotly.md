# Instalação

Instalar via CRAN.

    install.packages("plotly")

# Demonstração de Uso

    library(plotly)
    fig <- plot_ly(
      x = c("Ciências Humanas", "Ciências Exatas", "Ciências Biológicas"),
      y = c(50, 30, 15),
      name = "Alunos do IFPE por área de ensino",
      type = "bar"
    )
    fig

<img src="newplot.png" class="screenshot" width=800 />

# Uso da função plot\_ly()

Fornece uma interface mais direta para o plotly original criado em
javascript e com isso, podemos usufruir de tipos de gráficos mais
elaborados e melhor renderizados. (EX: coordenadas paralelas, mapas,
superfícies e malhas)
