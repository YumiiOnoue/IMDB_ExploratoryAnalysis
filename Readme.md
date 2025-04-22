# Análise Exploratória de Dados do IMDB

## Introdução

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) em um conjunto de dados do IMDb. A análise explora diversas variáveis relacionadas a filmes, incluindo notas, gêneros e ano de lançamento, utilizando bibliotecas do ecossistema Python para manipulação e visualização de dados.

## Tecnologias Utilizadas
- Python
- Jupyter Notebook
- Pandas - Manipulação de dados
- Matplotlib & Seaborn - Visualização de dados
- NumPy - Cálculos estatísticos

## Objetivos
- Carregar e explorar o conjunto de dados do IMDb.
- Identificar padrões e relações entre variáveis.
- Criar visualizações gráficas para facilitar a compreensão dos dados.
- Gerar insights sobre tendências em avaliações de filmes.

## Resultados

Ao analisar os dados da IMDb, observa-se que 73,14% do conteúdo é classificado como TV Episode, seguido de shorts (curtas-metragens) com 10,16%, e apenas 7,21% corresponde à categoria movie (filmes). Esse panorama revela um dado interessante: a maioria do conteúdo cadastrado na plataforma não são filmes tradicionais, como muitas vezes se supõe ao pensar na IMDb.
Entretanto, o grande número de TV Episode pode ser explicado pela forte presença e relevância das produções seriadas, que incluem temporadas longas, spin-offs e minisséries.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/distribuicao_titulo.png)

Ao analisar a distribuição percentual de títulos por gênero, fica evidente a predominância do gênero Drama, que representa a maior fatia dos títulos cadastrados na IMDb, seguido por Comédia e Documentário. Em relação aos gêneros com menor participação nas produções são: Game-Show, Talk-Show, Film-Noir e Reality-TV.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/n_titulos_genero.png)

A seguir temos os resultados para a análise das avalições dos filmes.
Apesar do produção de filmes ser predominantemente do gênero drama e seguido de comédia, o que possui a melhor avaliação mediana são os filmes do gênero documentário, ou seja, 50% das avalições desse gênero são maiores ou iguais a 7,3 e 50% são menores ou iguais a esse valor. 

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/mediana_avaliacao.png)

Ao analisar a mediana das avalições por ano de estréia, pode-se observar que nos primeiros anos há uma grande oscilação entre as medianas das avaliações. Somente, a partir de 1920, nota-se uma estabilização gradual, permanecendo estável acima de 6,0 e 6,5. Entretanto, a partir dos anos 2000, a tendência é de aumento da mediana, permanecendo mais próximo dos 6,5 do que dos 6,0.
Portanto, nesse gráfico temos uma tendência positiva nas avalições dos filmes, podendo ser justificado pelo maior investimento em tecnologia, produção e roteiro.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/mediana_ano_lancamento.png)

O gráfico a seguir mostra o número de filmes avaliados por gênero em relação ao ano de estréia. Para essa análise destacamos os gêneros mais avaliados, que são: drama, documentário, comédia, ação e romance.
Para o período analisado, o gênero drama possui predominancia na avaliação. Destacando o período após os anos de 2000 que houve aumento expressivo na quantidade de filmes avaliados desse gênero e de outros, e em 2017, drama ultrapassa mais de 6 mil filmes avaliados.
Até aproximadamente os anos 2000, o segundo gênero mais avalido era documentário, sendo ultrapassando pelo gênero comédia e atingindo valores bem próximos da quantidade de filmes avalidos do gênero drama. Já os gêneros ação e romance, ficam mais proximos de mil filmes avaliados.
Para o período após 2020, observa-se uma queda no número de avaliações, que pode ser explicada por dois fatores principais: o impacto da pandemia da COVID-19 e do atraso nas avalições dos títulos mais recentes.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/numero_filmes_avaliados.png)

Em relação a duração dos filmes, o filme mais longo, até o momento, é 'Logistics', com 857 horas (51420 minutos). Dirigido por Daniel Andersson e Erika Magnusson, o filme acompanha todo o ciclo de vida de um pedômetro (dispositivo de rastreamento de passos) em ordem cronológica reversa. Esse filme é do gênero documentário, entretanto esse gênero não é considerado o maior em relação a duração. 
O gênero com maior duração é romance com 95 minutos, seguido por ação, guerra e drama (93 min). Sendo, a maioria dos longas-metragens com 90 minutos ou mais.
Já o gênero documentário tem duração de 74 minutos, mostrando o diferencial do filme Logistics, que apresenta mais de 694 vezes a duração mediana do gênero.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/duracao_genero.png)

Os três maiores países em produção de filmes são: Estados Unidos com 255.987 filmes, seguido pelo Reino Unido com 113.225 e o Japão com 87.815 filmes. A diferença entre os Estados Unidos e o segundo colocado ultrapassa 142 mil filmes, ou seja, mais de duas vezes a produção do Reino Unido, o que reforça o tamanho, a influência e o investimento contínuo da indústria cinematográfica norte-americana no cenário global.
Comparando com o Brasil, que produz 61.825 filmes e ocupa a 9ª posição, a produção cinematográfica nacional representa cerca de 24% da produção norte-americana.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/409f5e54d74fb8199931c7cfd4be76d879d7d179/producao_pais.png)

Ao analisar as avaliações dos filmes, o filme com a maior nota é The Shawshank Redemption, seguido de The Chaos Class e The Godfather, ambos do gênero Drama. O gênero Drama também aparece em 8 dos 10 melhores filmes, podendo indicar a preferência por uma grande carga emocional.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/cfd333757e27a95a67a8a6019e1e68740895bdec/melhores_filmes.jpeg)

Já os filmes com menor aceitação foram: o filme Cumali Ceber, do gênero comédia, seguido de Smolensk e Sadak 2, sendo esses dois últimos do gênero drama. Esses títulos ocupam as posições mais baixas da tabela, com notas entre 1.0 e 1.1, indicando forte rejeição do público e da crítica.

![Image Alt](https://github.com/YumiiOnoue/IMDB_ExploratoryAnalysis/blob/cfd333757e27a95a67a8a6019e1e68740895bdec/piores_filmes.jpeg)

Tanto os melhores filmes e piores filmes, são na sua maioria, do gênero drama ou comédia. Podendo significar que quando mal executados, sofrem maior rejeição, reforçando a importância de um bom desenvolvimento de roteiro, direção e atuação para agradar ao público.


## Conclusão
Conclui-se que a partir dos anos 2000, houve um aumento significativo na produção cinematográfica e que o gênero mais produzido é drama e comédia. Entretanto, no quesito aceitação do público, o gênero documentário é o mais bem avaliado. Sendo que avaliação não está diretamente relacionada com a duração do filme. Outro ponto a destacar, é a representatividade da produção dos Estados Unidos, sendo esta mais de duas vezes a quantidade produzido pelo segundo país do ranking.

-------------------

Este projeto foi desenvolvido nas aulas de Python da Data Science Academy. 

Também é a minha primeira vez utilizando o Github. Qualquer sugestão será bem vinda! ☺️ 
