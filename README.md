# enade-data-mining
## Idetificação de Perfis de Alunos do ENADE 2018 e Suas Caracteristicas

O objetivo dessa análise é descobrir relações entre a nota do aluno e sua situação socioeconômica usando duas tecnicas: regras de associação(Apriori) e árvore de classificação

## ENADE
A prova do Enade afere o desempenho dos estudantes em relação aos conteúdos programáticos previstos nas Diretrizes Curriculares Nacionais ou no Catálogo Nacional de Cursos Superiores de Tecnologia do respectivo curso de graduação, suas habilidades para ajustamento às exigências decorrentes da evolução do conhecimento e suas competências para compreender temas exteriores ao âmbito específico de sua profissão, ligados à realidade brasileira e mundial e a outras áreas do conhecimento.

As provas são compostas por uma parte de Formação Geral, comum aos cursos de todas as áreas, e uma parte de Componente Específico, própria de cada área de avaliação. A parte de Formação Geral tem 10 questões, sendo duas discursivas e oito de de múltipla escolha, envolvendo situações-problema e estudos de casos. A concepção dos itens é balizada pelos princípios dos Direitos Humanos. As questões discursivas avaliam aspectos como clareza, coerência, coesão, estratégias argumentativas, utilização de vocabulário adequado e correção gramatical do texto. Já a parte de Componente Específico de cada área de avaliação tem 30 questões, sendo três discursivas e 27 de múltipla escolha, envolvendo situações-problema e estudos de casos.

## Caracteristicas do Dataset

O dataset do ENADE possui as notas gerais e específicas do aluno, além de seus dados socioeconômicos.
### Dados Gerais
| Nome da variável | Categorias |
| ------ | ------ |
| MODALIDADE | presencial ou a distância |
| REGIÃO | Acre (AC) , Alagoas (AL), Amapá (AP), Amazonas (AM), Bahia (BA), Ceará (CE), Distrito Federal (DF), Espírito Santo (ES), Goiás (GO), Maranhão (MA), Mato Grosso (MT), Mato Grosso do Sul (MS), Minas Gerais (MG), Pará (PA), Paraíba (PB), Paraná (PR), Pernambuco (PE), Piauí (PI), Rio de Janeiro (RJ), Rio Grande do Norte (RN), Rio Grande do Sul (RS), Rondônia (RO), Roraima (RR), Santa Catarina (SC), São Paulo (SP), Tocantins (TO) |
| REGIÃO |Região Norte (NO), Região Nordeste (NE), Região Sudeste (SE), Região Sul (SUL), Região Centro-Oeste (CO) |
|IDADE | 4 e 94|
| ETNIA |Branca , Preta, Amarela, Parda, Indígena, Não quero declarar.|
| RENDA | Até 1,5 salário mínimo (até R$ 1.431,00), De 1,5 a 3 salários mínimos (R$ 1.431,01 a R$ 2.862,00), De 3 a 4,5 salários mínimos (R$ 2.862,01 a R$ 4.293,00), De 4,5 a 6 salários mínimos (R$ 4.293,01 a R$ 5.724,00), De 6 a 10 salários mínimos (R$ 5.724,01 a R$ 9.540,00), De 10 a 30 salários mínimos (R$ 9.540,01 a R$ 28.620,00), Acima de 30 salários mínimos (mais de R$ 28.620,00).|
| SITUACAO_TRABALHO |Não estou trabalhando.Trabalho eventualmente.Trabalho até 20 horas semanais.Trabalho de 21 a 39 horas semanais.Trabalho 40 horas semanais ou mais.|
| TP_BOLSA | Nenhum, pois meu curso é gratuito. Nenhum, embora meu curso não seja gratuito. ProUni integral. ProUni parcial,  apenas.FIES,  apenas.ProUni Parcial e FIES. Bolsa oferecida por governo estadual, distrital ou municipal. Bolsa oferecida pela própria instituição. Bolsa oferecida por outra entidade (empresa, ONG,outra).Financiamento oferecido pela própria instituição.Financiamento bancário.|
| TP_ENSINO_MEDIO | Todo em escola pública. Todo em escola privada (particular). Todo no exterior. A maior parte em escola pública. A maior parte em escola privada (particular). Parte no Brasil e parte no exterior. |
| SUPERIOR_FAMILIA | Sim ou Não|

## Bibliotecas usadas


- Python 
- Aequitas 
- Numpy
- Seasborn
- Jupyter Notebook
- Sklearn
- Matplotlib
- Pandas
