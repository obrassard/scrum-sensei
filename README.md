# *SCRUM-Sensei* : Introduction à SCRUM et à l'analyse d’applications

## Introduction

Scrum est une méthode [agile](#les-12-principes-agiles-) dédiée à la « gestion de projet ». Cette méthode de gestion, à pour objectif d’améliorer la productivité de son équipe. Elle est constituées de différentes *activités* qui s'enchainent en cycles itératifs.

Vous touverez dans ce guide, la description des différentes activités d'un cycle.

## :coffee: Tu as passé ton examen d'analyse d'applications grâce à ScrumSensei ?<br>[Ça vaut bien un petit café non](https://paypal.me/obrassard) ?! :smile:

## Table des matières

1. [Sprint 0, Grooming et Backlog de produit](#1-sprint-0--grooming--préparation-du-backlog-de-produit)<br>
2. [Planif de Sprint](#2-planif-de-sprint)<br>
3. [Les Sprints](#3-sprint-)<br>
    3.1 [La mêlée quotidienne](#31-la-mêlée-quotidienne-à-chaque-jour-pendant-les-sprints)<br>
4. [La revue de Sprint](#4-revue-de-sprint)<br>
5. [La rétrospective de Sprint](#5-rétrospective-de-sprint)<br>
6. [Le sprint de release](#6-sprint-de-release)<br>
7. [Les rôles au sein du procéssus SCRUM](#rôles-au-sein-du-procéssus-scrum)<br>
    7.1 [L'équipe SCRUM](#équipe-scrum)<br>
    7.2 [Le scrum master](#scrum-master)<br>
    7.3 [Le product owner](#product-owner)<br>
    7.4 [Les stakeholders](#stakeholders-parties-prenantes)<br>
    7.5 [Les business owners](#business-owners)<br>
8. [Les user stories](#une-user-story-cest-quoi-)<br>
    8.1 [INVEST](#vérification-invest)<br>
    8.2 [Les critères de validité](#une-us-est-composée-de-trois-élément-3c)<br>
    8.3 [Priorité des user stories](#priorité-des-users-stories)<br>
    8.4 [Le conditions de satisfaction](#condition-de-satisfaction-cs)<br>
    8.5 [Les sous-tâches](#%EF%B8%8F-définition-des-tâches)<br>
9. [Les biens livrables SCRUM](#biens-livrables-atréfacts-de-la-méthode-scrum)<br>
    9.1 [Le diagramme des concepts fondamentaux](#diagramme-des-concepts-fondamentaux-)<br>
    9.2 [Le glossaire](#glossaire-)<br>
    9.3 [La liste des acteurs et des intervenants](#-liste-des-acteurs-et-des-intervenants-)<br>
10. [Les 12 principes AGILES](#les-12-principes-agiles-)<br>
11. [Les tests du produit](#tests-du-produit)<br>

***

## :coffee: Tu as passé ton examen d'analyse d'applications grâce à ScrumSensei ? [Ça vaut bien un petit café non](https://paypal.me/obrassard) ? :smile:

##  1. Sprint 0 / Grooming : préparation du backlog de produit

Le backlog de produit est une liste de [User Stories](#une-user-story-cest-quoi-) classées en **ordre de priorité (selon la demande du [PO](#product-owner))**  et représentant **l’ensemble des fonctions à implémenter afin de répondre au besoin du client**. Le backlog de produit est modifiable tout au long du processus.

Les éléments les plus prioritaires devraient avoir plus de détails (description, conditions, storypoints), tant qu’une US ne fait pas partie du sprint courant elle peut être modifiée ou reclassée.

On veut avoir plus de user story de prête que ce qu’on pense compléter dans les [sprints](#3-sprint-) actuels. On souhaite toujours avoir 3 à 4 sprints d’avance (calculable par la vélocité moyenne)

**Étapes et artéfacts**

💡 [Voir la section artéfacts](#biens-livrables-atréfacts-de-la-méthode-scrum)

1. **Grooming** (maintenance du backlog de produit)
  - Fractionnement des épics / [User-stories]((#une-user-story-cest-quoi-)
  - Préparation des US pour les prochains sprint
  
  *Pourquoi faire du grooming?*
    - Être prêts pour la planif de sprint
    - Clarifier et comprendre les règles d’affaires et les conditions de satisfaction
    - Valider que nos priorités sont à la bonne place

2. **Analyse des besoins**, analyse textuelle → Rencontre avec le client
3. Préparation du [diagramme de **Concept Fondamentaux** (CFC)](#diagramme-des-concepts-fondamentaux-)
4. Préparation du [**Glossaire**](#glossaire-)
5. Définission des [*Acteurs* et de leurs rôles](#-liste-des-acteurs-et-des-intervenants-)

**Le sprint 0 comprend aussi l’organisation de l’équipe scrum elle même**

  - Composition de l’équipe
  - Choix et installation des logiciel
  - Choisir la durée des sprints
  - Préparer une liste de tâche générique
  - Défniir qui est le Scrum master
  - Définir la vélocité moyenne de l'équipe, c'est à dire le nombre de [`story points`](#Étapes-de-la-planif-de-sprint) complétés en moyenne par l'équipe

## 2. Planif de Sprint

- Présentation au [PO](#product-owner) des premières user stories du backlog, pour confirmer l’approbation des [conditions de satisfaction](#condition-de-satisfaction-cs) par le PO et confirmer leur importance au yeux du client.

- Sélection des user stories à inclure dans le **backlog de sprint**, c’est à dire la liste des user stories qui devront être complétées dans la durée du sprint et leur assignation entres les membres de l’équipe

- Définition de l’objectif du sprint

**Étapes de la planif de sprint:**

1. Lire les US une par une en présence du PO
2. Voter les poids (story points) et argumentations
  > Les storypoints sont des notes (1, 2, 3, 5, 8, 13 ...) assignées à chacunes des US, qui permettent de les comparer entre elles, une US de 5 serait en théorie plus complexe qu'un US de 3 
3. L'équipe fait un second vote si nécéssaire pour évaluer le nombre de storypoints, si l'équipe n'arrive toujours pas a un concensus, on choisi le pointage le plus élevé parmis les votes 
4. Construire le backlog de sprint
5. Définir l’objectif de sprint
6. Définition des [sous tâches de chacunes des US](#%EF%B8%8F-définition-des-tâches)


## 3. Sprint 🏃

- Période fixe durant laquelle le développement des user-stories est effectué et après laquelle nous devrions avoir un prototype potentiellement livrable (incréments au produit)

- On ne développe cependant seulement que les fonctionnalités approuvées par le PO, seulement celle qui ont de la valeur ajoutée

- Une fois le sprint démarré, les users-stories en cours ne peuvent être modifiées.

- La gestion et réparation des bugs devrait être intégré dans les sprints ( parce que ça prend beaucoup de temps )

## 3.1 La mêlée quotidienne (à chaque jour pendant les sprints)
Courte rencontre quotidienne entre les membres de l’équipe, faite **debout**, pour faire le point

- Présenter le travail **complété** vs le travail restant
- Précision des objectifs de la journée et des difficultés rencontrées

    1. Qu’est-ce qui a été fait ?
    2. Qu’est ce qui va être fait?
    3. Quels sont les obstacles rencontrés ?

## 4. Revue de Sprint
- Démonstration des fonctionnalité développées au PO pour qu’il puisse voir ce qui à été réalisé. **Montrer les US** **TERMINÉES** **seulement.**

- Le PO vérifie que les US ont bien été respectées (conditions de satisfactions)

- Revue de l’objectif de sprint

- Le PO approuve, commente ou rejette les US du backlog de sprint terminées *(Celles qui ne sont pas acceptées retournent dans le backlog de produit)*


> **💡 Qu’est-ce qu’on peut définir comme terminé ?**
- Pour un sprint : Terminé à la date de fin de sprint défini
- Pour une User-Story : Lorsqu’elle a été complètement programmée et testée
- Pour une tâche : Lorsque la tâche est complète à 100%

***

## 5. Rétrospective de Sprint

Ça ne touche jamais le projet en tant que tel, mais **seulement la gestion d’équipe..** Donc les logiciels, les mode de fonctionnement, les durées, horaires, etc..

    1. Qu’est-ce qui c’est bien passé durant le sprint ?
    2. Qu’est-ce qui à mal été dans le sprint ?
    3. Qu’est-ce qu’on doit améliorer pour le prochain sprint ?

À l'aide de ces 3 questions, l'équipe établi un **plan d'amélioration**

### Méthode en 5 points

Une autre stratégie consiste à regrouper des idées de chacun des membres, dans 5 catégories (souvent avec des notes autocolantes) concernant la gestion d'équipe avant d'établir un plan d'action :

    1. "Plus de ..." (More of ...)
    2. "Commencer à ..." (Start doing ...)
    3. "Arrêter de ..." (Stop doing ...)
    4. "Moins de ..." (Less of ...)
    5. "Continuer de ..." (Keep doing ...)

## 6. Sprint de release
- Fournir un produit fonctionnel à l’utilisateur

- Créer ou mettre a jour le guide utilisateur (patch note)

- S’assure que les données de la version précédente fonctionnent toujours dans la nouvelle version et adapter le modèle de donnée en production au besoin

- **On ne devrait pas faire de nouveau développement dans le sprint de release**

**Tests à affaire avant la release (au minimum) :**
  - Tests de regression
    - Est-ce que ce qui fonctionnais fonctionne toujours ?
  - Tests d'intégration
    - Les nouveaux ajouts fonctionnent avec les autres données ?
  - Tests de charge
    - Le système peut-il supporter la quantité de données potentielle et le nombre de personnes qui utiliserons l’application en même temps ?
    
💡 Voir la [section sur les tests](#tests-du-produit)

----------

# Rôles au sein du procéssus SCRUM

## Équipe Scrum

Équipe composée de 5-9 membres multifonctionnels


  **Rôle de l’équipe scrum**
  - Doit répondre des décisions
  - Tous les membres doivent assister à toutes les activités
  - Elle est auto-organisée sur une base volontaire(qqun se porte volontaire pour faire une tâche)

    **Qualités de l’équipe scrum**
    - Intensément collaborative
    - Constructive dans sa critique
    - Créative et innovatrice
    - Responsable et redevable
    - Orienté vers la valeur d’affaire
    - De dimension réduite
    - Stable, dans le meilleur des mondes
    - Auto organisée
    - Soutenue par la direction
    - Engagée a respecter les objectif
    - Confiance mutuelle des membres
    - Les décisions sont prises en équipe


## Scrum Master
- Ce n’est pas un chef de l’équipe, mais un membre dédié de l’équipe
- Il s’assure que les principes scrum sont respectés au sein de l’équipe
- Fait le suivi des accomplissements
- Oriente les discussions vers les objectifs

    **Qualités**
    - PR, Leader positif
    - Gardien du processus
    - Retirer les blocages
    - Évalue le progrès de l’équipe
    - Protège l'équipe des interférences
    - Aide le client a maximiser ses investissement
    - Agit comme coach et mentor
    - Commis au processus
    - Capacité de facilitation
    - Proactif et discipliné
    - Agit avec assurance
    - Habilité à prendre des décisions parfois difficiles
    - Enthousiaste


## Product Owner
- Représentant du client présent, Intermédiaire entre l’équipe de développement et l’entreprise
- Membre à part entière de l’équipe Scrum dont la responsabilité principale est de définir un produit qui apportera le maximum de valeur métier aux utilisateurs
  - Définit et priorise les spécifications et les dates limites
- Souvent “prêté par les entreprises clientes”
- Obtient l’information des utilisateurs et des parties prenantes
- Accepte ou rejette les travaux et change au besoin les priorités

    **Qualités**
    - Très bon communicateur
    - Expert dans son domaine d'affaires.
    - Facilité à visualiser des idées et concepts
    - Déterminé et à l’autorité de prendre des décisions
    - Proactif et discipliné
    - Habilité à gérer vers le haut et transversalement
    - Disponible pour son équipe.
    - Respectueux de l’équipe et du processus
    - Flexible
    - Joueur d’équipe
    - Bon négociateur

## StakeHolders (parties prenantes)
Ce sont les parties prenantes sont l'utilisateur final ou l'utilisateur cible pour lequel le produit est développé, comme ce seront eux qui utiliserons le logiciel leur opinion est très précieuse.


- Fournisse une rétroaction importante
- Proposent de nouvelles idées
- Définissent les points importants
- Ils peuvent participer à :
  - La planif de sprint
  - La rencontre de démo
  - La rencontre de rétrospective

## Business Owners
- Fait partie des StakeHolders
- En gros c’est celui qui paye
- Le propriétaire d'entreprise joue le rôle de **sponsor** dans un projet, alors il cherchera le meilleur intérêt de l'entreprise. Il s'appuie sur le Product Owner pour fournir la capacité de l'équipe à gérer le travail, et joue le rôle d'acteur principal et de prise de décision. Il joue un rôle important dans la carte d'organisation, car il représente à la fois le parrainage du produit et guide le Product Owner dans ce dont l'entreprise a besoin.

----------

# Une User-Story, c'est quoi ?

**Definition :**
Une tâche de haut niveau sur un plan de projet, un bien livrable de la méthodologie Agile, une exigence fonctionnelle de l’application à développer


## Vérification INVEST
Une bonne User Story (US) devrait respecter les critères de l'acronyme INVEST:

| Critère | Explication |
| --- | --- |
| **Indépendante**   | *Ne doit pas dépendre des autres US*                                                                       
| **Négociable**     | *Les critères peuvent être modifiées entre les sprints.*                                                                                                   |
| **Valeur Ajoutée** | *La user story doit représenter un incrément réellement utile pour l'utilisateur final ou du point de vue du client.* |
| **Estimable**      | *On doit être capable d’évaluer le temps nécessaire et la complexité du développement de la US*.<br><br>**Si elle est trop grosse elle ne peut pas être évaluée**.<br><br>De plus, les **conditions de satisfaction** doivent être suffisamment précises et restreintes pour que l'équipe de développement puisse quantifier l'effort d'implémentation, sinon dans l'absolu, du moins de la situer relativement aux user stories précédement développées. |
| **Short**          | *Une US devrait pouvoir être intégrée à un sprint de 2 personnes de 2 à 3 semaines* |
| **Testable**       | *Il doit y avoir une ou plusieurs conditions de satisfactions qui nous permettrons de tester le fonctionnement du code, et pour voir si les règles de métiers sont respectées* |

💡 **Lorsque le récit utilisateur ne respecte pas les conditions INVEST, c’est souvent parce que cette dernière peut-être fractionnée en plusieurs plus petite US**

## Une US est composée de trois élément (3C)

| Critère | Explication |
| --- | --- |
| **Carte**  | Brève description (*En tant que... je veux .. afin de..*) |
| **Conversation**  | Information plus détaillée, discussion avec l’équipe, le PO et les testeurs |
| **Confirmation**  | **Partie la plus importante** : Comprend les *conditions de satisfaction*, c'est à dire les critères de test pour assurer la complétude et l’acceptation de la US. Les condition de satisfaction doivent être ***quantifiable et précises*** |


## Priorité des Users-Stories

Dans le backlog, les users-stories devraient êtres classées en priorités selon plusieurs critères :

1. L’importance de la fonctionnalité (au yeux du client)
2. Le niveau de difficulté
3. La fréquence des cas (si une action n'est effectué que quelque fois au sein de l'application, elle est moins prioritaire)

---

## Condition de satisfaction (CS)
- Ensemble de conditions que la US doit satisfaire pour être 100% terminée
- En général, fourni par le PO ou le Client
- Ce ne sont pas des tests
- Pour une bonne CS :
  - la CS définit une **intention** plutôt qu’une solution
  - indépendant de l’implémentation
  - idéalement au «Je»
  - une attention particulière au verbe utilisé (devoir/pouvoir)

---

## ☑️ Définition des tâches
Lors d'un sprint, on doit séparer les users stories en sous-tâches
Exemple de tâches :

> Let's imagine a story "A new customer can sign up for the web site so that he can access it in the future"
>
> The tasks could be :
> - Collect personal infos (first name, last name, email address, password)
> - Validate email and password
> - Make sure that the account does not exist already
> - Create the account and go back to homepage.


### S.M.A.R.T.
Comme pour les user stories, les tâches doivent respecter certaines conditions :

**Specific (Spécifique)**
La tâche doit être assez spécifique afin que tous les membres de l’équipe comprennent ce qu’il y’a à faire. Ceci nous aide aussi à ce que l’ensemble des tâches ne se chevauchent pas et aide les gens à comprendre la contribution de la tâche dans la story. **Elles doivent aussi être idépendantes et testables**

**Measurable (Mesurable)**
“Comment la tâche peut être considérée comme terminée?”, c’est la question qui nous permet de mesurer une tâche. L’équipe doit s’accorder sur ce que la tâche veut dire et qu’elle fait bien ce qu’elle est supposée faire.

**Achievable (réalisable)**
Le propriétaire de la tâche doit s’attendre à être en mesure de réaliser une tâche. Dans une équipe, n’importe quel membre peut demander de l’aide sur quoi que ce soit du reste de l’équipe. Ceci implique bien sur que l’équipe est à la hauteur pour faire le travail.

**Relevant (Pertinent)**
Chaque tâche doit contribuer à la réalisation de la story. Elle doit être assez pertinente, et bien qu’elle est écrite pour le bénéfice des développeurs, le client peut toujours demander de l’explication et de la justification pour chaque tâche.

**Time-Boxed (durée limitée)**
La tâche doit avoir une durée limitée et spécifiée. Sans forcément avoir une durée en heure ou jours, il doit y avoir une durée connue afin que les développeurs puissent demander de l’aide quand cette durée est dépassée. Si une tache est plus compliquée que prévu, l’équipe doit savoir si il faut diviser la tâche, remplacer les propriétaires ou faire autre chose pour finaliser la tache.

----------

# Biens livrables (atréfacts) de la méthode SCRUM

> Les biens livrables sont des documents ou artéfacts à produire au cours de la méthode scrum

## Diagramme des concepts fondamentaux :

📘  C’est une vision de **haut niveau** qui sert à dialoguer avec le client pour obtenir un consensus sur les concepts clés qui font partie de l’application

*Chaque concept doit avoir une responsabilité , qui est une sorte de contrat ou d'obligation à respecter.. Un concept devrait avoir* ***au moins une*** *responsabilité, mais quand même en nombre limité.. Si elle comporte plus de 5 responsabilités, elle doit être subdivisée..*

**Verifications :**

![](https://d2mxuefqeaa7sj.cloudfront.net/s_C25AC55923765D39AD057A188E8B081D1F752EAB8086EC0DB75AED579C039EB0_1508801706414_Capture+decran+2017-10-23+a+19.34.56.png)

## Glossaire :

📘 Document qui permet à l’équipe de développement de s’entendre sur les définitions des concepts clés de l’application (selon ce qu’ils sont pour les clients) afin que tous les membres de l’équipes parlent de la même chose soient au courrant de ce que chacun des concept représentent réellement.

Le glossaire devrait au moins contenir tous les concepts présents dans le diagramme CFC. *Les synonymes devraient aussi être identifiés ainsi que les numéros de lignes de référence (pour retrouver l’explication du concept dans les documents)*


## 👥 Liste des acteurs et des intervenants :

📘 Liste des rôles joué par les entités qui interagirons avec l’application. Un acteur peut consulter et/ou modifier l’état de l’application en émettant et/ou recevant des “messages” (données). Nous permet de dresser le portrait des utilisateurs éventuels de l’application.

Un acteur peut être un **utilisateurs humains directs** (avec des 👐 ) ou une **application externe**

**Les différents niveaux des acteurs :**

| Niveau | Exemple |
| --- | --- |
| **Niveau stratégique** : Intéragit rarement avec les données, reçoit des rapports pour l’analyse et la gestion de l’entreprise      | Haute direction       |
| **Niveau tactique** : Interagit parfois avec les données, mais reçoit plus généralement des rapports pour analyse                   | Cadres intermédiaires |
| **Niveau opérationnel** : Intéragit couramment avec les données, responsables de l’ajout et de la modification des entrées de la Bd | Personnel de bureau   |

----------

## Les 12 principes AGILES :
> Comme SCRUM est une méthode AGILE, il faut se rappeler qu'elle se fonde sur les douzes principes agiles énoncés par le [*manifeste AGILE*](http://agilemanifesto.org/iso/fr/manifesto.html) :

1. Notre plus haute priorité est de **satisfaire le client** en livrant rapidement et régulièrement des **fonctionnalités à grande valeur ajoutée**.
2. **Accueillez positivement les changements** de besoins, même tard dans le projet. Les processus agiles exploitent le changement pour donner un avantage compétitif au client.
3. **Livrez fréquemment un logiciel opérationnel** avec des cycles de quelques semaines à quelques mois et une préférence pour les plus courts.
4. **Les utilisateurs ou leurs représentants et les développeurs doivent travailler ensemble** quotidiennement tout au long du projet.
5. Réalisez les projets avec des **personnes motivées**. Fournissez-leur l’environnement et le soutien dont elles ont besoin et faites-leur confiance pour atteindre les objectifs fixés.
6. La méthode la plus simple et la plus efficace pour transmettre de l’information à l'équipe de développement et à l’intérieur de celle-ci est **le dialogue en face à face**.
7. **Un logiciel opérationnel** est la principale mesure d’avancement (Mesurer l’avancement en termes de fonctionnalités).
8. Les processus agiles encouragent un **rythme de développement soutenable**. Ensemble, les commanditaires, les développeurs et les utilisateurs devraient être capables de maintenir indéfiniment un **rythme constant**.
9. Une attention continue à l’**excellence technique** et à une **bonne conception** renforce l’agilité.
10. La simplicité – c’est-à-dire l’art de **minimiser la quantité de travail inutile** – est essentielle.
11. Les meilleures architectures, spécifications et conceptions émergent d’**équipes auto-organisées.**
12. À intervalles réguliers, l'équipe **réfléchit aux moyens de devenir plus efficace**, puis règle et modifie son comportement en conséquence.

***

# Tests du produit
> Il est essentiel, au cours du processus de développement, de tester le produit développé. Il existe de nombreux types de test à effectuer :

## Tests fonctionnels

**Objectif :** Confirmer l’acceptation d’une User Story en vérifiant que les fonctionnalisés répondent aux besoins. Les tests devraient toujours inclure plusieurs scénarios pour chaques cas:

**Classe d’équivalence / Cas limites**
Les classe d’équivalence nous évite de tester plusieurs fois pour rien avec des valeurs qui sont dans le même “range” de données

Test qui devraient être faits au minimum :
$$n$$ étant une condition

1. Test qui respecte la condition à 100 %
2. $$x>n$$     *Exemple : Le client est inscrit depuis plus de 2 ans*
3. $$x<n$$     *Exemple : Le client est inscrit depuis moins de 2 ans*
4. $$x=n$$     👉 **Cas limite** → *Exemple : Le client est inscrit depuis 2 ans*

Lors de exécution des tests on devrait toujours détailler les tests qui ont échoué et documenter le résultat réel qu’on a obtenu

**Pour les écrire**

- Identifier les conditions de satisfaction visées par le test
- Identifier les pré-conditions
- Identifier les étapes et le résultat attendu
- Indiquer les données/classes d’équivalence à utiliser
- **Pré-conditions :**
  - Tout ce qu’on s’attend à ce qui soit déjà là de base et qui soit déjà fait
  - Les données dans les préconditions doivent respecter le scénario
  - Sous entend que les données sont valide pour le test en question
  - Exemple : « *J’utilise le client Bernard Gendron qui possède un code-postal valide.*»

## Autres types de test :

**Test unitaire** :
    Procédure permettant de vérifier le bon fonctionnement d'une méthode précise du code

**Test d’intégration** :
    Précédée des [tests unitaires](https://fr.wikipedia.org/wiki/Test_unitaire). Chacun des modules indépendants du logiciel est assemblé et testé dans l’ensemble.

**Test de régression** :
    Ensemble de tests d’un programme préalablement testé, après une modification, pour s’assurer que des défauts n’ont pas été introduits ou découverts dans des parties non modifiées du logiciel

**Test d’acceptation** :
    Visent à assurer formellement que le produit est conforme aux spécifications

**Test de performance** :
    Vérifient les performances de l’app pour un grand nombre d’utilisateur ou de requêtes

**Test de stress** :
    Vérifie la fiabilité de l’application en la testant dans des conditions qui excède les limites de opérations normales

**Test d’utilisabilité** :
    Méthode permettant d'évaluer un produit en le faisant tester par des utilisateurs<br>Permet d’observer directement la façon dont l’utilisateur se sert d’une application et ainsi identifier concrètement les véritables difficultés qu’il rencontre

**Test de compatibilité** :
    S’assurer de la compatibilité de l’application dans différents environnements

**Test de récupération** :
  Déterminer dans quelle mesure l’app est-elle capable de récupérer des accidents, des pannes matérielles et d'autres problèmes similaires.

## Les tests au sein du développement 

### Test Driven Development (TDD)

Le **test-driven development** (**TDD**) est une technique de développement de logiciel qui préconise d'écrire les tests unitaires avant d'écrire le code source d'un logiciel.

### Test Acceptance Driven Development (ATDD)
ATDD est étroitement liée au TDD. Il diffère par l'accent mis sur la collaboration développeur-testeur-client. ATDD englobe les tests d'acceptation, mais met l'accent sur la rédaction de tests d'acceptation avant que les développeurs commencent à coder.

### Behavior Driven Development (BDD)

Le **behavior-driven development** (ou **BDD**) est une [méthode agile](https://fr.wikipedia.org/wiki/M%C3%A9thode_agile) qui encourage la collaboration entre les développeurs, les responsables qualités, les intervenants non-techniques et les entreprises participant à un projet de logiciel. Cela permet aux développeurs de se concentrer sur les raisons pour lesquelles le code doit être créé, plutôt que les détails techniques…


### (╯°□°)╯︵ ┻━┻

## :coffee: Tu as passé ton examen d'analyse d'applications grâce à ScrumSensei ?<br>[Ça vaut bien un petit café non](https://paypal.me/obrassard) ?! :smile:
