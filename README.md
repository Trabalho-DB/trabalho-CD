# Análise Estatística do Mercado de Aluguel no Rio de Janeiro

## Descrição do Projeto
Este projeto realiza uma análise estatística de dados simulados do mercado de aluguel no Rio de Janeiro, com o objetivo de explorar padrões e tendências em imóveis disponíveis para locação. O estudo utiliza dados mockados contendo informações sobre imóveis, como bairro, tipo de imóvel, número de quartos, banheiros, avaliações, dias disponíveis e preço.

O projeto é implementado em um Jupyter Notebook (`cienciaDeDadosMercadoAluguelRJ.ipynb`) e utiliza bibliotecas Python como Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn e SciPy para análise de dados, visualizações e modelagem estatística.

## Objetivos
- Analisar a distribuição de preços de aluguel por bairro e tipo de imóvel.
- Identificar fatores que influenciam o preço, como número de quartos, banheiros e dias disponíveis.
- Aplicar técnicas estatísticas para explorar correlações e realizar predições.
- Gerar visualizações para facilitar a interpretação dos dados.

## Estrutura do Repositório
- **cienciaDeDadosMercadoAluguelRJ.ipynb**: Jupyter Notebook contendo o código, análises e visualizações.
- **README.md**: Este arquivo, com uma visão geral do projeto.

## Conjunto de Dados
Os dados utilizados são simulados e contêm 500 registros com as seguintes colunas:
- **id**: Identificador único do imóvel.
- **bairro**: Bairro onde o imóvel está localizado (ex.: Copacabana, Ipanema, Leblon, etc.).
- **tipo_imovel**: Tipo de imóvel (Apartamento, Casa, Quarto, Studio).
- **quartos**: Número de quartos.
- **banheiros**: Número de banheiros.
- **avaliacoes**: Número de avaliações do imóvel.
- **dias_disponiveis**: Dias disponíveis para aluguel no ano.
- **preco**: Preço do aluguel por noite (em R$).

## Requisitos
Para executar o notebook, instale as seguintes bibliotecas Python:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Como Executar
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd <NOME_DO_DIRETORIO>
   ```
3. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook cienciaDeDadosMercadoAluguelRJ.ipynb
   ```
4. Execute as células do notebook para realizar a análise.

## Metodologia
- **Pré-processamento**: Limpeza e organização dos dados simulados.
- **Análise Exploratória**: Visualizações (histogramas, boxplots, gráficos de dispersão) para entender a distribuição e relações entre variáveis.
- **Modelagem**: Aplicação de regressão linear para prever preços com base em variáveis como quartos, banheiros e localização.
- **Estatísticas**: Cálculo de métricas como média, mediana, desvio padrão e correlações.

## Resultados Esperados
- Identificação de bairros com preços médios mais altos (ex.: Leblon, Ipanema).
- Correlações entre preço e características como número de quartos e avaliações.
- Visualizações claras para comunicar os resultados.

## Autores
- Giovani Miamoto
- Luciano Júnior
- Victor Geroto
- Rafael Pecorari

## Data
17 de Junho de 2025

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo `LICENSE` para mais detalhes (se aplicável).

## Contato
Para dúvidas ou sugestões, entre em contato com os autores via e-mail ou abra uma *issue* no repositório.
