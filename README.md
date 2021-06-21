# QuizTime

🔥 Quiz

Application ludique et interactive de quiz entre joueurs.
Le jeu doit être fun et pouvoir se partager entre amis pour comparer les scores !
Vous pouvez choisir librement la quantité de javascript que vous allez mettre pour dynamiser et fluidifier l'expérience de jeu.

📜 Scénarios utilisateurs minimum requis

- Graphisme
Je visualise l'application sur tous les formats d'écran sans scrollbar horizontale
L'application utilise tout l'écran de façon optimal sur tous les appareils
Le design est sobre, moderne, simple et intuitif

- Compte
En tant qu'utilisateur non connecté, je dois me connecter en saisissant seulement mon pseudo. Il n'y a pas de mot de passe.
Si le pseudo n'est pas connu dans la base de données, un nouvel utilisateur est créé et je suis connecté sur le profil.
 Si le pseudo est connu dans la base de données, alors je suis connecté et redirigé sur le quizz.
Liste des utilisateurs et des scores
En tant qu'utilisateur connecté, j'accède à la liste de tous les utilisateurs et de leur meilleur score

- Quizz
En tant qu'utilisateur connecté, je remplis les questions du quiz triées aléatoirement.
En tant qu'utilisateur connecté, je ne peux pas modifier ma réponse une fois qu'elle est choisie.
En tant qu'utilisateur connecté, ma réponse devient verte ou rouge quand je la sélectionne. Le bouton suivant s'active.
En tant qu'utilisateur connecté j'ai un temps limité pour répondre aux questions
En tant qu'utilisateur connecté, j'observe les résultats sous forme de tableau de scores + un graphique en barre

🔗Complexité minimale requise

- Backend
Il doit y avoir une base de données avec au moins une table users et questions
Une relation doit exister en MySQL entre users et questions
Prenez soin de bien structurer votre application PHP !

- Frontend
Le site doit être entièrement responsive
Au format mobile certains éléments disparaissent, changent de taille ou encore de position. Vous devez montrer que vous savez gérer les règles média CSS en fonction de la taille de l'appareil utilisé.
Le Javascript étant potentiellement important en fonction de vos choix, il est requis de faire des fonctions et de structurer un minimum votre application.


💡 Suggestions
Gestion des high scores et podium des meilleurs joueurs
.. Quoi d'autre ?! Remplissez cette partie !
