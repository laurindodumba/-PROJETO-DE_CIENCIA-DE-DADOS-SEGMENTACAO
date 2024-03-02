## 1.   PROJETO DE CIÊNCIA DE DADOS 



Nada desanima mais rapidamente após comprar um carro novo do que ver a conta do novo seguro. É ainda mais frustrante quando você sabe que é um bom motorista. Parece injusto pagar tanto quando se é cuidadoso ao dirigir por anos. A Porto Seguro, uma das maiores seguradoras de automóveis e residências do Brasil, concorda plenamente. Imprecisões nas previsões de sinistros de seguradoras elevam o custo para bons motoristas e diminuem para os ruins. Nesta competição, o desafio é construir um modelo que preveja a probabilidade de um motorista fazer um sinistro de seguro auto no próximo ano. Embora a Porto Seguro use aprendizado de máquina há 20 anos, eles buscam novos métodos através da comunidade de aprendizado de máquina do Kaggle. Uma previsão mais precisa permitirá ajustar melhor seus preços, tornando o seguro automotivo mais acessível a mais motoristas.

### **Avaliação do Modelo (Sugerido pelo Cliente)**
Métrica de Pontuação
As submissões são avaliadas usando o **Coeficiente Gini Normalizado**.

O Coeficiente Gini Normalizado ajusta a pontuação pelo máximo teórico, de modo que a pontuação máxima é 1.

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

![image](https://github.com/laurindodumba/-PROJETO-DE_CIENCIA-DE-DADOS-SEGMENTACAO/assets/38964642/53ca7273-dbdc-4fcc-8e18-1de0cf02dede)



* [Descrição do Projeto](#descrição-do-projeto)

# 1) Entendimento do problema de Negócio
   Construir um **modelo que preveja a probabilidade de um motorista fazer um sinistro de seguro auto no próximo ano**

**"Sinistro"** é um termo usado no setor de seguros para se referir a um evento em que o segurado sofre um prejuízo coberto pela sua apólice e, consequentemente, faz uma reclamação ou solicitação de indenização à seguradora. No contexto de seguro auto, um sinistro pode envolver situações como:

1. Acidentes de trânsito (colisões, capotagens, etc.);
2. Roubo ou furto do veículo;
3. Danos causados por fenômenos naturais (enchentes, granizo, etc.);
4. Danos causados por terceiros (vandalismo, por exemplo);
5. Entre outros.

Após a ocorrência de um sinistro, o segurado deve entrar em contato com a seguradora para informar o ocorrido e iniciar o processo de avaliação e eventual indenização, conforme estabelecido na apólice de seguro.   

* [Status do Projeto](#status-do-Projeto)

# 2) Entendimento dos Dados

Para este projeto utilizaremos os dados disponibilizados pela seguradora Porto Seguro no ambiente Kaggle:

https://www.kaggle.com/competitions/porto-seguro-safe-driver-prediction/data

Nos dados de treino e teste:
- variáveis que pertencem a agrupamentos similares são marcadas como tal nos nomes das variáveis (por exemplo, ind, reg, car, calc).

- Os nomes das variáveis incluem o sufixo "bin" para indicar variáveis binárias e "cat" para indicar varipaveis categóricas. Variáveis sem essas designações são contínuas ou ordinais.


- Valores de -1 indicam nulo.

- A coluna "target" indica se uma reclamação (sinistro) foi feita ou não para aquele titular da apólice.

O arquivo train.csv contém os dados de treino, onde cada linha corresponde a um titular de apólice, e a coluna "target" indica que uma reclamação foi feita.
O arquivo test.csv contém os dados de teste.


* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)

# Preparação dos Dados

- Gerar Metadados da ABT (Tabela Analítica de Modelagem)
- Tratamento de missing (nulos)
- Tratamento de categóricas de alta cardinalidade (LabelEncoder)
- Tratamento de categóricas de baixa cardinalidade (OneHotEncoder)
- Aplicar normalização a toda tabela de modelagem (ABT)
- Gerar artefatos para implantação do data prep realizado


- `Funcionalidade 1`: descrição da funcionalidade 1
- `Funcionalidade 2`: descrição da funcionalidade 2
- `Funcionalidade 2a`: descrição da funcionalidade 2a relacionada à funcionalidade 2
- `Funcionalidade 3`: descrição da funcionalidade 3




* [Tecnologias utilizadas](#tecnologias-utilizadas)
- Python



# Autor:
Nome: Laurindo Dumba
