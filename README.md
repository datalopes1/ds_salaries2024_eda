
# 💽EDA - Data Science Salaries 2024

Neste projeto será realizado o processo de EDA (Exploratory Data Analysis) a partir do dataset Data Science Salaries 2024, que pode ser encontrado no [Kaggle](https://www.kaggle.com/datasets/sazidthe1/data-science-salaries/data), com licensa [Database: Open Database](https://opendatacommons.org/licenses/dbcl/1-0/) e enviado por [Sazidul Islam](https://www.kaggle.com/sazidthe1). 

### 🛠️ Ferramentas utilizadas
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## 1.1. Os dados, o problema e os objetivos
Como pessoa em transição de carreira é muito importante ter noção do novo ambiente corporativo que me aguarda, do que vou enfrentar no começo, e onde posso chegar encarando essa jornada. Outro passo importante é entender os próximos passos após chegar ao meu primeiro emprego na área de dados, onde vou virar meu foco de estudos, entrei nesta jornada após ouvir muito sobre Data Science e Machine Learninig mas ao iniciar meus estudos e correr atrás de entender esse universo vi que existem várias outras posições. Este conjunto de dados abrange uma grande coleção de dados sobre salários na área de Data Science, no período de tempo entre 2020 e 2024, os dados incluem vários aspectos relacionados a salário, proporcionando uma visão multifacetada da carreira. 

Os dados foram coletados do [ai-jobs.net](https://ai-jobs.net/).

### Estrutura do dataset

| Coluna | Descrição|
|--------|----------|
| **job_title** | O título da vaga ou posição associada ao salário registrado. |
| **experience_level** | Nível de experiência da pessoa que ocupa a vaga. |
| **employment_type** | Indica o regime de trabalho, se a vaga é integral, meio-período, etc. |
| **work_models** | Indica se o modelo de trabalho é presencial, híbrido ou remoto.|
| **work_year** | Específica o ano de trabalho. |
| **employee_residence** | O local onde o trabalhador reside. |
| **salary** | O salário registrado para vaga. |
| **salary_currency** | A moeda em que o salário foi registrado. |
| **salary_in_usd** | Salário em doláres. |
| **company_location** | Localização da empresa contratante. |
| **company_size** | Tamanho da empresa contratante. |

### Objetivos
Então meus objetivos com essa Análise Exploratória de Dado são:

- Buscar conhecer mais posições dentro da área, e como são remuneradas;
- Entender se empresas maiores valorizam mais os profissionais de dados;
- Compreender se os layoffs estão afetando a evolução dos salários ao longo do tempo;
- Onde estão localizadas as companhias que mais contratam;

## 1.2. Importação das bibliotecas e carregamento dos dados
A bibliotecas utilizadas foram o pandas, numpy, datetime, os, matplotlib, seaborn, plotly e warnings.

# 🧱2. Entendendo os dados 
##  2.1. Estrutura do dataframe
Aqui busquei através do métodos shape, head(), tail(), e info() para entender a estrutura dos dados. 
## 2.2. Breves conclusões antes de partir para os próximos passos

- O dataframe parece limpo e bem cuidado, possivelmente não terá nulos e duplicatas;
- Existem muitas posições dentro da área de Data Science, muitas funções de engenharia e outras um pouco vagas enquanto ao propósito;
- Vejo a necessidade de criar uma coluna de especialidade ou expertise, para ter melhor entendimento na análise;
- Alguns preenchimentos de employee_residence contém estados dos EUA, será necessário mudar para a localidade do país;

# 🧹3. Limpeza e manipulação dos dados
## 3.1. Verificação de nulos e duplicados
Verificação através dos métodos isna() e duplicated(). 
## 3.2. Manipulação dos dados e colunas
Foram feitos os processos de consertar preenchimentos e criar a coluna 'expertise'

# 4. EDA ou Análise Exploratória de dados


# 5. Conclusões
![Imagem1](https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?q=80&w=2072&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
Planejar e tomar decisões sempre medindo todos os passos para o processo ter o rendimento mais eficaz e eficiente foi a base da minha formação academica, como Engenheiro de Produção, buscar formas, maneiras e ferramentas para melhorar os processos sempre me interessaram. Ao progredir para supervisor de vendas durante minha carreira como corretor de imóveis, analisar o desempenho dos colegas e dos produtos na incorporadora estimularam ainda mais minha mente a um pensamento guiado por dados. Em 2022 quando tive a oportunidade de poder retomar e concluir minha graduação após a pandemia de COVID-19, a área de dados parecia como uma escolha cristalina do meu próximo passo de transição para uma nova carreira. Saber onde estou pisando ainda sim é importante, e ver que a progressão de carreira tem amplas opções de caminhos para seguir é muito animador.

### Alguns insights

- O site que serviu de base para os dados é norte-americano que também é onde estão sediadas maioria das grandes empresas de tecnologia, então naturalmente maioria das vagas vão estar localizadas neste país mas existe uma grande diversidade de localizações para trabalhar de forma remota, como diversos países europeus o que é interessante. A Índia é outro páis que emprega muitos profissionais e tem uma tradição de formar excelentes programadores.
- O trabalho remoto ainda tem uma quantidade significante de vagas ofertadas, e com tantas empresas sediadas nos Estados Unidos e Europa ter fluência em inglês é um grande diferencial para carreira.
- Apesar da pandemia e dos layoffs os salários continuam crescendo, muito por conta das posições que tratam de AI, existe uma tendência de queda próxima a uma estabilização dos salários dos analistas, a partir da observação deste conjunto de dados.
- A grande diferença entre as ofertas de vagas Senior, Mid e Entry-level indica a necessidade de entrada de mais profissionais no mercado ao longo do tempo e do avanço de carreira dos profissionais alocados.
- Empresas de porte médio são onde se encontram maioria das vagas e melhores salários, isso é uma surpresa para mim. Mas um sinal de onde devo procurar aplicar por vagas.
- Vagas de engenharia e arquitetura de dados remuneram bem e são áreas que devo buscar entender um pouco melhor, e são boas opções para me especializar no futuro.