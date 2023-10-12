# Interview Alix

## Points soulevés
- Alix fait directement remarquer un problème dans l'utilisation autonome et le système d'abonnement. Implication des parents important pour lui.
- Proposition d'ajout dans le lecteur d la possibilité de modifier les couleurs de fond (les fonds colorés aident les enfants dyslexiques). Et propose des polices sans empatements : Arial ou Cambria en 14 avec interligne fort.
=> penser à ajouter beaucoup de paramètres modifiables au lecteur d'histoires.
- Proposition à la fin de l'histoire que l'enfant réponde à une question assez générique: "Que penses-tu que le héros/l'héroïne ressent à la fin de l'histoire?" etc.
- Proposition d'une notification paramètrable fait aux parents pour les notifier régulièrement de l'avancée de la lecture de l'enfant, du nombres d'histoires afin qu'ils ou elles puissent engager une discussion avec l'enfant.
- Proposition d'un mode exercice en mode texte à trou qui permettrait de conjuguer un mot ou selection choix multiples vocabulaire adapté.
- Proposition d'ajouter une fonctionnalité d'impression de l'histoire qui plaît l'enfant (lien affilié avec un imprimeur à la demande?)

## User Journey

```mermaid
journey
    title Focus
    section Accueil
        Affichage: 4
    section Ma bibliothèque
        Affichage: 5
    section Lecteur
        Affichage : 2
    section Les avatars
        Affichage:3
    section Mes récompenses
        Affichage: 4
    section Mon Profil
        Affichage: 4
    section Contrôle Parental
        Affichage: 1
    section Ajouter un enfant 
        Affichage: 4
    section Se connecter
        Affichage: 3
    section S'abonner 
        Affichage: 3
```
# USER JOURNEY ANTONIETTA 

Antonietta souligne qu'il pourrait être plus intéressant pour un enfant de pouvoir tester la personnalisation des avatars avant de pouvoir demander au parent de s'abonner, sinon il risque de se désintéresser de l'application.
De même, il souligne que le fait de pouvoir avoir un aperçu des récompenses pouvant être échangées contre des points d'expérience pourrait augmenter l'intérêt des utilisateurs.
Il nous dit également de permettre au parent d'ajouter au moins un profil enfant pour lui permettre d'explorer l'application avant d'acheter, mais en bloquant le choix des préférences pour générer des histoires cohérentes avec les préférences de l'enfant.
Elle trouve que l'application n'est pas très intuitive sur certains points pour un jeune public, elle recommande d'ajouter des boutons qui permettent de revenir en arrière facilement.
Il nous fait part de sa crainte qu'un enfant puisse acheter l'application de manière autonome s'il connaît le code du téléphone et donc appliquer le contrôle parental.

Par rapport à cela:
- Nous avons modifié notre wireframe permettant à l'utilisateur de tester la personnalisation des avatars, en laissant certaines personnalisations libres et en lui demandant de s'abonner uniquement lorsqu'il souhaite choisir des skins ou accessoires bloqués par l'abonnement.
- De la même manière, nous avons rendu visible la page des récompenses, donnant un aperçu de la façon dont l'utilisateur pourrais échanger ces points d'expérience en choisissant de générer de nouvelles histoires à son guise.
- Nous avons inclus des boutons de retour à l'accueil, pour qu'il soit plus intuitif pour un enfant de pouvoir revenir en arrière, plutôt que de glisser vers la gauche.
- Nous essayons de comprendre comment intégrer un contrôle parental, pour éviter que l'enfant ne démarre l'abonnement à l'insu des parents.

```mermaid
journey
    title Focus
    section Accueil
        Dans la totalité: 5
    section Ma bibliothèque
        Dans la totalité: 5
    section Les avatar
        Subscription: 2
    section Mes récompenses
        Subscription: 2
    section Mon Profil
        Parent Control: 1
    section Ajouter un enfant 
        Subscription: 3
    section Changer de langue 
        Apprentissage: 5
    section Se connecter
        Facilité: 5
    section S'abboner 
        Intuitivité: 2
```