Fonctionnalité: Gérer la messagerie sur la page de tchat

  Scénario: Utiliser la messagerie en tant qu'étudiant ou bénévole sur desktop
    Étant donné que je suis connecté en tant qu'étudiant ou bénévole
    Lorsque j'accède à la page de tchat
    Alors je devrais voir une zone de saisie de texte pour envoyer un message

* Alors sur le côté gauche, je devrais voir toutes les instances de messagerie
* Alors je devrais voir une entrée de recherche pour rechercher un étudiant (pour le bénévole) ou un bénévole (pour l'étudiant) afin de l'inviter à discuter
* Alors chaque instance de messagerie devrait avoir une croix cliquable pour supprimer l'instance de messagerie

  Scénario: Utiliser la messagerie en tant qu'étudiant ou bénévole sur mobile
    Étant donné que je suis connecté en tant qu'étudiant ou bénévole
    Lorsque j'accède à la page de messagerie sur mobile
    * Alors je devrais voir une zone de saisie de texte pour envoyer un message

    * Alors je devrais voir une entrée de recherche pour rechercher un bénévole (pour l'étudiant) ou un étudiant (pour le bénévole) afin de l'inviter par message
	* Et lorsque je clique sur le profil recherché, cela devrait me rediriger vers la page de messagerie avec cette personne

    * Alors je devrais être redirigé vers une page distincte appelée "Messagerie" qui contient toutes les instances de messagerie
    * Alors chaque instance de messagerie dans la page "Messagerie" devrait être cliquable et pointer directement vers les messages échangés avec l'étudiant ou le bénévole
    * Alors chaque instance de messagerie dans la page "Messagerie" devrait avoir une croix cliquable pour supprimer l'instance de messagerie

    Note: La suppression de l'instance de messagerie ne devrait pas supprimer les messages eux-mêmes et ils devraient toujours apparaître lorsque la discussion est ré-ouverte.
