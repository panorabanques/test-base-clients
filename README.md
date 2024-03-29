### Présentation

Nous souhaitons développer une application web permettant la gestion d'une base clients.

### Cet outils doit permettre :

    - de visualiser la liste des clients
    - de saisir un client avec civilité, nom, prenom, date de naissance, email, adresse postale
        - la saisie de l'adresse postale doit être facilitée par l'API publique: https://adresse.data.gouv.fr/
    - de supprimer ou modifier un client.
    - importer la base client depuis un format de votre choix (en ligne de commande ou  via l'écran)
    - exporter la base client dans un format de votre choix
    - d'afficher une synthèse des clients par département
    - Optionel: brancher une sécurisation de l'application et deux modes differents admin / reader only

### Conseils

    - Le temps de développement est libre (attention à ne pas y passer trop de temps - le but est de voir comment vous développez et pas de passer ce code en production - Ce n'est pas grave si le dev. n'est pas complet)
    - Le choix des technologies et des frameworks est libre (postgres, nodejs et reactjs conseillés mais pas obligatoire).
    - L'outils doit pouvoir supporter une volumétrie importante sans perte significative de temps de réponse.
    - Les validations se font cotés serveur et/ou client (choix à expliquer)

### Finalité

    - Il vous sera ensuite demander d'expliquer vos choix technologiques (si différents de ceux préconisés)
    - D'expliquer vois choix de developpements (Structure, Pattern, Tests mis en place)
