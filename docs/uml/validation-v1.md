# Validation de la V1 du MCD

Date de validation : 2026-03-10
Statut : VALIDE

## Portee

La version `mcd-v1.puml` est la base de reference metier pour le projet JDR.
Elle sert de support de conception et de presentation jury avant l'ouverture des travaux de V2.

## Points valides

- separation entre `ProfilPersonnage` et `PersonnageCampagne`
- un seul MJ par campagne
- un seul personnage joueur actif par utilisateur et par campagne
- personnage reutilisable via profil, avec progression reinitialisee par campagne
- snapshot du personnage pour preserver l'historique des campagnes
- PNJ et ennemis portes par la meme entite `PersonnageCampagne`
- univers conserve comme referentiel, sans surcharge locale de campagne
- un seul univers medieval exploite en V1
- kit de depart choisi par le MJ par classe pour la campagne
- carte de campagne persistante pour reprise de partie
- journalisation des choix et des consequences d'evenements des la V1

## Regle de travail

Toute evolution structurelle part maintenant de `mcd-v2.puml`.
La `V1` reste la reference validee tant qu'une nouvelle decision n'a pas ete formalisee.
