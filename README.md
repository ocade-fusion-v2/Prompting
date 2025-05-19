# Prompting
Bonnes pratiques &amp; Astuces du prompting


Utilisation de gpt 3.5 pour tester et améliorer le prompt et le modèle gpt-4  pour la génération de contenu.
Utilisation de gpt o3 deep search pour des génération de documents ou des demandent plus complexes avec des réflexions.
Attention modèle image applique un filtre visage donc on n'obtiendra pas deux fois le même visage.

0. Créer un "reset prompt" sous forme de **bullet points** et le stocker dans un fichier structuré (JSON par ex.).
1. Bien définir l'intention recherché. Présent dans Yourtext Guru (brief SEO). On peut aussi coller la SERP dans GPT-4 avec search pour déduire l'intention de la SERP.
2. Utilisation du plan du site SEO-TXL de Yourtext Guru pour la structure du site, il prend en compte les top termes et le brief SEO.
3. Rédiger le contenu optimisé pour le SEO avec les guides Yourtext Guru, utiliser les top termes autant que necessaires, les n-grammes 2 et 3 quand c'est possible. Pour les entitées nommées comme des marques, il faut rechercher des informations sur le sujet afin d'enrichir un contenu à reformuler.
4. Donner des contenus additionnel pour guider la réponse de l'IA. Lui dire qu'il doit prendre en priorité le contenu additionnel si il contient la réponse et ensuite la réponse de l'IA (information SERP ou présent dans le modèle).
5. Vérifier la qualité algorithmique de la page (Vitesse page, comportement utilisateur...)
6. Obtenir des backlinks avec la bonne ancre.
7. L'UX.UI doit correspondre à ce qu'on attend du type de tempplate (un produit doit ressembler à une page produit).
8. Donner des informations en entrées et des exmeples de ce qu'on attend en sortie.
9. Demander à l'IA de se noter sur 20 et de dire ce qu'elle pourrait améliorer. Boucler pour améliorer la sortie du prompt.
10. Demander à l'IA est ce que ça réponse est vrai et vérifiée. si elle répond non lui demander de vérifier en allant sur le web.
11. Dire à l'IA de ne pas inventer car je serai très déçu (l'IA veut faire plaisir).
12. Dire à l'IA qu'une réponse optimale est obligatoire car c'est une question de vie ou de mort. (L'IA va se concentrer sur la réponse).
13. Mettre les information les plus importantes en premier.
14. Utilisation du fan-out. Demander à l'IA de poser des questions pour mieux comprendre la demande et ainsi améliorer le prompt.
15. Utiliser des phrases courtes et explicites pour éviter les ambiguïtés.
16. Répéter une même idées sous plusieurs formes pour s'assurer que l'IA a bien compris et accentuer les points importants.
17. Utiliser des phrases directives comme "Tu vas devoir faire ça" ou "Tu dois faire ça", "Tu écris comme..." pour donner des instructions claires.
18. Demande d'écrire un contenu unique, sans plagiat.
19. Les modèles d'IA générative sont dit "alignés" c'est à dire qu'ils sont conçus pour respecter le langages des humains, leur faire plaisirs etc... Ils ont donc des biais dés leur conception.
20. Fixer un ton de voix (vocabulaire, niveau de familiarité...)
21. Fractionner les demandes pour plus de clareté avec des séparateur comme deux lignes de `###`
22. Utilise un corpus de textes afin que l'ia prenne le style de rédaction souhaité. Il est possible de demander à l'IA de générer la liste des spécificités de l'auteur afin de mieux comprendre le style.
23. Ne pas demander de ne pas utiliser tel ou tel mots car l'IA va en utiliser d'autre et à terme on tournera en rond. Utiliser vraiment un style de rédaction qui s'inspire d'un corpus de texte.


# Reformulation
1. Possibilité de générer plusieurs sites avec des contenus "reformulés" correctements avec des infromations suplémentaire et des styles de tons différents.
2. Pour reformuler un texte sur le diapo qui consite à demander une `synthèse séquentielle` et la travailler pour à la fin avoir quelque chose de propre et totalement différents parlant pourtant du même sujet à la base.


# Traduction
1. Ne pas traduire mot à mot mais utiliser un prompt qui immite un style new yorkais par exmeple car il y aura des expressions et des tournures de phrases qui ne seront pas les même.
2. Dire de rédiger comme les journaux intel ou intel anglais afin qu'il reprenne un style journalistique anglais.
3. Lui dire de lire les textes à voix haute afin de vérifier la fluidité du texte, l'ia aura tendances à utiliser des termes plus fluidie à l'oral qu'à l'écrit.

# Se faire assister par l'IA (GPT-03)
# Etude de marché
# Génération d'images
# Trouver des backlinks
# Analyse one page
# Support client
# Trouver meilleur prix
# Préparer un rendez-vous client
# Recommander des produits
# Revert prompting
