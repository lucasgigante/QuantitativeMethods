# Relatório – Métodos Quantitativos para Análise Multivariada
## Docente: Esteban Fernandez Tuesta

# Introdução
De acordo com Crescenzi e Rodríguez-Pose¹, é notória a heterogeneidade nas condições socioeconômicas em países em desenvolvimento. No Brasil, a gigantesca dimensão geográfica e territorial promove distintas capacidades de fomento do avanço econômico e científico. O entendimento da relação entre os níveis de produção científica e econômica permite a identificação de pontos de melhoria para o cenário brasileiro.

O presente relatório é um requisito para obtenção de nota na disciplina de Métodos Quantitativos para Análise Multivariada, ministrada no quarto semestre do curso de Sistemas de Informação da Escola de Artes, Ciências e Humanidades (EACH-USP). Foi solicitada a elaboração de um trabalho final envolvendo a análise de um conjunto de dados, o qual foi fornecido pelo professor responsável. Essa atividade teve o intuito de consolidar os temas vistos em aula e complementar com uma aplicação sobre dados reais.

A seção da metodologia tratará das validações e operações realizadas sobre os conjuntos de dados fornecidos, acompanhados de trechos de código, quando pertinente. A seção referente às conclusões contemplará os expostos dos resultados mais relevantes ao trabalho, concluindo o relatório.

Cabe ressaltar que apesar da validação de consistência ter sido aplicada de modo idêntico nos programas em R e Python, foi acordado entre o grupo de oferecer diferentes análises em cada linguagem, de modo a utilizar variáveis diferentes e enriquecer o trabalho.

¹CRESCENZI, R.; RODRÍGUEZ-POSE, A. An integrated framework for the comparative analysis of the territorial innovation dynamics of developed and emerging countries. Journal of Economic Surveys, v. 26, n. 3, p. 517-533, 2012.

# Metodologia
A metodologia levou em conta a preparação e manipulação dos conjuntos de dados fornecidos pelo professor responsável, assim como as diretrizes previstas no enunciado dado:

Agrupar os artigos de um pesquisador por instituição ao qual ele está associado. ✅

Juntar todas as informações possíveis (produção científica e atividade econômica). ✅

Extrair a maior quantidade de conclusões possíveis a respeito da interação ou influência da atividade científica sobre a econômica. ✅

Estudar a posição das instituições nas principais localidades, podendo agrupar os dados de acordo com a microrregião/mesorregião (para as atividades econômicas) ou por estado (para as atividades científicas). ✅

Nesse contexto, em linhas gerais, as etapas do trabalho são as seguintes:

Etapa 1: Importação de bibliotecas e validação dos datasets
Etapa 2: Agrupamento de dados
Etapa 3: Verificação de correlações: aplicação de técnicas de análise multivariada

Etapa 4: Conclusões alcançadas

A numeração das etapas diz respeito à subseção correspondente do desenvolvimento, que será discutido a seguir.

Vale comentar novamente que a maior parte das análises são comuns tanto ao relatório feito em R quanto ao de Python. Porém, outras foram feitas unicamente em R ou Python.
