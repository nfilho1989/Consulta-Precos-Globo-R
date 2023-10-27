# Consulta-Precos-Globo-R
Script R para consultar preços de programação da Globo via API, com objetivo de integrar os dados com o Salesforce. Instruções no README.

# Descrição Detalhada:
Este repositório contém um script R que permite a consulta de preços de programação da Globo por meio da API da TV Globo. O script é projetado para extrair informações de preços de programas com base em critérios de data, abrangência e secundagem. Além disso, o projeto inclui a integração de dados de audiência dos programas, obtidos de uma planilha no Google Sheets. O objetivo é automatizar a obtenção de dados de preços e audiência da programação da Globo.

# Configuração:
1 - Clone o repositório em seu ambiente R.
2 - Certifique-se de ter as bibliotecas R necessárias instaladas, como httr, jsonlite, dplyr, urltools, RODBC, lubridate, googlesheets4 e tidyverse.
3 - Defina o URL da API, credenciais de usuário e senha na seção apropriada do script.
4 - Atualize os parâmetros de consulta, como datas, abrangência e secundagem, conforme necessário.

# Como Usar:
1 - Execute o script R para iniciar as consultas de preços.
2 - Os resultados são consolidados em um dataframe chamado df_resultado, que inclui informações de programa, abrangência, secundagem, exibição e preços.
3 - Os dados de audiência dos programas são integrados ao dataframe df_resultado a partir de uma planilha no Google Sheets.
4 - Os resultados são formatados e podem ser usados para análises posteriores.

# Outras Informações Relevantes:

Este projeto é útil para profissionais que precisam acessar informações de preços e audiência da programação da Globo de maneira automatizada.
Certifique-se de manter o repositório atualizado à medida que você fizer melhorias ou correções no código.
Para informações detalhadas sobre os dados de audiência da programação, consulte a planilha no Google Sheets fornecida.
