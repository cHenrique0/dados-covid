# Dados Covid-19

Dados da covid-19 no brasil, utilizado para uma atividade da disciplina de **Análise de Sistemas Lineares** do curso de **[Engenharia da Computação](http://www.ecp.ufma.br/)** 
na **[UFMA](https://portalpadrao.ufma.br/site)**. 

A atividade consiste em analisar os dado do dataset e implementar uma função média móvel que recebe como entrada um vetor de dados e um número K, sendo K a quantidade de itens para
calcular a média. A função deve retornar um vetor onde cada elemento representa a média da série, isto é, a soma do valor atual e dos K-1 termos, sendo essa soma dividida por K. 
Validar a função para dados de COVID-19. Obter os dados públicos de morte do estado do Maranhão e calcular a média dos 7 últimos dias (incluindo o atual) e dos 14 últimos dias. 
Baseado no critério da imprensa, variação entre esses 7 e 14 dias, informar se a pandemia no estado está em alta (>15%), baixa (<-15%) ou estabilidade. 
Adicionalmente, mostrar o gráfico dos dados (brutos) de mortalidade conjuntamente com o da média móvel por dia.
