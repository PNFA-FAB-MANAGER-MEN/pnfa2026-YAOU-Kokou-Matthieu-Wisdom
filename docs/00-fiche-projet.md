# Fiche projet — Équipe 22

> Livrable L2 · Jalon J1 (samedi 29 août 2026) · validée par l'encadreur référent.
> Aucune fabrication n'est autorisée avant la validation de ce jalon.

## 1. Dispositif D22 : Détecteur de qualité de l'air et de temperature en fablab et en classe.

> une phrase pour le présenter à un chef d'établissement.

## 2. Besoins et bénéficiaires

- Les fabmanager et les eleves ont besoin en permanance de savoir la qualité de l'air ainsi que la temperature
- Le dispositif va etre installer dans les fablabs et les salles de classe


## 3. Objectifs d'apprentissage

Trois objectifs observables rattachés au programme officiel, chapitre cité.

1.
2.
3.

## 4. Description du dispositif

Ce que l'objet fait :
- mesurer la concentration du dioxyde de carbone dans l'air
- mesurer la temperature
- afficher trois niveaux d'alerte pour le CO2 et trois niveaux pour la temperature
- fonctionner hors reseaux

Ce que l'élève fait avec :
- exploite les données pour prendre des decisions

croquis ou esquisse annotée :
![ebauche visuel fait avec paint](medias/Ebauche%20visuele%201.png)

## 5. Architecture technique pressentie

Capteurs :
- un capteur de dioxyde de carbone à mesure infrarouge non dispersive, seul type fiable pour cet usage
- un capteur de temperature

actionneurs :
- les LEDS
- le buzzer 
- l'ecran

liaison:
- le PCB
- les cables

procédés de fabrication envisagés
(au moins trois procédés distincts, exigence ET-FAB-02) :
- l'impression additive
- l'impression soustractive
- traditionnel

application :
- fusion360
- VScode
- mblock

## 6. Rôle des élèves

Position sur le continuum POUR / AVEC / PAR et extension PAR décrite (exigence EP-03).

## 7. Ancrage réseau et implantation

Lab de rattachement :
 - CRIT
 - établissement 
lieu d'usage :
 - FabLabs
 - salle de classe

conditions matérielles de la salle :
 - salle hermétiquement fermer

## 8. Périmètre

| | Contenu | 
|---|---|
| Dans la v1.0 (Socle) | un boitier fonctionnel |
| En option (Avancé / Expert) | le controle de la temperature, de l'aeration et la notification automatique |
| Explicitement exclu | la reprogrammation via le reseau |

## 9. Risques et parades

| Risque | Type | Parade |
|---|---|---|
| defaut des capteurs | technique | test et redondence |
| insufisance de temps | calendrier | faire des prototypes tres simple |
| manque de competence| pédagogique | la sous traitance |

## 10. Budget matière estimé

Grandes masses en FCFA, au regard de la dotation (plafond indicatif : 60 000 FCFA) : 60 0000 FCFA

## 11. Licences et diffusion

- Licences choisies et motivation : Open source
- Accord de l'équipe pour la mise en avant réseau : poster sur github en public

## Exemptions demandées

- [ ] ET-FAB-06 (moulage) — justification :
- [ ] ET-MEC-01 (fonction motorisée) — justification :
