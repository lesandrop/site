# Avaliação do engajamento de longo prazo de programadores em projetos de código aberto

1. Nome do aluno 1

1. Nome do aluno 2 (se houver)

* Lesandro Ponciano (orientador de acadêmico)

## Introdução

1. A área da Engenharia de Software tratada neste trabalho é _Fatores Humanos na Engenharia de Software_ e _Desenvolvimento de Software de Código Aberto_

1. O problema que este trabalho busca resolver nessa área é conforme as questões de pesquisa (RQ, do inglês _Research Questions_) a seguir: _(RQ1) Qual é a duração do engajamento de programadores em projetos de código aberto? (RQ2) Os programadores se engajam fazendo commit nos projetos de código aberto de forma transiente, i.e. uma vez e não voltam mais, ou eles permanecem engajados ao longo do tempo? (RQ3) A popularidade do projeto influencia a duração do engajamento?_

1. Resolver este problema é relevante por que _a avaliação do engajamento permite analisar a sustentabilidade do projeto de código aberto tendo a conta a tendência que ele tem programadores (contribuidores) ao longo tempo, permite avaliar riscos à sua qualidade quando os programadores no caso, por exemplo, de programadores que apresentam um comportamento transientes, e, por fim, pode-se compreender se a popularidade dos projeto incentiva no engajamento de longo prazo_

1. O objetivo geral deste trabalho é _medir a duração de engajamento de longo prazo de programadores em projetos de código aberto._

1. Os *três* objetivos específicos deste trabalho são: _(1) Contrastar abordagens para mensurar engajamento de longo prazo em contexto de projeto de código aberto; (2) Distinguir programadores que apresentam engajamento de longo prazo e programadores que exibem engajamento de curto prazo; (3) Analisar se a duração do engajamento é influenciada por características de popularidade dos projetos, como o número de forks._


## Fundamentação Teórica

1. O conceito/teoria principal associado a este trabalho é _desenvolvimento de software open source_  A sua definição neste trabalho é o "desenvolvimento de software lançado sob uma licença na qual o detentor dos direitos autorais concede aos usuários os direitos de usar, estudar, alterar e distribuir o software e seu código-fonte a qualquer pessoa e para qualquer finalidade", conforme definido no trabalho "Understanding open source and free software licensing: guide to navigating licensing issues in existing & new software" (https://www.oreilly.com/library/view/understanding-open-source/0596005814/index.html) pelo autor Andrew M Laurent (2004).

1. O conceito/teoria secundário associado a este trabalho é _engajamento humano_. A sua definição neste trabalho é "um processo composto por quatro estágios distintos: ponto de engajamento, período de engajamento sustentado, desengajamento e reengajamento. Além disso, o processo é caracterizado por atributos de engajamento que dizem respeito ao usuário, ao sistema e à interação usuário-sistema.", conforme definido no trabalho "What is user engagement? A conceptual framework for defining user engagement with technology" (https://doi.org/10.1002/asi.20801), pelos autores Heather L. O'Brien, Elaine G. Toms (2008)

1. O conceito/teoria terciário associado a este trabalho é _duração do engajamento_ A sua definição neste trabalho é _"Duração do período de engajamento sustentado, por vezes denominado retenção. Expressa quanto tempo um ser humano permanece no sistema. É um envolvimento de curto prazo quando ocorre durante um período de tempo relativamente curto (por exemplo, minutos ou horas), e um envolvimento de longo prazo quando dura um longo período de tempo (por exemplo, meses ou anos). No engajamento de curto prazo, o ponto de engajamento é o momento em que o indivíduo executa a primeira ação dentro do sistema, o período de engajamento é o intervalo de tempo durante o qual ele/ela continua interagindo com o sistema em uma sessão de trabalho contínua. No envolvimento de longo prazo, o ponto de engajamento é o momento em que o indivíduo realiza a primeira ação dentro do sistema, o período de engajamento refere-se ao número de dias em que ele continua interagindo com o sistema, e o ponto de desligamento refere-se ao dia em que ele sai do sistema e não volta mais. Assim, o envolvimento de longo prazo pode consistir em vários ciclos de envolvimento de curto prazo."_ Essa definição é conforme definido no trabalho "Finding Volunteers' Engagement Profiles in Human Computation for Citizen Science Projects" (https://doi.org/10.15346/hc.v1i2.12), pelos autores Lesandro Ponciano e Francisco Brasileiro (2014).   


## Trabalhos Relacionados

1. O trabalho mais relacionado é "How Gamification Affects Software Developers: Cautionary Evidence from a Natural Experiment on GitHub" (https://doi.org/10.1109/ICSE43902.2021.00058), publicado no ano 2021, por que ele estuda como programadores que atuam em código aberto respondem à gamificação, que é uma forma de engajá-los e de mantê-los engajados.

1. O segundo trabalho mais relacionado é "Studying Software Developer Expertise and Contributions in Stack Overflow and GitHub" (https://doi.org/10.1109/ICSME46990.2020.00038), publicado no ano 2020, por que ele trata da expertise dos programadores e de suas contribuições em projetos de código aberto, permitindo entender suas contribuições em termos quantitativos e qualitativos, que são essenciais para análise de engajamento.

1. O terceiro trabalho mais relacionado é "Herding a Deluge of Good Samaritans: How GitHub Projects Respond to Increased Attention" (https://doi.org/10.1145/3366423.3380272), publicado no ano 2021,  por que ele coloca a questão da popularidade ou atenção recebida pelo projeto e de como isso afeta o comportamento dos programadores, sendo, portanto, relevante para se compreender como popularidade e engajamento podem estar relacionados.
## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é "quantitativa", porque _ela trata de atribuidos quantitativos associados à duração do engajamento dos programadores nos projetos_, e também é  e "descritiva", pois ela _trata da descrição das propriedades do engajamento natural (orgânico) dos programadores sem qualquer controle de variáveis._

1. Os materiais utilizados neste trabalho são come segue: a) _projetos de código aberto selecionados são aqueles que utilizam a plataforma GitHub (https://github.com/), um conjunto de 30 projetos com diferente número de forks, de 10 a 10000, são analisados; 2) dados dos commits feitos pelos programadores são coletados via Interface de Programação de Aplicações (API) do GitHub (https://docs.github.com/en/rest?apiVersion=2022-11-28). A cada commit estão associadas às informações do projeto, programador e data; 3) dados da popularidade dos projetos quanto ao número de forks e número de programadores, ambos coletados via API._

1. Os métodos empregados neste trabalho são _agrupamento k-means (https://doi.org/10.1016/S0031-3203(02)00060-2), regressão linear, correlação (Spearman ou Kendall), análise de tendência central e de dispersão._

1. As métricas de avaliação empregadas no estudo são _Relative Activitiy Duration_ do programador (https://doi.org/10.15346/hc.v1i2.12), _Activity Ratio_ do programador (https://doi.org/10.1109/MCSE.2014.4), _número de forks_ do projeto e número de programadores no projeto. 

1. As etapa de execução do trabalho são: (1) coletar os dados dos projetos no GitHub; (2) calcular as métricas, (3) analisar tendência central e dispersão; (4) analisar a relação entre as variáveis por correlação e regressão; e (5) analisar o agrupamento k-means. A partir dessas etapas, as questões de pesquisa são respondidas e os objetivos (geral e específicos) são atingidos.
