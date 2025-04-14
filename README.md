# Análise Genômica Progressiva em 3D

Este projeto é uma visualização interativa de dados genéticos, utilizando animações 3D para representar a evolução das mutações ao longo do tempo. Ele foi desenvolvido para ilustrar a distribuição e o impacto genético de diferentes tipos de mutações em um conjunto de dados simulados.

## Descrição do Projeto

O objetivo deste projeto é simular e visualizar dados genéticos em um gráfico 3D interativo, onde as mutações genéticas são exibidas com diferentes impactos ao longo de uma sequência de posições no genoma. A animação mostra a evolução das mutações e seus impactos, permitindo uma visualização dinâmica de hotspots genéticos e variações ao longo do tempo.

Além disso, o projeto inclui a adição de uma legenda detalhada, que permite a fácil identificação de diferentes tipos de mutações durante a animação. A legenda é posicionada fora da área do gráfico para garantir que ela não sobreponha os dados.

### Funcionalidades

- **Simulação de Dados Genéticos**: Os dados incluem informações sobre a posição no genoma, tipo de mutação (SNP, DEL, INS, CNV), impacto das mutações e o gene afetado.
- **Visualização 3D**: As mutações são representadas em um gráfico 3D, com a posição no genoma no eixo X, o tipo de mutação no eixo Y e o impacto genético no eixo Z.
- **Animação Progressiva**: As mutações são inseridas progressivamente na animação, com um controle de velocidade que facilita a visualização de como os dados evoluem ao longo do tempo.
- **Legenda Interativa**: A legenda é exibida fora da área do gráfico e acompanha a animação, mostrando os tipos de mutações e suas respectivas cores.
- **Hotspots Genéticos**: As regiões de alta concentração de mutações (hotspots) são destacadas na animação, proporcionando uma visão clara das áreas de maior impacto genético.

## Tecnologias Utilizadas

- **Python**: A linguagem principal utilizada para a simulação e criação da animação.
- **Matplotlib**: Usada para gerar gráficos 2D e 3D, além de animar os dados. O pacote `matplotlib.animation.FuncAnimation` foi utilizado para criar a animação progressiva.
- **Numpy**: Utilizado para a geração de dados simulados, incluindo a criação de variáveis aleatórias para representar as mutações genéticas.
- **Pandas**: Utilizado para manipulação de dados tabulares, facilitando o armazenamento e a filtragem dos dados gerados.
- **IPython Display**: Usado para exibir a animação no Jupyter Notebook.
- **GIFs**: A animação final é salva como um arquivo GIF utilizando a biblioteca `Pillow`, permitindo fácil compartilhamento e visualização.

## Como Executar

1. **Instalar as dependências**: Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las usando o `pip`:
    ```bash
    pip install numpy matplotlib pandas pillow
    ```

2. **Rodar o Código**: O código pode ser executado em um ambiente Jupyter Notebook ou Jupyter Lab. Execute o script de animação para gerar e visualizar o gráfico 3D interativo com as mutações genéticas.

3. **Personalizar os Dados**: A função `generate_genetic_data()` pode ser modificada para usar seus próprios dados genéticos, simulando diferentes tipos de variações genéticas e suas consequências.


## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
