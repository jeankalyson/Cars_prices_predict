# Cars_prices_predict

Este projeto tem como objetivo uma análise preditiva de preços de carros baseado em dados de um arquivo de treino. Peço compreensão caso os dados não sejam totalmente os esperados, pois estou buscando sempre evolução e esse curso é uma ótima oportunidade para isso.

## Neste repositório, costa os seguintes arquivos :
**LH_CD_JeanKalyson**: arquivo com código de colab, que consta toda a evolução e tratamento de dados, e o relatório dos mesmos.

**requirements**: contém os requisitos e bibliotecas utilizadas no projeto.

**cars_test**: Arquivo csv com os dados de teste para análise.

**cars_train**: Arquivo csv com os dados de treino para análise.

**Todo o passo a passo do projeto está no arquivo Dados_Carros. No decorrer do código, é necessário executar as células de código na
ordem que estão montadas e todas já estão executadas

**Obs:** Caso for executar o projeto novamente, lembre de atualizar o caminho dos arquivos train e test para o caminho do arquivo em seu dispositivo. Ambos os arquivos estão disponiveis para download.

Cars_train = pd.read_csv(**'caminho do arquivo cars_train.csv'**,encoding='latin-1')

Cars_test = pd.read_csv(**'caminho do arquivo cars_test.csv'**,encoding='latin-1')

**TODAS AS REPOSTAS PARA AS SEGUINTES PERGUNTAS FORAM RESPONDIDAS NO DECORRER DO CÓDIGO:**

1. Utilizando as variáveis (features), faça um relatório com uma análise das
principais estatísticas da base de dados. Descreva graficamente essas
variáveis (features), apresentando as suas principais estatísticas descritivas.
Comente o porquê da escolha destas estatísticas e o que elas nos informam..

2. Faça uma EDA. Nesta EDA, crie e responda 3 hipóteses de negócio. Além disso,
responda também às seguintes perguntas de negócio:
a. Qual o melhor estado cadastrado na base de dados para se vender um
carro de marca popular e por quê?
b. Qual o melhor estado para se comprar uma picape com transmissão
automática e por quê?
c. Qual o melhor estado para se comprar carros que ainda estejam dentro
da garantia de fábrica e por quê?

3. Explique como você faria a previsão do preço a partir dos dados. Quais
variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de
problema estamos resolvendo (regressão, classificação)? Qual modelo melhor
se aproxima dos dados e quais seus prós e contras? Qual medida de
performance do modelo foi escolhida e por quê?


**link para o pdf do colab com os arquivos por precaução:** https://drive.google.com/drive/folders/1nTIEYu1Z7Cyq1f-833H658zGfpVV892H?usp=sharing
