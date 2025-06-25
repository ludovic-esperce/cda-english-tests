# English quiz training

## Entraînement à la certification

Ce dépôt répertorie un ensemble d'exercices permettant de s'entraîner au questionnaire professionnel que le candidat aura lors de la certification (CDA m04).

Les modalités d'évaluation de ce questionnaire sont les suivantes :
- compétences évaluées :
    - Installer et configurer son environnement de travail en fonction du projet
    - Concevoir et mettre en place une base de données relationnelle
    - Contribuer à la mise en production dans une démarche DevOps
- contenu du questionnaire :
    - Le candidat étudie une documentation technique rédigée en anglais et répond à :
        - deux questions fermées à choix unique posées en français
        - deux questions ouvertes posées en anglais et amenant des réponses courtes, en rédigeant la réponse en anglais

> [!IMPORTANT]  
> Les exercices proposés ne suivent pas nécessairement ces modalités. Ils sont proposés à titre d'entraînement (et sont parfois plus complexes).

## Utilisation de ce dépôt

Afin de répondre aux questions vous pourrez faire un fork de ce dépôt.
Par la suite, vous pourrez modifier les fichiers markdown de questionnaire (tâchez de ne pas modifier les proposition de réponses) et pousser sur votre dépôt personnel vos modifications.

Vous allez rencontrer 2 types de questions :
- (MCQ) : multiple choice questions
Dans ce cas vous pourrez cocher ou décocher vos réponses.

Pour cocher une réponse, modifiez le markdown tel que :
```md
1. (MCQ) The answer to life, universe and everything.
- [x] 42
- [ ] Wait... what?
- [x] programming every day
```

- (Open-ended question)
Pour cette catégorie, vous pourrez ajouter votre réponse entre les balises **```text**.

Par exemple :
````md
```text
    My great and overly-inspired answer to life,
    universe,
    and the other things
    on multiple lines.
```   
````
