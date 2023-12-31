
![reacticon](https://github.com/LouisSappey/React-typescript-Workshop/assets/72028359/38db3070-4af3-434b-9c46-e45bfea29437)

# React-typescript-Workshop

Construire une Application de Connexion et de Liste de Tâches avec React, TypeScript, Flexbox, Grid & Routage

**Introduction à React et TypeScript**

* **Les Bases de React**
* Ressource : https://react.dev/blog/2023/03/16/introducing-react-dev
* **TypeScript dans React**
* Ressource : https://www.typescriptlang.org/docs/handbook/react.html



**Etape 0 : Installation et installation du projet
**Configuration de l'Environnement et du Projet****

Mise en Place de l'Environnement de Développement
Installer Node.js et npm.

* Créer un nouveau projet en utilisant Create React App avec le modèle TypeScript :
  ```
  npx create-react-app mon-app --template typescript
  ```
* Ressource : [https://create-react-app.dev/docs/adding-typescript/]()
* Une fois set up allez dans votre app:
* ```
  cd my-app
  ```
* Pour la lancer faite:
* ```
  npm start
  ```



**Etape 1: Mise en place de React Routter**
**Fondamentaux de React et Introduction au Routage**

* Composants Fonctionnels et Hooks
* Créer un simple composant fonctionnel.
* Ressource : [https://fr.legacy.reactjs.org/docs/hooks-overview.html]()

**Mise en Place du Routage**

* Installer React Router : npm install react-router-dom.
* Configurer BrowserRouter et Routes.
* Ressource : [https://www.codingthesmartway.com/7-steps-to-get-started-with-react-routing/]()
* Votre index.tsx devrait ressembler a peu près a ça:
<img width="609" alt="Capture d’écran 2023-11-27 à 10 10 59" src="https://github.com/LouisSappey/React-typescript-Workshop/assets/72028359/6e927957-ed24-4612-a21e-f0ed921226bb">



**Etape 2: Création de nos page Login**
**Construction des Composants de l'Application**


Nous allons directement faire notre page Login dans App.tsx
* Créer un composant Login avec un état pour le nom d'utilisateur et le mot de passe.
* Implémenter un gestionnaire de clic pour "se connecter"
* Un champ pour l'email et un champ pour le mot de passe
* Ressource pour la gestion des événements : [https://fr.legacy.reactjs.org/docs/handling-events.html]()
* Ressource pour votre page Login: https://www.publish0x.com/how-to-build-a-login-form-in-react-and-typescript/build-a-login-form-using-react-and-typescript-xwylgzl

* Si vous voulez ameliorez vos compétences en styles vous pouvez voirs les documentations plus bas.

**Call Api:**

Nous allons simulé une veritable connection avec une Api en ligne:

* Allez sur ce lien: https://reqres.in/
* Cliquez sur:
<img width="314" alt="Capture d’écran 2023-11-27 à 09 40 33" src="https://github.com/LouisSappey/React-typescript-Workshop/assets/72028359/797853e5-e837-4414-accd-751094d0226b">



* Puis utliser les informations donnez en faisant un call api sur l'url donner avec l'utilisateur donner et le mot de passe(Si vous voulez implementer la methode register libre a vous)

<img width="609" alt="Capture d’écran 2023-11-27 à 09 45 12" src="https://github.com/LouisSappey/React-typescript-Workshop/assets/72028359/37c6feea-5fc7-49ca-a819-a3302ca0217c">

Vous pouvez utiliser axios pour votre POST call api:
https://www.digitalocean.com/community/tutorials/react-axios-react





**Etape 3: Création de note TodoList**

Avant d'implementer note ToDoList nous voulons que lorsqu'on nous nous sommes connecter être redirigé à notre ToDoList.

Ajouter un dossier components et dedans crée une fichier ToDoList.tsx c'est ici que nous allons crée notre ToDoList.

Noublier pas d'export votre function pour pouvoir la récuperer.


<img width="162" alt="Capture d’écran 2023-11-27 à 10 17 01" src="https://github.com/LouisSappey/React-typescript-Workshop/assets/72028359/5b3c3567-2a64-4c5d-bf01-6fb7465f4bb4">

Votre React Router aussi devra etre changer :


<img width="678" alt="Capture d’écran 2023-11-27 à 10 31 39" src="https://github.com/LouisSappey/React-typescript-Workshop/assets/72028359/81767012-84d1-4e20-ae40-77a02ed8e40d">



**Implémentation de la Navigation**

* Navigation avec React Router
* Il faut donc ajouter la redirection a votre ToDoList quand la connection a réussi.
* Ressource : [https://www.programcreek.com/typescript/?api=react-router-dom.useNavigate]()

**Composants de la ToDoList**

* Créer les composants TodoList et TodoItem pour afficher les tâches.
* Implémenter la fonctionnalité pour ajouter et basculer l'état des tâches.
* Ressource pour l'état et le cycle de vie : [https://www.freecodecamp.org/news/react-component-lifecycle-methods/]()
* Il existe de nombreux packages de ToDoList si vous n'y arrivez pas sans n'hesiter pas a en utiliser un ! Vous pourez vous concentrer sur tous ce qui est flexbox et grid qui sont essentiels pour la construction d'une application/siteWeb responsive et beau !


**Documentations Utiles
Stylisation avec Flexbox et Grid**

* **Flexbox**
* Utiliser Flexbox pour styliser le composant Login.
* Ressource : [https://css-tricks.com/snippets/css/a-guide-to-flexbox/]()
* **Grid**
* Utiliser Grid pour organiser le composant TodoList.
* Ressource : [https://css-tricks.com/snippets/css/complete-guide-grid/]()

**Sauvegarder les élements avec localStorage:**

* C'est une lib très utiles qui permet de sauvegarder des élements sur votre app sans backend !

* Ressource:[ https://blog.logrocket.com/using-localstorage-react-hooks/]()

**Ressources Supplémentaires**

* **Flexbox**
* Flexbox Froggy - Un jeu qui aide à apprendre [https://flexboxfroggy.com/#fr]()
* **CSS Grid**
* Grid Garden - Un jeu pour apprendre le système de grille CSS. [https://cssgridgarden.com/#fr]()
* Tuto Log In / Register : [https://medium.com/@prabhashi.mm/create-a-simple-react-app-typescript-with-login-register-pages-using-create-react-app-e5c12dd6db53]()
