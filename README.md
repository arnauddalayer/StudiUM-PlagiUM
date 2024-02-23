# PlagiUM

## Présentation

PlagiUM est un outil permettant d’afficher les différentes adresses IP utilisées par un étudiant lors de la réalisation d’une activité StudiUM/Moodle (par exemple un examen en ligne).

## Mise en garde

Cet outil doit être utilisé avec toutes les précautions requises, et les données doivent être interprétées avec discernement :

- Dans certains cas, le même étudiant peut avoir légitimement eu plusieurs adresses IP (changement d’un poste qui posait un problème, activation d’une connexion VPN, etc.). Inversement, il serait difficile de prouver que plusieurs appareils ont été utilisés s’ils ont tous la même adresse IP d'après StudiUM/Moodle (même réseau domestique, utilisation d'une passerelle ou proxy, etc.).
- Même s’il permet de faciliter le processus de documentation d’une tentative de fraude, il est recommandé de faire analyser les données par un spécialiste, et de recouper les événements avec la tenue d’un journal lors de l’activité (ex. prise en note des noms et heures de sorties de la salle d’examen, par exemple pour aller aux toilettes).
- Cet outil ne se substitue pas aux autres mesures de sécurité qu’il convient de mettre en place lors des examens (surveillance physique, configuration d’une clé d’accès communiquée sur place, restriction d’accès par adresse IP si applicable, utilisation de Safe Exam Browser, etc.).
- Les adresses IP en vert sont des adresses IP de l’UdeM. Il convient de valider que ces adresses IP sont légitimes dans le cadre de l’activité (par exemple, les adresses IP des appareils connectés en sans-fil ne sont pas les mêmes que celles des postes de laboratoires informatiques).

## Utilisation

Pour faire l’analyse :

- Connectez-vous à votre compte StudiUM/Moodle et rendez-vous dans l’espace du cours de l’activité à analyser.
- Cliquez sur `Rapport`.
- Rendez-vous ensuite dans `Journaux`.
- Dans le menu déroulant `Toutes les activités`, sélectionnez celle pour laquelle vous souhaitez faire une analyse.
- Dans le menu déroulant `Toutes les actions`, sélectionnez Toutes les modifications.
- Cliquez sur `Consulter ces journaux`.
- Rendez-vous tout en bas de la page. Dans l’option `Télécharger les données`, sélectionnez le format `Javascript Object Notation (.json)`. Cliquez sur `Télécharger`.
- Sur la page de PlagiUM, cliquez sur `Choisir un fichier` et sélectionnez le fichier *.json* que vous venez de télécharger de StudiUM/Moodle.
- Cliquez sur `Traiter le fichier`.

## Remarques

- L’analyse des données que vous soumettez dans PlagiUM se fait localement dans votre ordinateur : les données ne sont pas transmises à notre serveur.
- Les rapports et journaux StudiUM/Moodle et PlagiUM contiennent des informations personnelles (nom, adresses IP, etc.) : ces documents ne doivent pas être diffusés ou partagés de manière inappropriée afin de respecter la confidentialité et la protection des données personnelles.
- Lorsque vous passez votre souris sur une adresse IP, une infobulle apparaît affichant l'heure associée à cette adresse IP. Cette heure correspond à la première fois que cette adresse IP a été enregistrée dans le rapport.
- Philosophiquement parlant, cet outil n'a pas été conçu pour être utilisé systématiquement pour chaque évaluation. Il devrait être utilisé uniquement en cas de soupçon de fraude. Son utilisation doit être considérée comme un dernier recours, et non comme une pratique standard.
- Cet outil n'a pas été conçu pour que l'enseignant prenne en charge lui-même le processus de traitement des fraudes. Tout cas de fraude suspecté doit être traité en respectant les règlements des départements, facultés ou universitaires. Il est important de suivre les procédures établies pour garantir l'équité et le respect des droits des étudiants.