Análise de Diversidade 2022 - Curso de Dados PrograMaria

Análise exploratória de dados da pesquisa Data Hackers 2022, com foco em diversidade de gênero e raça no mercado de dados brasileiro.

📋 Sobre o Projeto

Este projeto foi desenvolvido como parte do curso de Dados da PrograMaria e tem como objetivo explorar os dados da pesquisa Data Hackers 2022, identificando padrões de diversidade, desigualdade de gênero e raça no mercado de dados brasileiro.

As análises foram realizadas no Google Sheets e visualizadas no Google Data Studio (Looker Studio), cobrindo perfil sociodemográfico, formação acadêmica, nível de senioridade e faixas salariais dos respondentes.

🗂️ Sobre a Base de Dados
Fonte: Pesquisa Data Hackers 2022 — base pública
Total de respondentes: 4.270
Variáveis: 29 colunas cobrindo perfil sociodemográfico, formação acadêmica, situação de trabalho, cargo, nível de senioridade e faixa salarial
Ferramentas utilizadas: Google Sheets e Google Data Studio
Indicadores gerais
Indicador	Valor
Total de respostas	4.270
Gênero feminino	1.055 (24,71%)
Pessoas não brancas	1.527 (35,76%)
PCDs	54 (1,26%)
Fora de SP	2.410 (56,44%)
🧹 Decisões Metodológicas

Antes das análises, foram tomadas algumas decisões importantes para garantir a qualidade e a honestidade dos resultados:

Campos em branco: 9 respondentes não informaram o gênero e foram excluídos das análises de gênero
"Prefiro não informar" em gênero: 12 pessoas — menos de 0,3% da base — foram excluídas por não gerarem conclusões estatisticamente confiáveis
Grupos raciais pequenos: as categorias Outra (17 pessoas), Indígena (11 pessoas) e Prefiro não informar em raça (26 pessoas) foram excluídas das visualizações principais, porém mencionadas por transparência metodológica
Nulos estruturais: os 577 registros sem faixa salarial e nível de senioridade correspondem a respondentes não empregados (desempregados, estudantes) — não são erros, são dados estruturais
Média salarial: calculada a partir do ponto médio de cada faixa salarial declarada, sendo uma estimativa aproximada e não um valor exato
📊 Análises Realizadas
1. Painel Resumo

Cinco indicadores-chave que apresentam um recorte imediato sobre representatividade e diversidade na área de dados brasileira.

Os cinco indicadores, juntos, traçam um perfil claro de quem está sub-representado na área de dados: mulheres representam menos de 1 em cada 4 profissionais, pessoas não brancas somam 35,76% apesar de serem maioria na população brasileira, e PCDs são praticamente invisíveis com apenas 1,26% da base.

2. Distribuição por Gênero
Gênero	Quantidade	%
Masculino	3.194	74,78%
Feminino	1.055	24,72%

Insight: Para cada mulher na área de dados, há aproximadamente 3 homens — uma desproporção significativa que se reflete nos níveis de carreira e faixas salariais.

3. Distribuição por Cor/Raça/Etnia
Raça	Quantidade	%
Branca	2.744	65,07%
Parda	1.054	24,99%
Preta	291	6,90%
Amarela	128	3,04%

Insight: 9 em cada 10 profissionais de dados se autodeclaram brancos ou pardos. Pessoas pretas representam menos de 7% da área.

Excluídos da visualização: Indígena (11), Outra (17) e Prefiro não informar (26) — menos de 1% da base.

4. Distribuição de Gênero por Etnia
Raça	Feminino	%	Masculino	%	Total
Branca	654	23,90%	2.082	76,10%	2.736
Parda	270	25,71%	780	74,29%	1.050
Preta	81	28,22%	206	71,78%	287
Amarela	38	29,69%	90	70,31%	128

Insight: A área de dados é majoritariamente masculina em todos os grupos raciais. Um padrão interessante: quanto mais minorizada a raça, maior a proporção feminina — sugerindo que mulheres de grupos raciais minorizados que entram na área tendem a ter perfil diferenciado.

5. Distribuição de Pessoas no Brasil

Top 10 estados:

Estado	Qtd	%
São Paulo (SP)	1.745	40,86%
Minas Gerais (MG)	478	11,19%
Rio de Janeiro (RJ)	338	7,91%
Paraná (PR)	309	7,23%
Rio Grande do Sul (RS)	204	4,78%
Bahia (BA)	162	3,79%
Santa Catarina (SC)	156	3,65%
Distrito Federal (DF)	132	3,09%
Pernambuco (PE)	120	2,81%
Ceará (CE)	95	2,22%

Por região:

Região	Qtd	%
Sudeste	2.642	61,86%
Sul	669	15,66%
Nordeste	530	12,41%
Centro-Oeste	222	5,20%
Norte	61	1,43%

Insight: São Paulo concentra 40,86% de todos os profissionais. O Norte do país, com apenas 1,43%, evidencia uma desigualdade regional profunda no acesso ao mercado de dados.

6. Gênero x Escolaridade
Nível de Ensino	Feminino	%	Masculino	%	Total
Graduação/Bacharelado	365	24,28%	1.138	75,72%	1.503
Pós-graduação	370	28,33%	936	71,67%	1.306
Estudante de Graduação	104	17,05%	506	82,95%	610
Mestrado	133	25,63%	386	74,37%	519
Doutorado ou PhD	57	29,84%	134	70,16%	191
Não tenho graduação formal	24	21,82%	86	78,18%	110

Insight: Mulheres representam apenas 17,05% entre estudantes de graduação, mas chegam a 29,84% entre doutoras e PhDs — sugerindo que precisam de mais credenciais acadêmicas para competir em igualdade de condições.

