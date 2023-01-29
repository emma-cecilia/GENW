# Cahier de charge du projet GENW (La Grande École Numérique du Web)
GENW va former des développeurs web sur des cursus de formation de 3 mois. Elle dispose de plusieurs sites répartis dans tout le pays. 
Afin de pouvoir gérer les apprenants, elle souhaite se doter d’un intranet qui sera à disposition à la fois des apprenants et du personnel (enseignant, administratif, 
technique) .

Les fonctionnalités attendues 
Page d’accueil 
Si l’utilisateur n’est pas connecté, il doit arriver sur une page d’identification lui 
demandant son adresse e-mail et son mot de passe. 
Une fois connecté, il arrive sur la page d’accueil qui comportera : 
- un lien vers la gestion de son compte : coordonnées, mot de passe, email 
- un lien lui permettant de se déconnecter 
- un accès vers les différents modules pour lesquels il a les droits d’accès 

Annuaire 
La GENC a besoin d’un annuaire qui répertoriera : 
• Le personnel de la GENC (enseignants, personnel administratif) 
• Les apprenants 
• Les contacts de l’école (sociétés, ministères, etc.) 
L’annuaire se présentera sous la forme d’une liste de contacts. On accédera par défaut à tous les contacts (système de pagination à prévoir) classés par ordre alphabétique. On devra pouvoir filtrer les contacts par catégorie, société, etc. et effectuer une recherche sur le nom, la société, un numéro, etc. 
En cliquant sur un nom, on accédera à ses informations : 
• Nom 
• Prénom 
• Date de naissance 
• Adresse 
• Numéro de téléphone • Email 
• Diplômes 
• Profession 
• Employeur 
• Notes : zone de texte qui permettra de mettre des annotations sur le contact 
Les contacts seront classés en catégories : société, ministère, apprenant, personnel (cette liste pourra évoluer). Pour chaque fiche, on devra pouvoir définir les droits d’accès à cette fiche : tout le monde, apprenants, personnel, partenaires… 
Seul le personnel de la GENC et l’administrateur du site pourront créer de nouveaux contacts et définir les droits d’accès. 
On doit également avoir accès à un trombinoscope pour chaque classe (photo et nom des apprenants). 

Gestion des absences 
Le personnel de l’école doit pouvoir gérer les présences et absences des apprenants. 
Pour cela, chaque jour la secrétaire indiquera pour chaque apprenant s’il a été présent ou non. Cette saisie doit se faire depuis une même page, et être gérée par demi-journée. 
Le personnel est le seul à avoir accès à cette partie. Il devra pouvoir rechercher un apprenant en particulier, auquel cas il verra le planning de la formation avec en rouge les demi-journées où l’apprenant a été absent. En cliquant sur une demi-journée, il pourra visualiser les détails de l’absence : raison, heure de départ et d’arrivée si absence « courte » (par exemple un aller-retour au Ministère) .
Ce système devra être dupliqué pour le personnel de l’école (professeurs et personnel administratif) .

Les fonctionnalitées à ajouter sont: le gestion de paie, la gestion de congés, la gestion du parc informatique.
Après le cahier de charge j'aurai le dictionnaire de données que je mettrai en place, le model conceptuel de données (MCD), le model logique de données (MLD), la création de la base de données, la création des tables, la maquette du site, le développement du site, les tests, le livrable.
