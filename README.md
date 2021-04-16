PROJET GAMEON :
Scénario :(rappel)
Embauchée comme développeuse Front-End junior dans la PME GameOn, spécialisée dans les conférences et les concours de jeux:

Suite au changement de responsable pour la réalisation d'un formulaire d'inscription, 
Je prend le relais faisant du shadowing du développeur principal, Erika, suivant son travail au quotidien.
Suite aux commentaires négatifs de la part de certains utilisateurs, La nouvelle page d'accueil et l'inscription aux concours
sont à simplifier. 

Jason mon prédecesseur avait commencé à travailler sur la structure HTML et le style CSS, sur la base de maquettes fournies.
Il a terminé la mise en page et le contenu de la page d'accueil ainsi que de la modale du formulaire.
Il a également ajouté le JavaScript pour le lancement de la maquette. 

A partir de ce qui est déjà réalisés: 

OBJECTIF : 

- complèter la partie Front-End, d'ajouter le code JavaScript manquant,
pour que le formulaire soit pleinement fonctionnel, en respectant les "issues".
sur le repo GitHub.
 Les issues décrivent ce qu'il reste à faire en respectant les conditions demandées:

CONDITIONS GÉNÉRALES:
- Travailler sur un repo GitHub forké ;
- Utiliser des fichiers séparés pour le HTML, le CSS et le JavaScript ;
- Toujours commenter mon code (décrire chaque fonction et chaque classe, 
  ainsi que les parties du code qui nécessitent plus de détails) ;
- Tester manuellement les fonctionnalités, les entrées de formulaire et l'affichage responsive. 

👩‍🎓️ Je dispose :
 - du lien vers le repo avec le code qu'il a déjà complété.
 - maquette

# Projet GameOn
1. Forkez ce repo ;
2. Il est conseillé d'utiliser VisualStudio Code et vous pouvez utiliser Docker, mais ce n'est pas obligatoire ;
3. Il n'y a aucune dépendance ;
4. Vous ne devez utiliser que du CSS personnalisé et du JavaScript pur, sans jQuery, Bootstrap ou autre librairie.

REQUIS:
TESTS MANUELS #5👍️
🕵‍♀️️VISUALISER ET TESTER L'INTERFACE UTILISATEUR DANS LES DERNIÈRES VERSIONS DE CHROME ET DE FIREFOX,
 AINSI QUE DANS LES VERSIONS MOBILE ET DESKTOP. CORRIGER LES ERREURS D'AFFICHAGE EXISTANTES.
TESTER TOUTES LES FONCTIONNALITÉS DES BOUTONS ET DES ENTRÉES DE FORMULAIRE (TESTER LES VALEURS CORRECTES ET INCORRECTES).
réalisé:
📨️Projet forké sur git, enregistré dans mon répo.
HTML et CSS passés au validateur, les 2 versions de navigateurs et correction des erreurs. 
Regrouper les données media query de même format, dans le css. 
Supprimer un "div" de trop en html pour permettre le bon fonctionnement du formulaire. 

👩‍🎓️J'ai dû retravailler les plus petites versions pour que soit adaptable à tous les écrans comme demandé ci-dessus 
le site doit être responsive. Avec un écran mobile minimum de 320px, on doit pouvoir remplir le modal.
📱️ bien que la version minimum mise en place sur certains éléments ici est 540px dans le css.🤷️
Corection de ce qui est refusé par le validateur et anotation en français. 
Des erreurs de syntaxe et autres corrigées dans le HTML .
JS réalisé testé, responsive. Les boutons du main-bar ne sont pas encore reliés à des sources par les liens mais peuvent
 devenir pleinement opérationnels par la suite. pur l'instant ils sont réactif au passage de la souris.

AJOUTER CONFIRMATION QUAND ENVOIE RÉUSSI #4👍️
🔉️APRÈS UNE VALIDATION RÉUSSIE, INCLURE UN MESSAGE DE CONFIRMATION DE LA SOUMISSION RÉUSSIE POUR L'UTILISATEUR.
 (EX. "MERCI ! VOTRE RÉSERVATION A ÉTÉ REÇUE.")👍️
 Validation des boutons du formulaire d'inscription réalisé. Des messages d'erreurs s'affichent au besoin.🚨️
