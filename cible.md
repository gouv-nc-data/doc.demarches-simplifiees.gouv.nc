---
description: "Cette page indique quels sont les trois publics concernés par l'utilisation de «\_Démarches simplifiées\_»\_: les usagers, les administrateurs (qui créent les formulaires) et les instructeurs."
---

# Cible

**demarches-simplifies.gouv.nc** est une application générique qui peut être utilisée par tout organisme exerçant des missions de service public pour une grande variété de démarches administratives.

## Cas d'usage

Les démarches dématérialisées peuvent concerner des particuliers, des entreprises, des associations ou des collectivités territoriales.

Il peut s'agir d'appels à projets, de procédures de création d'entreprise, de démarches d'enregistrement, d'inscription, de demande d'autorisation ou bien d'agrément ou des démarches internes à destination des agents publics…

**demarches-simplifies.gouv.nc** est adapté lorsque :

* L'usager doit transmettre des pièces jointes (jusqu'à 200 Mo par pièce jointe) ;
* Une trace juridique de la demande doit être conservée (horodatage et stockage des dossiers) ;
* L’organisme n'effectue aucune vérification (procédure déclarative) ;
* L'organisme vérifie seulement la complétude de la demande (arrêt possible à ce stade) ;
* La demande est instruite par plusieurs services d’un même organisme public ;
* La demande est instruite avec des partenaires publics (collectivités, agences…) ;
* L'instruction débouche sur la délivrance d’une attestation (éditeur d’attestation) ;
* Il existe déjà une application interne pour traiter les demandes (API permettant de sortir les données).

En revanche, l'application n'est pas l'outil le plus adapté dans les cas suivants :

* Enquête anonyme (obligation de se créer un compte, ce qui crée des frictions) ;

## Bénéfices

**demarches-simplifies.gouv.nc** a l'avantage d'être un outil :

* **Simple** : entièrement en ligne, sans installation ni paramétrage à effectuer, qui peut être utilisé directement par les services gestionnaires (modèle Typeform, Google Form).
* **Intégré à l’écosystème numérique public** : récupération automatique d’informations sur les demandeurs via API et NC Connect et récupération d'informations géographiques;
* **Collaboratif** : possibilité de co-construire et co-instruire les demandes pour simplifier la vie des usagers et des administrations, ce qui simplifie l'instruction des dossiers lorsque plusieurs organismes publics interviennent ;
* **Sûr** : plateforme homologuée Référentiel Général de Sécurité (RGS) et disponibilité constatée toujours supérieure à 99 % sur une période de 30 jours et accessible en ligne.

Les retours d'expérience montrent une réduction considérable des délais de traitement des demandes :

## Ce que nous ne faisons pas

### Différents rôles / niveaux d'instructeurs

Ajouter des rôles d’instructeurs avec des droits plus ou moins fins n'est pas quelque chose que nous souhaitons faire, car cela va à l'encontre de deux de nos principes :

* **Confiance** : nous voulons pousser les instructeurs, même à différents niveaux, à se faire confiance, et nous pensons que notre outil peut justement donner l'opportunité à une organisation de se réorganiser autour de la confiance. Rajouter des contraintes, même légères, à certains instructeurs, va à l'encontre de ce principe.
* **Absence de workflow** : un tel changement serait quelque part mettre en place un workflow, or nous ne voulons pas introduire de workflow, sous quelque forme que ce soit, afin de garder l'outil aussi générique que possible.

### Définir l'administration comme émettrice des e-mails automatiques qui sont envoyés depuis notre site

Changer notre adresse e-mail par la vôtre est problématique :

* L' e-mail émane de notre site, il est donc normal que l'expéditeur vienne de notre domaine, pour bien signifier à l'usager que le changement a eu lieu sur notre plateforme
* L' un des buts de notre site est de centraliser les échanges relatifs à un dossier au même endroit, en envoyant un e-mail depuis l'adresse de l'administration qui gère la démarche, l'usager pourrait alors répondre directement à cette adresse et les échanges seraient alors dispersés entre notre site et des boites e-mails.