7. Gênero x Nível de Senioridade
Nível	Feminino	%	Masculino	%	Total
Júnior	272	26,80%	743	73,20%	1.015
Pleno	295	27,96%	760	72,04%	1.055
Sênior	187	20,87%	709	79,13%	896
Pessoa Gestora	132	18,59%	578	81,41%	710

Insight: A desigualdade de gênero se aprofunda conforme a carreira avança. Mulheres são 26,80% no Júnior e caem para 18,59% na Gestão — evidenciando um teto de vidro claro na área de dados.

8. Média Salarial por Gênero
Gênero	Média Salarial
Masculino	R$ 10.488,63
Feminino	R$ 8.632,79
Diferença	R$ 1.855,84

Insight: Homens ganham em média 17,7% a mais que mulheres. Para cada R$ 1,00 que um homem ganha, uma mulher recebe R$ 0,82 — gap que se combina com a sub-representação feminina nos níveis mais altos.

9. Etnia x Escolaridade
Raça	Graduação	Pós-grad	Est. Grad	Mestrado	Doutorado	Sem grad
Branca	36,41%	30,07%	13,30%	12,94%	4,63%	2,37%
Parda	31,59%	32,64%	16,89%	10,72%	4,74%	3,13%
Preta	35,74%	30,24%	17,53%	11,34%	2,06%	3,09%
Amarela	39,06%	31,25%	11,72%	10,94%	5,47%	1,56%

Insight: Pessoas pretas têm a maior proporção ainda estudando (17,53%) e a menor com doutorado (2,06%) — menos da metade do observado entre brancos (4,63%). Pardos lideram em pós-graduação (32,64%), possivelmente como estratégia para compensar barreiras raciais.

10. Etnia x Média Salarial
Raça	Média Salarial
Amarela	R$ 13.197,58
Branca	R$ 11.906,27
Parda	R$ 9.044,03
Preta	R$ 7.718,27

Insight: Pessoas pretas ganham em média R$ 4.188,00 a menos que pessoas brancas — uma diferença de 35%. A desigualdade salarial racial é consistente e se soma às barreiras de progressão de carreira já identificadas.

11. Etnia x Região do Brasil
Região	Branca	Parda	Preta	Amarela
Sudeste	65,82%	23,38%	7,04%	3,75%
Sul	81,17%	13,70%	3,77%	1,36%
Nordeste	46,67%	41,26%	10,45%	1,62%
Centro-Oeste	60,93%	30,23%	6,05%	2,79%
Norte	50,00%	44,59%	4,05%	1,35%

Insight: O Sul é a região mais homogênea (81,17% branca). Nordeste e Norte apresentam maior diversidade racial, mas são justamente as regiões com menos oportunidades no mercado de dados — criando uma dupla desvantagem para pessoas pretas e pardas nessas regiões.

12. Etnia x Nível de Senioridade

% dentro de cada nível:

Nível	Branca	Parda	Preta	Amarela	Total
Júnior	60,80%	26,57%	9,75%	2,89%	1.005
Pleno	65,33%	25,50%	6,59%	2,58%	1.047
Sênior	69,97%	22,61%	4,39%	3,04%	889

% que chegam à gestão dentro de cada grupo racial:

Raça	Gestores	Total	%
Amarela	28	111	25,23%
Branca	480	2.397	20,03%
Parda	162	897	18,06%
Preta	35	241	14,52%

Insight: Pessoas pretas representam 9,75% no Júnior e caem para 4,39% no Sênior — uma redução de mais da metade. Na gestão, apenas 14,52% dos profissionais pretos empregados chegam a posições de liderança, contra 20,03% dos brancos.

🔍 Conclusão

A análise exploratória da pesquisa Data Hackers 2022 revelou um retrato claro e preocupante sobre diversidade no mercado de dados brasileiro. A área é predominantemente masculina e branca, e essa desigualdade não se limita à entrada — ela se aprofunda conforme a carreira avança.

Os principais achados foram:

Desigualdade de gênero: para cada mulher na área, há 3 homens. Mulheres representam 26,80% no Júnior e caem para 18,59% na gestão
Desigualdade racial: pessoas pretas representam menos de 7% da área e ganham 35% a menos que brancos em média
Teto de vidro duplo: mulheres e pessoas pretas encontram barreiras que se intensificam exatamente nos momentos de maior progressão
Escolaridade compensatória: mulheres e pardos buscam mais qualificação acadêmica, possivelmente como estratégia para competir em condições desiguais
Desigualdade regional: o Sudeste concentra 62% dos profissionais, e regiões com maior diversidade racial têm menos acesso ao mercado de dados
🛠️ Processo Técnico

Toda a análise foi realizada no Google Sheets com visualizações no Google Data Studio, seguindo estas etapas:

Entendimento da base: leitura das variáveis, identificação de tipos de dados, nulos e valores únicos
Limpeza e decisões metodológicas: exclusão de categorias com amostra pequena, documentadas por transparência
Tabelas dinâmicas: cada análise construída com filtros específicos e valores calculados como % da linha para comparação proporcional
Visualizações: gráficos de barras horizontais empilhadas com paleta de cores padronizada em degradê de roxo
🚀 Próximos Passos
Cruzar raça + gênero simultaneamente para medir desigualdade acumulada
Analisar salário controlando por cargo e tempo de experiência
Comparar com edições anteriores da pesquisa Data Hackers para identificar tendências
Evoluir as análises para Python com pandas para cruzamentos mais complexos
📊 Dashboard

As visualizações completas estão disponíveis no Google Data Studio:
👉 Acessar Dashboard — Análise de Diversidade 2022

👩‍💻 Sobre

Análise desenvolvida durante o curso de Dados da PrograMaria.
Dados: Data Hackers Survey 2022