👩‍🎓️ le message que j'ai choisi est : "Votre demande d'inscription a bien été enregistrée" que je trouve plus adaptée
 que le précédent message.
 
🚨️👍️
Des messages d'erreur spécifiques doivent apparaître sous l'entrée qui n'est pas correcte. 
Les messages d'erreur doivent s'afficher sous le champ de saisie associé. Exemples :

"Veuillez entrer 2 caractères ou plus pour le champ du nom."
"Vous devez choisir une option."
"Vous devez vérifier que vous acceptez les termes et conditions."
"Vous devez entrer votre date de naissance."
OK.Les messages suivants s'affichant qu'après la validation et le message d'erreur, 
👩‍🎓️Je précise que sur le formulaire est en anglais au niveau du choix de ville, donc au singulier et non pas au pluriel,🙋‍♀️️
 pour "quelle ville" dans un premier temps , cela peut toujours être modifié par la suite à la demande.(Aucune)
  
IMPLÉMENTER ENTRÉES DU FORMULAIRE #2 👍️
 1) LIER LES LABELS AUX ENTRÉES DANS LE HTML EN UTILISANT LES ATTRIBUTS "FOR" ET "ID" DANS LE CODE EXISTANT.
 CORRIGER LE CODE HTML QUAND NÉCESSAIRE.(ok fait)
(2) UTILISER DU JAVASCRIPT PUR (PAS DE JQUERY) POUR TERMINER LE FORMULAIRE :
OK.
👩‍🎓️Plusieurs erreurs sont présentes. la corection du formulaire pose problème dans certains champs qui
 ne sont plus fonctionnel après correction(exemple : remplacer toutes les class par id est une mauvaise idée),
 conaissant la spécificité de l'Id qui ne doit être attibué qu'à un seul élément... cependant j'ai ajouté des id
 pour cibler certains éléments travailler l'affichage dans le fichier modal.css
 .Le validateur désigne "label class.."comme étant une erreur, j'ai donc déplacé "for" dans la
 même ligne et remplacé par "label for", ce qui est accepté.

LE FORMULAIRE DOIT ÊTRE VALIDE QUAND L'UTILISATEUR CLIQUE SUR "SUBMIT"👍️
LES DONNÉES DOIVENT ÊTRE SAISIES CORRECTEMENT :👍️
(1) LE CHAMP PRÉNOM A UN MINIMUM DE 2 CARACTÈRES / N'EST PAS VIDE.
(2) LE CHAMP DU NOM DE FAMILLE A UN MINIMUM DE 2 CARACTÈRES / N'EST PAS VIDE.
(3) L'ADRESSE ÉLECTRONIQUE EST VALIDE.
(4) POUR LE NOMBRE DE CONCOURS, UNE VALEUR NUMÉRIQUE EST SAISIE.
(5) UN BOUTON RADIO EST SÉLECTIONNÉ.
(6) LA CASE DES CONDITIONS GÉNÉRALES EST COCHÉE, L'AUTRE CASE EST FACULTATIVE / PEUT ÊTRE LAISSÉE DÉCOCHÉE.
CONSERVER LES DONNÉES DU FORMULAIRE (NE PAS EFFACER LE FORMULAIRE) LORSQU'IL NE PASSE PAS LA VALIDATION.
"required" est utilisé que pour les conditions générales, le deuxième champs n'étant pas obligatoire.
👩‍🎓️le champs à remplir restant en rouge hachuré s'il n'est pas bien rempli, indique instantanément à l'utilisateur 
que le champs n'est pas correct. Utilisation d'"input invalid-valid" dans le css pour la validation directe
(4)Pour terminer le modal, l'éventualité qu'une valeur 0 puisse être insérée et qu'aucune ville ne puisse être cochée,
quand le client n'a participé à aucun autre autre concours, ni à aucun concours dans les villes citées,
 est maintenant possible.👍️

TODO : FERMER LA MODALE #1👍️
AJOUTER LA FONCTIONNALITÉ AU BOUTON (X)
Elle peut fermée en appuyant sur la croix en haut à gauche.

👩‍🎓️Outil personnels utilisés : Vs code
                            cours openClassroom, site du zéro, MDN w3 school et recherches sur internet; 
                            Js fiddle pour tester les codes js;
Conclusion: document interessant qui mériterait d'être développé dans son intégralité. 🤷️ 🔚️                          
                            
