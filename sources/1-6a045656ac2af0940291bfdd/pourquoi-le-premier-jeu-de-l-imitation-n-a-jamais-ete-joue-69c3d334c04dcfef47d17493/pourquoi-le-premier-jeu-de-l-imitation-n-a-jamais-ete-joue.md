# Introduction

Dans **Computing Machinery and Intelligence**,
[@turingComputingMachineryIntelligence1950] a présenté ce qui est devenu
le Test de Turing Standard (STT), où un interrogateur doit déterminer
lequel de deux interlocuteurs cachés est humain. Pourtant, la
**première** version du jeu, décrite dans le même texte, est bien moins
discutée :

> Il se joue avec trois personnes : un homme (A), une femme (B) et un
> interrogateur (C), qui peut être de l'un ou l'autre sexe. \[...\]
> L'objectif du jeu pour l'interrogateur est de déterminer qui des deux
> autres est l'homme et qui est la femme. \[...\] Nous posons maintenant
> la question : « Que se passera-t-il lorsqu'une machine prendra la
> place de A dans ce jeu ? [^1]
>
> --- [@turingComputingMachineryIntelligence1950]

Malgré sa place première dans l'article de Turing, ce Test de Turing
Genré (ou *Gendered Turing Test, GTT*) exigeant que la machine incarne
une femme n'a jamais été mis en pratique. Nous pensons que sa valeur
réside dans son cadre provocateur et qu'il mérite d'être réactualisé
dans les débats contemporains sur l'intelligence, qu'elle soit
artificielle ou humaine.

Suivant l'hypothèse de [@sterrettTuringsTwoTests2000] selon laquelle le
GTT serait "l'indication la plus appropriée de l'intelligence" nous
avons émis l'hypothèse que le GTT égaliserait le terrain entre l'humain
et la machine, et qu'il constituerait un test empirique de
l'intelligence basé sur un objectif commun de tromperie. Pour le
vérifier, nous avons conçu une expérience à petite échelle impliquant 9
participant·e·s humain·e·s (4 femmes, 3 hommes et 2 interrogateurs de
genre masculin)[^2] et le modèle de langue ChatGPT-4, tous ayant pour
objectif de jouer le rôle d'une femme. Dans cette expérimentation,
l'interrogateur converse séparément avec deux interlocuteur·ice·s
invisibles, via des médiateurs humains. Chaque échange dure trois
minutes, et les messages sont retardés pour uniformiser la durée de
frappe. Deux sessions totalisant quinze tours nous ont permis d'observer
comment les participant·e·s établissent ou non une stratégie sous la
contrainte enfin, nous avons collectivement commenté l'expérience.

À partir de cette réactualisation, nous soutenons que le GTT n'avait pas
encore été mis en application car sa structure révèle des biais
culturels et interprétatifs, notamment autour de la performance genrée,
que le STT tend à laisser implicite. Plutôt que de mesurer
l'intelligence, les deux versions du jeu de l'imitation fonctionnent
comme des espaces où les présupposés des expérimentateur·ice·s au sujet
de l'intelligence sont exposés. Le GTT le rend particulièrement
explicite : identifier un persona uniquement sur un critère de genre
souligne la complexité du genre en tant que performance linguistique et
culturelle. Revisiter le GTT permet ainsi de recadrer le STT, montrant
que la clarté apparente qui a favorisé son adoption repose sur des
présupposés concernant humain et machine. L'indétermination conceptuelle
présente dans la formulation originale de Turing persiste, suggérant que
les deux tests en révèlent davantage sur nos cadres interprétatifs que
sur la cognition machine.

# État de l'art

Les recherches sur l'article de Turing se concentrent principalement sur
le STT et ses implémentations. Alors que les débats sur les capacités
cognitives des grands modèles de langue (*Large Language Model, LLM*)
LLM abondent, les évaluations utilisant le STT restent inconcluantes :
[@jonesLargeLanguageModels2025] rapportent dans une expérimentation de
grande échelle que GPT-4.5 a trompé les interrogateurs dans 76 % des
parties, tandis que [@restrepoechavarriaChatGPT4TuringTest2025] observe
l'inverse, avec une identification de l'IA dans 9 interactions sur 10.

