 🚧 * EM CONSTRUÇÃO * 🚧


# Dashboard comercial em Power BI
Este é um modelo de dashboard criado em Power BI, voltado para análises e decisões comerciais. Foram utilizados dados de uma empresa fictícia para se demonstrar o passo a passo de toda a criação, passando pelo carregamento e limpeza dos dados, realização de todos os cálculos e o desenvolvimento dos painéis.

### 1. Carregamento e Transformação dos dados no Power BI
O primeiro passo foi carregar todos os arquivos .csv e realizar sua transformação através do Power Query. Para a normalização dos arquivos, foram necessários ajustes, que incluem:  
. Adequação dos nomes dos arquivos e algumas colunas  
. Adequação do **tipo de dado** nas colunas, especialmente números, strings e calendário  
. Transformação (criação) de colunas para constar dados específicos  
. Tratamento das células *nulls* e em branco  
. Criação dos parâmetros de datas  


*IMAGEM*

### 2. Criação do *Modelo* e as Relações
Foi utilizado o esquema *Snowflake*. Todas as tabelas de dimensões possuíam uma relação 1:* (one to many) para com as tabelas de fatos (vendas e devoluções)

*IMAGEM*
 
### 3. Criação de *Medidas* com a linguagem DAX
A fim de realizar a agragação dos principais dados usados no painel, tais como totais, contagens e outros indicadores, foram utilizadas a criação de *medidas*. Dentre elas, incluem-se:  
- Totais de vendas, devoluções, lucro, custos  
- Relações
- Médias de faturamento  
- Séries temporais (janelas)

Todas as medidas foram conferidas através de suas inserções em matrizes.


*imagem*

### 4. Montagem do Dashboard
Após todas as transformações e cálculos, foram originados 4 paines, que interagem entre si, com os seguintes propósitos, mas não a eles limitados:  


### 5. Dashboard Finalizado
#### Screenshots

![image](https://github.com/user-attachments/assets/c35666cb-488d-439d-8606-0d1806045c35)
![image](https://github.com/user-attachments/assets/0bb83554-7c7a-4a2c-b310-fcb8174f0498)
![image](https://github.com/user-attachments/assets/707b0005-a160-48fb-9188-8ef5cbfb7ef0)
![image](https://github.com/user-attachments/assets/7d6b52ef-999c-4334-86f3-d4fb858c54f6)
