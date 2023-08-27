# PipelineETL
Pipeline ETL de dados da Web utilizando Python.

## Recursos

- **Coleta de Dados**: O módulo `WebScraper` extrai o texto de um artigo da web, que é usado como entrada para a análise.

- **Processamento de Texto**: O módulo `TextProcessor` realiza a tokenização e limpeza do texto, removendo palavras irrelevantes, como stopwords e caracteres especiais.

- **Análise de Frequência**: O pipeline calcula a frequência das palavras no texto processado usando a classe `Counter` do Python.

- **Visualização de Dados**: Os resultados da análise são apresentados em um DataFrame do Pandas, exibindo as palavras e suas frequências em ordem decrescente.


## Como Utilizar

1. Instale as dependências necessárias executando o seguinte comando:

```
pip install -r requirements.txt
```

2. Execute as células do notebook para executar o pipeline ETL. As últimas células instanciam a classe `ETLPipeline` e extrai informações de um artigo da web.


3. Os resultados da análise serão exibidos no console, mostrando as palavras mais frequentes no texto do artigo.


## Configuração

- Certifique-se de ter o Python 3.x instalado.

- Personalize as classes `WebScraper` e `TextProcessor` para se adequarem à estrutura dos sites que você deseja extrair e processar.