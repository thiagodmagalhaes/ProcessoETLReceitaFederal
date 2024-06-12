# ETL - Análise de Dados da Receita Federal

Este repositório contém um script Python para realizar o processo de Extração, Transformação e Carga (ETL) de dados da Receita Federal do Brasil. O objetivo é automatizar o tratamento e enriquecimento desses dados para posterior análise e tomada de decisões estratégicas.

## Pré-requisitos
- Python instalado no ambiente.
- Bibliotecas necessárias instaladas (requests, pyspark).

## Como executar o código
1. Clone ou baixe este repositório para o seu computador `git clone https://github.com/thiagodmagalhaes/ProcessoETLReceitaFederal.git`
2. Abra o arquivo `ANÁLISE_DE_DADOS_RECEITA_FEDERAL_COMTRATAMENTOS.ipynb` em seu ambiente de desenvolvimento Python.
3. Defina o caminho para o diretório de destino `(destination_directory)` onde os arquivos serão salvos após a extração e transformação. Isso é feito na seção de definição de variáveis no início do código.
4. Execute o script Python.
5. Aguarde o término do processo de ETL. O progresso do processo será exibido no console.
6. Verifique o diretório de destino definido para os arquivos tratados e enriquecidos.

## Organização do código
- O código está organizado em seções que correspondem às etapas do processo de ETL: Extração, Transformação e Carga.
- Cada seção é responsável por uma parte específica do processo, como download de arquivos, leitura e tratamento dos dados.
- Comentários no código fornecem explicações sobre o que cada parte do código está fazendo.

## Atenção
- Certifique-se de ter uma conexão de internet estável durante a execução do código, pois ele faz download de arquivos da Receita Federal.
- Verifique se o diretório de destino definido possui permissões de escrita.
- Caso ocorram erros durante a execução, verifique as mensagens de erro e siga as instruções fornecidas para solucioná-los.
