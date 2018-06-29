# Luis_Ricardo_DataScience_Files

# DATA SCIENCE APPROACH

## Introdução
A importância da classificação de supernovas se dá por muitos fatores. A classificação de supernovas de tipo Ia é objeto de diversas pesquisas e aplicações referentes a cosmologia e ao entendimento sobre como o universo se expande.
De maneira fundamental, supernovas são explosões estelares que destroem completamente as estrelas e podem ser causadas pelo colapso gravitacional em estrelas massivas e por reações de acréscimo de massa em anãs brancas que desencadeiam explosões termonucleares de proporções extremas. As supernovas formadas por reações termonucleares em anãs brancas são o foco de diversos estudos e são denominadas supernovas Ia.

A expansão acelerada do universo foi constatada pela observação das supernovas de Tipo Ia como sendo pontos de luminosidade com intensidades bem definidas formadas por estrelas anãs brancas (compostas em essência de Carbono e Oxigênio em condições degeneradas). Esta abordagem rendeu o prêmio Nobel de física para os astrônomos Saul Perlmutter (PERLMUTTER et al., 1999), Adam G. Riess e Brian P. Schmidt (RIESS et al., 1998).

## Abordagem

O entendimento computacional sobre este fenômeno reside na capacidade de análise e interpretação dos dados de supernovas coletados. A tarefa de avaliar e analisar os dados referentes às curvas de luz e aos espectros é estritamente dependente da especialidade de um astrônomo, entretanto executar esta tarefa de maneira prática e consistente é difícil devido à complexidade e a grande quantidade de dados gerados.

A análise espectral de supernovas tem sua importância, pois o espectro é o primeiro tipo de informação que se obtém da observação de uma explosão de supernova. Esta análise permite avaliar os tipos de supernovas de colapso de núcleo e termonucleares (tipo Ia) em um curto espaço de dias. Este curto período é referente ao pico de luminosidade máxima da explosão observada, fora deste período as características dos espectros mudam completamente, sendo difícil sua classificação e análise. A figura 1 ilustra como os espectros sofrem alterações importantes tornando a tarefa de classificação espectral dificil no decorrer dos dias. O ponto indicado como 0 dia é o ponto em que a supernova atinge sua luminosidade máxima.

<p align="center"> Figura 1 - Fases espectrais de uma supernova de tipo Ia</p>

<p align="center">
<img width="460" height="300" src="https://github.com/LuisRicardoAF/Luis_Ricardo_DataScience_Files/blob/master/phase.png">
</p>

<p align="center"> Fonte: Blondin (2012)</p>

Desta maneira se propõe uma abordagem que possa analisar e avaliar os espectros de supernovas antes e depois do pico de luminosidade máxima para que se possa gerar modelos de classificação que correlacionem estas fases com o tipo de supernovas. Desta maneira é possível avaliar supernovas de tipo Ia pelo espectro antes da luminosidade máxima e nas fases finais quando o brilho é mais fraco, permitindo ampliar as condições de contorno da classificação espectral de supernovas.

## Dados

Os dados a serem utilizados são de acesso gratuito e definidos na tabela 1. Estes dados compreendem espectros de supernovas de diversos tipos de supernovas estando em diversas fases de observação. Os dados são dispostos em arquivos no formato ascii com as colunas para o comprimento de onda em [Å] e o fluxo de radiação em [1e-15 erg/s/cm2/A]. As fases de cada espectro também estão disponíveis nos arquivos de publicação dos espectros.

<p align="center"> Tabela 1 – Identificação de dados </p>

<p align="center">
<img width="460" height="300" src="https://github.com/LuisRicardoAF/Luis_Ricardo_DataScience_Files/blob/master/dados.png">
</p>

## Resultados Esperados

Espera-se com a avaliação e organização dos dados de fase espectral aplicando as diversas atividades da disciplina de introdução a DataScience gerar um esquema de classificação seguro que permita avaliar supernovas fora da faixa de dias da luminosidade máxima. Outro ponto importante nesta abordagem é verificar o comportamento das supernovas Ia em cada uma de suas fases de forma a identificar se determinado perfil do espectro dura mais dias em algumas supernovas do que em outras e se o espectro indica se elas evoluem de maneira parecida. Neste sentido, seria possível identificar se o perfil de supernova Ia no brilho máximo dura mais ou menos dias de supernova para supernova.

A figura 2 ilustra a forma como se pretende aplicar a abordagem da divisão de espectros por fases para gerar um agrupamento e classficação dos dados.

<p align="center"> Figura 2 - Resultados para separação e classificação das fases de uma supernova Ia</p>
<p align="center">
<img width="460" height="300" src="https://github.com/LuisRicardoAF/Luis_Ricardo_DataScience_Files/blob/master/fasesAnalysis.png">
</p>

<p align="center"> Fonte: Sandelli (2016)</p>


## Referências

•	PERLMUTTER, S. et al. 1999. Measurements of omega and lambda from 42 high-redshift supernovae. The Astrophysical Journal, v. 517, n. 2, p. 565, 1999.

•	RIESS, A. G. et al. 1998. Observational evidence from supernovae for an accelerating universe and a cosmological constant. The Astronomical Journal, v. 116, n. 3, p. 1009, 1998.

•	BLONDIN, S.; MANDEL, K. S.; KIRSHNER, R. P. 2011. Do spectra improve distance measurements of Type Ia supernovae? Astronomy & Astrophysics, v. 526, p. A81, 2011.

•	BLONDIN, S. et al. The spectroscopic diversity of type Ia supernovae. The Astronomical Journal, v. 143, n. 5, p. 126, 2012.

•	MATHESON, T. et al. Optical spectroscopy of Type Ia supernovae. The Astronomical Journal, v. 135, n. 4, p. 1598, 2008.

•	MODJAZ, M. et al. Optical spectra of 73 stripped-envelope core-collapse supernovae. The Astronomical Journal, v. 147, n. 5, p. 99, 2014.

• SASDELLI, M.; ISHIDA, E. E. O.; VILALTA, R.; AGUENA, M.; BUSTI, V. C.; CAMACHO, H.; TRINDADE, A. M. M.; GIESEKE, F.; SOUZA, R. S. de;
FANTAYE, Y. T.; MAZZALI, P. A. Exploring the spectroscopic diversity of type ia supernovae with dracula: a machine learning approach. Monthly Notices of the Royal Astronomical Society, v. 461, n. 2, p. 2044–2059, 2016. 20, 21

