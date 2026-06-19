---
layout: page
title: Politique de confidentialité — Ma Cave
description: Politique de confidentialité de l'application mobile Ma Cave éditée par Pop Gestion. Conforme RGPD.
permalink: /macave/
---

**Éditeur :** Pop Gestion (SARL/EURL)
**Adresse du siège :** 17 rue Frédéric Koehler, 91330 Yerres, France
**SIRET :** 893 311 712 00010
**Contact :** [contact@pop-gestion.fr](mailto:contact@pop-gestion.fr)
**Délégué à la protection des données (DPO) :** [contact@pop-gestion.fr](mailto:contact@pop-gestion.fr)

**Dernière mise à jour :** 28 mai 2026

---

## 1. Objet

La présente politique décrit comment l'application mobile **Ma Cave** (ci-après « l'Application ») collecte, utilise et protège les données personnelles de ses utilisateurs. Elle s'applique à tout utilisateur qui télécharge, installe ou utilise l'Application.

L'éditeur de l'Application est **Pop Gestion** (ci-après « nous » / « l'Éditeur »), responsable du traitement au sens du Règlement Général sur la Protection des Données (RGPD — UE 2016/679).

## 2. Données collectées

L'Application collecte les catégories de données suivantes :

### 2.1 Données de compte utilisateur
- **Adresse email** (pour la création et l'authentification du compte)
- **Mot de passe** (stocké chiffré, jamais consulté en clair)

Ces données sont collectées au moment de la création du compte et sont nécessaires pour permettre la sauvegarde de votre cave dans le cloud et la synchronisation entre appareils.

### 2.2 Données de cave à vin
- **Caractéristiques des bouteilles** que vous ajoutez (nom, appellation, région, millésime, type, notes de dégustation)
- **Emplacement physique** (rangée/colonne dans votre grille de cave)
- **Photos d'étiquettes** que vous scannez pour identifier vos bouteilles
- **Historique** des bouteilles sorties (commentaires, dates, notes de dégustation)
- **Caves partagées** : si vous partagez votre cave avec d'autres utilisateurs, leur email associé au compte

### 2.3 Données techniques
- **Identifiant publicitaire Android (AAID)** : utilisé uniquement par notre partenaire publicitaire Google AdMob pour servir des publicités (voir section 5).
- **Logs techniques anonymisés** (erreurs de fonctionnement) pour améliorer la stabilité de l'Application.

### 2.4 Permissions appareil
L'Application demande les permissions suivantes (vous pouvez les révoquer à tout moment depuis les paramètres Android) :
- **Caméra** : nécessaire pour scanner les étiquettes de bouteilles
- **Photos / Stockage** : nécessaire si vous voulez ajouter une étiquette depuis votre galerie

L'Application **ne collecte pas** : votre localisation, vos contacts, votre microphone, vos SMS, votre historique d'appels.

## 3. Finalités et bases légales du traitement

| Finalité | Base légale RGPD |
|---|---|
| Création et gestion de votre compte | Exécution du contrat (CGU) |
| Sauvegarde et synchronisation de votre cave | Exécution du contrat |
| Identification IA de vos étiquettes de bouteilles | Exécution du contrat |
| Affichage de publicités | Consentement (formulaire UMP RGPD) ou intérêt légitime selon votre région |
| Sécurité et prévention de la fraude | Intérêt légitime |
| Amélioration de l'Application (logs anonymisés) | Intérêt légitime |

## 4. Sous-traitants et destinataires

Vos données sont traitées par les sous-traitants suivants, sélectionnés pour leur niveau de sécurité conforme au RGPD :

### 4.1 Supabase (base de données et authentification)
- **Société :** Supabase Inc., 970 Toa Payoh North, Singapore
- **Finalité :** stockage de votre compte et de votre cave
- **Localisation des données :** serveurs UE (Francfort, Allemagne)
- **Politique :** <https://supabase.com/privacy>

### 4.2 Google Gemini API (identification IA des étiquettes)
- **Société :** Google Ireland Limited, Gordon House, Barrow Street, Dublin 4, Irlande
- **Finalité :** analyse des photos d'étiquettes pour identifier la bouteille (nom, appellation, millésime)
- **Important :** les photos d'étiquettes sont transmises à Google **uniquement pour le temps de l'analyse**, ne sont pas conservées par Google selon les conditions de l'API Gemini (paid tier).
- **Politique :** <https://policies.google.com/privacy>

### 4.3 Google AdMob (publicités)
- **Société :** Google Ireland Limited
- **Finalité :** affichage de publicités interstitielles dans l'Application
- **Données partagées :** identifiant publicitaire Android (AAID), informations techniques de l'appareil
- **Personnalisation :** conditionnée à votre consentement via le formulaire RGPD (UMP) affiché au premier lancement de l'Application en zone UE/EEE
- **Politique AdMob :** <https://policies.google.com/technologies/ads>
- **Vous pouvez à tout moment** réinitialiser votre identifiant publicitaire ou refuser la publicité personnalisée depuis les paramètres Android (Paramètres → Confidentialité → Annonces).

### 4.4 Google Play Services
- **Société :** Google Ireland Limited
- **Finalité :** distribution de l'Application via le Play Store, services techniques Android
- **Politique :** <https://policies.google.com/privacy>

## 5. Publicités et consentement RGPD

L'Application affiche des publicités fournies par **Google AdMob**. Au premier lancement de l'Application, un formulaire de consentement RGPD (UMP — User Messaging Platform de Google) vous est présenté si vous êtes situé dans l'Union européenne, l'Espace économique européen ou le Royaume-Uni.

Vous pouvez choisir :
- **Accepter** les publicités personnalisées (basées sur vos centres d'intérêt)
- **Refuser** les publicités personnalisées (publicités non-personnalisées affichées à la place)
- **Gérer vos partenaires** (refus granulaire par partenaire publicitaire)

Si vous refusez tout traitement, les publicités ne s'affichent pas et l'Application reste fonctionnelle.

Vous pouvez modifier votre choix à tout moment depuis l'écran « Paramètres » de l'Application (« Gérer mon consentement publicitaire »).

## 6. Stockage local (sans transmission)

L'Application utilise une bibliothèque de stockage local (MMKV) pour mémoriser des informations sur votre appareil et accélérer l'affichage :
- Cache de votre cave (affichage instantané au démarrage)
- Préférences d'interface (thème, langue)
- État du consentement publicitaire

Ces données restent **uniquement sur votre appareil** et sont supprimées lorsque vous désinstallez l'Application.

## 7. Durées de conservation

| Donnée | Durée |
|---|---|
| Compte utilisateur (email + mot de passe) | Jusqu'à suppression du compte par l'utilisateur |
| Données de cave (bouteilles, historique) | Jusqu'à suppression du compte ou suppression manuelle |
| Logs techniques | 12 mois maximum |
| Photos d'étiquettes envoyées à Gemini | Non conservées (transmises pour analyse uniquement) |

Lorsque vous supprimez votre compte, **toutes vos données sont effacées de manière irréversible** sous 30 jours, à l'exception des données que nous serions tenus de conserver pour une obligation légale.

## 8. Vos droits

> 🗑️ **Vous souhaitez supprimer votre compte ?** Consultez notre page dédiée : [Suppression de compte et des données](/legal/macave/suppression-compte/).

Conformément au RGPD, vous disposez des droits suivants sur vos données personnelles :

- **Droit d'accès** : obtenir une copie de vos données
- **Droit de rectification** : corriger des données inexactes
- **Droit à l'effacement** (« droit à l'oubli ») : suppression de votre compte
- **Droit à la limitation** du traitement
- **Droit à la portabilité** : récupérer vos données dans un format structuré
- **Droit d'opposition** au traitement (notamment publicité)
- **Droit de retirer votre consentement** à tout moment

Pour exercer ces droits, contactez-nous à : **[contact@pop-gestion.fr](mailto:contact@pop-gestion.fr)**

Vous disposez également du droit d'introduire une réclamation auprès de l'autorité de contrôle de votre pays. En France, il s'agit de la **CNIL** (<https://www.cnil.fr>).

## 9. Sécurité

Nous mettons en œuvre les mesures techniques et organisationnelles suivantes pour protéger vos données :
- Chiffrement TLS de toutes les communications réseau
- Chiffrement des mots de passe (algorithme bcrypt côté Supabase)
- Authentification par JWT signé
- Accès aux données utilisateur restreint par Row-Level Security (RLS) côté base de données
- Rate-limiting sur les API sensibles pour prévenir les abus

Aucun système n'étant infaillible, en cas de violation de données, nous nous engageons à vous en informer dans les 72 heures conformément à l'article 33 du RGPD.

## 10. Enfants et mineurs

L'Application n'est pas destinée aux personnes mineures (moins de 18 ans), notamment en raison du contexte œnologique. Nous ne collectons pas sciemment de données de mineurs. Si vous estimez qu'un mineur nous a transmis des données, contactez-nous pour suppression immédiate.

## 11. Transferts internationaux

Certains de nos sous-traitants (Google) peuvent traiter des données hors UE. Ces transferts sont encadrés par les **Clauses Contractuelles Types** approuvées par la Commission européenne et/ou les certifications **Data Privacy Framework UE-US**.

## 12. Modifications

Cette politique peut être mise à jour pour refléter des changements de l'Application ou de la réglementation. La date de dernière mise à jour est indiquée en haut du document. En cas de modification substantielle, vous serez notifié au prochain lancement de l'Application.

## 13. Contact

Pour toute question concernant cette politique ou vos données personnelles :

**Pop Gestion**
17 rue Frédéric Koehler, 91330 Yerres, France
Email : [contact@pop-gestion.fr](mailto:contact@pop-gestion.fr)
SIRET : 893 311 712 00010

---

*Cette politique de confidentialité est conforme au Règlement Général sur la Protection des Données (RGPD — UE 2016/679) et à la loi Informatique et Libertés.*
