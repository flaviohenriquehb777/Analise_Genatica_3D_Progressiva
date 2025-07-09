# Análise Genômica Progressiva em 3D

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este projeto é uma visualização interativa de dados genéticos, utilizando animações 3D para representar a evolução das mutações ao longo do tempo. Desenvolvido para ilustrar a distribuição e o impacto genético de diferentes tipos de mutações em um conjunto de dados simulados, ele oferece uma perspectiva dinâmica sobre a análise genômica.

## 🚀 Demonstração

Veja a animação em ação:

<p align="center">
  <img src="../media/genome_analysis_3d_with_legend.gif" alt="Animação 3D de Análise Genômica" width="500"/>
</p>

## 📝 Descrição do Projeto

O objetivo deste projeto é simular e visualizar dados genéticos em um gráfico 3D interativo, onde as mutações genéticas são exibidas com diferentes impactos ao longo de uma sequência de posições no genoma. A animação mostra a evolução das mutações e seus impactos, permitindo uma visualização dinâmica de hotspots genéticos e variações ao longo do tempo.

Além disso, o projeto inclui a adição de uma legenda detalhada, que permite a fácil identificação de diferentes tipos de mutações durante a animação. A legenda é posicionada fora da área do gráfico para garantir que ela não sobreponha os dados e mantenha a clareza da visualização.

### Funcionalidades

* **Simulação de Dados Genéticos**: Os dados incluem informações sobre a posição no genoma, tipo de mutação (SNP, DEL, INS, CNV), impacto das mutações e o gene afetado, todos gerados de forma simulada para demonstração.
* **Visualização 3D Interativa**: As mutações são representadas em um gráfico 3D, com a posição no genoma no eixo X, o tipo de mutação no eixo Y e o impacto genético no eixo Z, proporcionando uma compreensão espacial dos dados.
* **Animação Progressiva**: As mutações são inseridas progressivamente na animação, com um controle de velocidade que facilita a visualização de como os dados evoluem ao longo do tempo, destacando padrões e tendências.
* **Legenda Dinâmica**: A legenda é exibida fora da área do gráfico e acompanha a animação, mostrando os tipos de mutações e suas respectivas cores, garantindo que o público compreenda rapidamente o que cada ponto representa.
* **Hotspots Genéticos**: Regiões de alta concentração de mutações (hotspots) são visualmente destacadas na animação, proporcionando uma visão clara das áreas de maior impacto genético e relevância biológica.

## 🛠️ Tecnologias Utilizadas

* **Python**: A linguagem de programação principal utilizada para a simulação e criação da animação.
* **Matplotlib**: Usada para gerar gráficos 2D e 3D, e fundamental para a animação dos dados através do pacote `matplotlib.animation.FuncAnimation`.
* **Numpy**: Essencial para a geração eficiente de dados simulados, incluindo a criação de variáveis aleatórias que representam as mutações genéticas.
* **Pandas**: Utilizado para manipulação de dados tabulares, facilitando o armazenamento, organização e filtragem dos dados genéticos gerados.
* **IPython Display**: Usado para exibir a animação diretamente no ambiente Jupyter Notebook, proporcionando uma experiência de desenvolvimento integrada.
* **Pillow**: Biblioteca utilizada para salvar a animação final como um arquivo GIF, permitindo fácil compartilhamento e visualização em diversas plataformas.

## 🚀 Como Executar

Para rodar este projeto em seu ambiente local, siga os passos abaixo:

1.  **Clone o repositório**:

    ```bash
    git clone [https://github.com/SeuNomeDeUsuario/Analise_Genatica_3D_Progressiva.git](https://github.com/SeuNomeDeUsuario/Analise_Genatica_3D_Progressiva.git)
    cd Analise_Genatica_3D_Progressiva
    ```

2.  **Instalar as dependências**:
    Certifique-se de ter as bibliotecas necessárias instaladas. Recomenda-se criar um ambiente virtual.

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3.  **Rodar o Código**:
    O código principal para a geração da animação está no arquivo `Analise_Genatica_3D_Progressiva.ipynb` dentro da pasta `notebooks`. Você pode executá-lo em um ambiente Jupyter Notebook ou Jupyter Lab:

    ```bash
    jupyter notebook notebooks/Analise_Genatica_3D_Progressiva.ipynb
    ```

    Após a execução do notebook, o GIF da animação será salvo na pasta `img/`.

4.  **Personalizar os Dados**:
    A função `generate_genetic_data()` no notebook pode ser modificada para usar seus próprios dados genéticos ou para simular diferentes tipos de variações genéticas e suas consequências, permitindo a adaptação do projeto às suas necessidades.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver ideias para melhorias, novas funcionalidades ou encontrar algum problema, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Contato

Se você tiver alguma dúvida ou sugestão, entre em contato:

* **Nome:** Flávio Henrique Barbosa
* **LinkedIn:** [Flávio Henrique Barbosa | LinkedIn](https://www.linkedin.com/in/fl%C3%A1vio-henrique-barbosa-38465938)
* **Email:** flaviohenriquehb777@outlook.com




