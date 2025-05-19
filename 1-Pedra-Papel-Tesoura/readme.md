# Visualização Interativa: Jogo Pedra-Papel-Tesoura

Este gráfico 3D interativo mostra os **payoffs esperados do Jogador 2** em um jogo clássico de **Pedra-Papel-Tesoura**, considerando que o Jogador 1 pode adotar estratégias mistas.

## Interpretação

- Os eixos **x** e **y** representam as probabilidades do Jogador 1 jogar **Pedra** e **Papel**, respectivamente.
- A probabilidade de jogar **Tesoura** é automaticamente calculada como `1 - x - y`.
- Cada plano colorido representa o **payoff esperado** do Jogador 2 ao escolher uma das três estratégias puras:
  - **Vermelho**: Jogador 2 escolhe **Pedra**
  - **Verde**: Jogador 2 escolhe **Papel**
  - **Azul**: Jogador 2 escolhe **Tesoura**
- O ponto preto no gráfico marca o **equilíbrio de Nash misto**, onde o Jogador 1 joga cada opção com probabilidade igual a 1/3. Nesse ponto, o Jogador 2 fica indiferente entre suas opções.

## Acesse o gráfico interativo

🔗 [Clique aqui para visualizar o gráfico interativo](https://g-cintra.github.io/Micro-3/payoff_3d_with_equilibrium.html)

## Requisitos

Este gráfico foi gerado com a biblioteca Python `plotly`. Para abrir o arquivo localmente, basta ter um navegador moderno — não é necessário instalar nada.

