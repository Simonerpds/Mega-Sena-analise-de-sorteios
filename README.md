Análise dos Sorteios da Mega Sena

Este projeto realiza uma análise exploratória dos sorteios da Mega Sena, utilizando Python e a biblioteca Pandas. O objetivo é identificar padrões, estatísticas e curiosidades nos números sorteados ao longo do tempo.

O conjunto de dados utilizado contém 2988 concursos, com informações sobre os números sorteados, vencedores e valores de prêmios.

Funcionalidades

O projeto inclui as seguintes análises:

Números mais frequentes:
Calcula quais números saíram mais vezes em todos os concursos.
Exemplo de resultado: 10, 53, 37, 5, 34, 33.
Números menos frequentes:
Lista os números que apareceram menos vezes.
Exemplo de resultado: 26, 21, 55, 22, 15, 31, 48, 3, 12, 7.
Distribuição pares x ímpares:
Conta quantos números pares e ímpares já foram sorteados.
Exemplo de resultado: Pares: 9003, Ímpares: 8925.
Espaçamento entre números consecutivos:
Calcula a diferença entre os números sorteados de um concurso para o outro.
Analisa padrões e frequências de espaçamento.
Padrões de espaçamento repetidos:
Identifica sequências de diferenças entre concursos que se repetem.
Útil para análise de padrões raros ou curiosos.
Número que mais saiu por posição:
Analisa qual número apareceu com mais frequência em cada posição (Bola1, Bola2, …, Bola6).
Números que nunca foram sorteados:
Verifica se existem números que nunca saíram em nenhum sorteio.
Resultado atual: todos os números de 1 a 60 já foram sorteados pelo menos uma vez.
Média dos números sorteados:
Calcula a média dos números de cada sorteio e a média geral de todos os concursos.
Resultado: Média geral dos números sorteados: 30.53.

Tecnologias Utilizadas

Python 3
Pandas para manipulação e análise de dados
Excel como fonte dos dados (Mega-Sena.xlsx)

Estrutura do Projeto

Mega-Sena/
│
├─ Mega-Sena.xlsx          # Arquivo com os dados dos concursos
├─ mega_sena_analysis.py   # Script com todas as análises
└─ README.md               # Documentação do projeto

Conclusão

Este projeto oferece uma visão estatística e detalhada dos resultados da Mega Sena, permitindo identificar tendências, números mais e menos frequentes, padrões de espaçamento e outros insights interessantes para curiosos e entusiastas de loterias.