L'accent mis sur le STT pourrait s'expliquer par le fait que beaucoup
interprètent le GTT comme un dispositif purement illustratif ou
métaphorique (par ex. [@goncalvesTuringsTestBeautiful2024] et
[@piccininiTuringsRulesImitation2000]). D'autres, cependant, considèrent
la version littérale comme significative.
[@genovaTuringsSexualGuessing1994] l'interprète comme un reflet des vues
personnelles de Turing sur l'identité sexuelle, suggérant que la
performativité genrée fournit déjà un modèle pour comprendre comment
l'imitation linguistique pourrait constituer une forme de pensée.

Malgré l'intérêt théorique pour le GTT, seul
[@pattersonGenderTuringTest2018] a tenté une approximation empirique
sous ce nom, en se concentrant sur des humains devinant le genre d'un·e
auteur·ice· à partir de courts textes. Cependant, leur étude
n'impliquait ni dialogue produit par une machine ni échange interactif
dans un cadre ludique. Il manque alors une réactualisation interactive
du GTT mettant en scène les "machines de Turing" à l'état de l'art, à
savoir les LLMs conversationnels ou génératifs.

# Résultats de l'expérience du jeu genré : Jouer la féminité

Des quinze parties de notre expérimentation, hommes, femmes et IA ont
tous remporté plusieurs parties. Bien qu'à petite échelle, ce résultat
souligne la nature performative du dispositif et la profonde
artificialité de la performance genrée
[@butlerGenderTroubleFeminism2011]. Les participantes, quant à elles,
ont délibéré sur l'opportunité d'exagérer les traits féminins ou de
présenter un "soi non marqué". Certaines ont même envisagé d'adopter un
persona "plus masculin", bien que cela aille contre leur intérêt dans la
partie, afin soit de remettre en question les prémisses du jeu soit de
recourir à des pratiques familières de *gender swapping* en ligne
[@hussainGenderSwappingSocializing2008; @tangInvestigatingSexualHarassment2020].
Les participants masculins, qu'ils soient joueurs ou interrogateurs,
avaient tendance à s'appuyer sur des indices formels (ponctuation,
émoticônes) plutôt que sur le contenu sémantique des échanges. Le LLM,
pour sa part, a performé de manière cohérente en suivant le prompt
donné, démontrant que la féminité peut être modélisée par des
instructions basiques en langue naturelle.

Nous avons observé que les interrogateurs évaluaient les réponses qui
leur étaient envoyées en fonction de leurs propres biais et
extrapolaient à partir de micro-indices linguistiques présents dans les
réponses des interlocuteurs. Ce que cette instance du GTT a révélé était
donc moins un concours de tromperie qu'un théâtre d'interprétations.

Notre expérience suggère que l'une des raisons pour lesquelles le
premier jeu de l'imitation de Turing n'a rarement, voire jamais à notre
connaissance, été joué littéralement est qu'il fonctionne moins comme un
test universel d'intelligence que comme un miroir tendu à notre
imagination linguistique et sociale. Le rejouer aujourd'hui avec des
LLMs, capables d'interpréter à un haut degré de fidélité un personnage
humain, rend visible l'ambiguïté procédurale et la volatilité
interprétative qui ont maintenu cette version du jeu largement
théorique.

# Perspectives

Cette réactualisation du GTT démontre comment les méthodes des humanités
numériques peuvent réactiver des expériences de pensée classiques dans
le contexte de questionnement collectif sur l'IA, révélant les
présupposés culturels et interprétatifs que ces outils intègrent.

En promptant un LLM d'adopter un personnage linguistique genré à partir
d'un minimum de consignes, l'expérience montre que les machines peuvent
maîtriser une compétence linguistique, ce qui peut être compris comme
une définition très étroite de l'intelligence, et non comme une norme
universelle. Dans ce contexte, ce qui est mis à l'épreuve ne sont pas
les LLMs, mais plutôt les biais humains exposés par le travail
interprétatif des interrogateurs lorsqu'ils attribuent une identité,
genrée ou autre, dans l'incertitude. L'ambiguïté révélée par le travail
interprétatif des interrogateurs, ambiguïté également présente dans les
implémentations du STT mais ignorée par les études précédemment citées,
rappelle de longs débats philosophiques où l'intelligence humaine est
définie en contraste avec ce que les machines ne peuvent pas encore
faire, comme le suggère la Chambre chinoise de
[@searleMindsBrainsPrograms1980]. Rejouer le GTT clarifie donc que les
deux tests de Turing interrogent, plutôt qu'ils ne déterminent, la
frontière entre cognition humaine et machine, ainsi que les différentes
façons de définir l'intelligence.



# Références

[^1]: Notre traduction

[^2]: Les participant·e·s se sont identifié·e·s en genre.
