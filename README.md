# Projeto 1  
### Data source
* Pasta onde extraímos os dados da API.
* O programa "get_raw_matches.ipynb" extraí os dados da API e guarda os guarda em um JSON.
* O programa "matches_useful_data_filter.ipynb" remove colunas com dados muitos ausentes da API ou colunas com dados irrelevantes.
* O programa "data_treatment.ipynb" faz a tratativa dos dados.

### Scrapper 
* Extraí os dados da página da Wiki.

### Data_tests.ipynb
* Testes de hipoteses com os dados.

# Projeto 2  
### Data source
* Cumpre as mesmas funções que no projeto 1, porém fizemos algumas pequenas alterações.
    * Mudamos a quantidade de consultas a API, então pegamos mais dados.
    * Limpamos os dados do dataset, deixando apenas dados relevantes para a predição.  

## input_dataset_generator
* Usa os dados extraídos no Scrapper para trocar o nome de cada civilização, por algo que a represente, no caso o seu poderio militar e econômico.
* A ultima etapa do pré-projeto.

## main
* Arquivo onde executamos e explicamos todos os passos do projeto.