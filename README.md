[README.md](https://github.com/user-attachments/files/31332095/README.md)
# Mon Agenda du Sommeil

Une web app simple et gratuite pour observer son sommeil pendant 14 jours, repérer son rythme et prendre du recul sur ses nuits sans transformer le sommeil en performance.

## À quoi sert cet agenda ?

L’objectif est de noter chaque matin quelques informations simples sur la nuit écoulée afin de faire apparaître progressivement des tendances : horaires, durée estimée du sommeil, temps nécessaire pour s’endormir, réveils nocturnes, siestes, qualité subjective du sommeil et sensation de récupération au réveil.

L’agenda s’inspire des variables habituellement utilisées dans les agendas du sommeil, tout en restant accessible et agréable à utiliser au quotidien.

## Fonctionnalités

- saisie quotidienne simple sur téléphone ou ordinateur ;
- suivi sur 14 jours ;
- estimation du temps total de sommeil ;
- calcul du temps passé au lit ;
- calcul de la part du temps au lit passée à dormir ;
- suivi du temps nécessaire pour s’endormir ;
- suivi des réveils nocturnes ;
- curseurs de qualité subjective du sommeil et de récupération ;
- graphique veille-sommeil pour visualiser le rythme sur plusieurs jours ;
- bilan automatique rédigé dans un langage simple ;
- export CSV, JSON et bilan imprimable ;
- ajout possible sur l’écran d’accueil d’un iPhone comme une petite web app.

## Comment l’utiliser ?

Chaque matin, ouvre l’agenda et renseigne simplement ce dont tu te souviens de ta nuit, sans chercher une précision parfaite ni regarder l’heure pendant la nuit uniquement pour remplir l’outil.

L’intérêt apparaît surtout après plusieurs jours, lorsque les horaires, les variations et les différences entre les nuits commencent à devenir visibles.

Après 14 jours, le bilan permet de regarder l’ensemble avec davantage de recul.

## Installation sur iPhone

Ouvre l’agenda dans Safari, appuie sur **Partager**, puis choisis **Ajouter à l’écran d’accueil**.

L’icône de l’agenda apparaîtra ensuite avec les autres applications et permettra d’y revenir facilement chaque matin.

## Confidentialité

Les données saisies sont enregistrées localement dans le navigateur de l’appareil grâce au `localStorage`.

Elles ne sont pas envoyées automatiquement vers un serveur externe par cette web app.

Cela signifie aussi que supprimer les données du navigateur, changer d’appareil ou supprimer certaines données de Safari peut entraîner la perte de l’historique enregistré.

Pour conserver ou transmettre ses données, l’utilisateur peut utiliser les fonctions d’export disponibles dans l’agenda.

## Hébergement

Cette web app est statique et peut être hébergée gratuitement avec GitHub Pages.

Le fichier principal est :

```text
index.html
```

L’icône utilisée pour l’écran d’accueil est :

```text
agenda-sommeil-icon-v3.png
```

## Mise à jour sur GitHub Pages

Pour publier une nouvelle version, remplace simplement le fichier `index.html` dans le dépôt puis valide les modifications avec un nouveau commit.

Si GitHub Pages est déjà configuré sur la branche `main` et le dossier `/(root)`, aucune autre modification n’est nécessaire.

## Important

Cet agenda est un outil d’observation personnelle et ne constitue pas un diagnostic médical.

Si des difficultés de sommeil persistent, ont un retentissement important sur les journées ou suscitent une inquiétude, elles doivent être discutées avec un professionnel de santé.

## Projet

Créé pour **The Sleep Lab — Club Daily Reminder**.

L’idée derrière cet outil est simple : avant de chercher à améliorer son sommeil, il peut être utile de commencer par l’observer.
