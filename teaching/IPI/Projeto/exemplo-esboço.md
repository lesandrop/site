# Equipe

* Nome do aluno 1
* Nome do aluno 2
* Nome do aluno 3 (se houver)
* Nome do orientador acadêmico e de conteúdo

# Tema
O tema tratado na pesquisa é _engajamento de longo prazo de programadores em projetos de código aberto_.

# Problema
O problema a ser resolvido na pesquisa é: _Qual é a duração do engajamento de programadores em projetos de código aberto? Os programadores se engajam fazendo commit nos projetos de código aberto de forma transiente, i.e. uma vez e não voltam mais, ou eles permanecem engajados ao longo do tempo? A propularidade do projeto influencia a duração do engajamento?_.

# Objetivo geral
O objetivo geral a ser alcançado nesta pesquisa é _medir a duração de enjamento de longo prazo de programadores em projetos de código aberto_.

# Objetivos específicos
Os objetivos específicos são:
1. _Constrastar abordagens para mensurar engajamento de longo prazo em contexto de projeto de código aberto;
2. _Distinguir programadores que apresentam engajamento de longo prazo e programadores que exibem engajamento de curto prazo_;
3. _Analisar se a duração do engajamento é influenciada por características de popularidade dos projetos, como o número de forks_.
   
# Materiais e Métodos
As ferramentas, dados, métricas, forma de amostragem, análise estatística são:
* Os projetos de código aberto selecionados são aqueles que utilizam a plataforma GitHub (https://github.com/). Um conjunto de 30 projetos com diferente número de forks, de 10 a 10000, são analisados.
* Dados dos commits são coletados via Interface de Programação de Aplicações (API) do GitHub (https://docs.github.com/en/rest?apiVersion=2022-11-28). A cada commit estão associadas as informações do projeto, programador e data.
* Engajamento de longo prazo é medido pelas métricas _Relative Activitiy Duration_ (definida no trabalho científico disponível no seguinte link https://doi.org/10.15346/hc.v1i2.12) e Activity Ratio (definida em no trabalho científico disponível no seguinte link https://doi.org/10.1109/MCSE.2014.4)
* Progamadores são analisados em grupo pelos valores de _Relative Activitiy Duration_  e _Activity Ratio_
* Correlação de Spearman é medida entre popularidade de projeto e média de engajamento dos programadors.
