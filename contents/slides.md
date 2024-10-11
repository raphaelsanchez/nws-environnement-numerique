---
marp: true
title: Environnement Numerique
author: Raphael Sanchez
theme: nws
paginate: true
---

<!-- _class: cover invert -->
<!-- _paginate: false -->

# Environnement numérique

Acquérir les connaissances de bases de l'informatique nécessaires à la bonne compréhension de l'environnement de travail à la NWS

---

![bg right w:400](../assets/raphael.png)

## Raphael Sanchez

Développeur d'interface et Design System [@Indépendant](https://raphaelsanchez.design)

- 17 ans d'expérience
- Expert accessibilité
  et eco-conception
- Fan inconditionnel de CSS ♥️
- Intervenant depuis 2019

---

<!-- Slide 012-->
<!-- _paginate: false -->

# Ce que nous allons voir

1. Bref historique de l'informatique
2. Internet et le Web
3. Roles et particularités des outils numériques
4. Bonnes pratiques de sécurité
5. Les formats de fichiers et ordres de grandeur
6. Résolutions d'écran
7. Introduction aux bonnes pratiques du developpement web

---

<!-- _class: chapter invert -->
<!-- _paginate: false -->

# Bref historique de l'informatique

Brève introduction sur l'évolution des outils de calcul
jusqu'aux ordinateurs modernes

---

<!-- header: Historique de l'informatique-->

## Les origines du calcul

- **Boulier** : 3000 av. J.-C. outil utilisé pendant des millénaires
- **Règle à calcul** : 17e siècle, invention de William Oughtred

![bg right:40%](https://images.bibelotandco.fr/uploads/images/grand-boulier-vintage-en-bois-de-hetre_imgx1200_8987.jpg)

---

<!-- header: Historique de l'informatique-->

## L'ère des machines à calculer

- **Pascaline** : 1642, Blaise Pascal
- **Machine de Babbage** : 1837, Charles Babbage
- **Hollerith** : 1890, Herman Hollerith

![bg right:40%](https://www.echosciences-grenoble.fr/uploads/body_image/attachment/1005523249/image.png)

---

<!-- header: Historique de l'informatique-->

## Les premiers ordinateurs

- **ENIAC** : 1946, John Presper Eckert et John W. Mauchly
- **UNIVAC** : 1951, Eckert et Mauchly

![bg right:40%](https://cse.engin.umich.edu/wp-content/uploads/sites/3/2021/02/Burks-ENIAC-historic-scaled-1-749x1024.jpg)

---

<!-- header: Historique de l'informatique-->

## L'évolution des composants

- **Tube à vide** : 1946, ENIAC
- **Transistor** : 1947, John Bardeen, Walter Brattain et William Shockley
- **Circuit intégré** : 1958, Jack Kilby et Robert Noyce

![](https://as2.ftcdn.net/v2/jpg/00/23/47/07/500_F_23470715_AjENqTvpIpq6PiOLZzIx1IENqVEqarAa.jpg)

---

<!-- header: Historique de l'informatique-->

## L'avènement de l'informatique personnelle

- **Altair 8800** : 1975, Ed Roberts
- **Apple I** : 1976, Steve Wozniak et Steve Jobs
- **IBM PC** : 1981, IBM

![bg right:40%](https://www.depannagemac.com/blog/wp-content/uploads/apple1.jpg)

---

<!-- header: Historique de l'informatique-->

## L'ère d'Internet

- **ARPANET** : 1969, Département de la Défense des États-Unis
- **World Wide Web** : 1991, Tim Berners-Lee
- **Google** : 1998, Larry Page et Sergey Brin

---

<!-- header: Historique de l'informatique-->

## L'ère de l'informatique mobile

- **IBM Simon** : 1992, IBM
- **Blackberry** : 1999, Research in Motion
- **iPhone** : 2007, Apple

![bg right:40%](https://cdn.mgig.fr/2024/08/mga-3306a57b-w375-w1500-w750_accroche.jpg)

---

<!-- header: Historique de l'informatique-->

## L'ère du cloud computing

- **Amazon Web Services** : 2006, Amazon
- **Microsoft Azure** : 2010, Microsoft
- **Google Drive** : 2012, Google

---

## Les tendances actuelles et futures

- **Intelligence artificielle** : Deep learning, machine learning
- **Blockchain** : Cryptomonnaies, contrats intelligents
- **Quantum computing** : Calcul quantique
- **Réalité augmentée** : AR, VR, MR (Mixed Reality)
- **5G** : Réseau mobile de cinquième génération
- **IoT** : Internet des objets

---

<!-- _class: chapter invert -->

# Internet et le Web

Introduction aux protocoles de communication

---

<!-- header: Internet et le Web-->

## Internet

- **ARPANET** : 1969, Département de la Défense des États-Unis
- **TCP/IP** : 1983, Vinton Cerf et Robert Kahn
- **WWW** : 1991, Tim Berners-Lee et Robert Cailliau

---

<!-- header: Internet et le Web-->

## Différence entre Internet et le Web

- **Internet** : réseau mondial d'ordinateurs interconnectés
- **Web** : système de publication et de consultation de documents multimédias

---

<!-- header: Internet et le Web-->

## Achitecture du Web

- **Client** : navigateur web
- **Routeur** : connecte les réseaux
- **FAI** : Fournisseur d'Accès à Internet
- **Serveur DNS** : traduit les noms de domaine en adresses IP
- **Serveur Web** : héberge les sites web

---

![ bg ](https://www.gsara.tv/neutralite/wp-content/uploads/2011/08/big-internet-scheme.jpg)

---

<!-- header: Internet et le Web-->

## Protocoles de communication

- **HTTP** : HyperText Transfer Protocol
- **HTTPS** : HTTP Secure
- **FTP** : File Transfer Protocol

---

<!-- header: Internet et le Web-->

## Noms de domaine

- **DNS** : Domain Name System
- **TLD** : Top-Level Domain (ex: .com, .org, .net)
- **ccTLD** : Country Code Top-Level Domain (ex: .fr, .de, .uk, .us, etc...)

Note : Le **.tv** est le ccTLD de Tuvalu, petit pays insulaire du Pacifique Sud.

---

<!-- header: Internet et le Web-->

## Protocoles de la couche application

- **SMTP** : Simple Mail Transfer Protocol
- **POP3** : Post Office Protocol
- **IMAP** : Internet Message Access Protocol
- **DNS** : Domain Name System
- **HTTP** / **HTTPS\*** : HyperText Transfer Protocol
- **FTP** : File Transfer Protocol
- **SSH** : Secure Shell
- ...

\*HTTP Secure

---

<!-- _class: chapter invert -->

# Roles et particularités des outils numériques

Introduction aux différents outils numériques utilisés
dans le cadre professionnel.

---

<!-- header: Roles et particularités des outils numériques-->

## Introduction aux outils numériques

- **Client de messagerie** : Outlook, Thunderbird
- **Client de messagerie instantanée** : Slack, Teams
- **Client FTP** : FileZilla, Cyberduck
- **Clients VPN** : OpenVPN, Cisco AnyConnect
- **Clients de stockage** : Dropbox, Google Drive, OneDrive
- **Navigateur web** : Chrome, Firefox, Safari
- **Gestionnaire de mots de passe** : LastPass, 1Password
- **Outils de collaboration** : Google Workspace, Microsoft 365

---

<!-- header: Roles et particularités des outils numériques-->

## L'interconnexion des outils

- **API** : Application Programming Interface
- **Webhooks** : Notifications HTTP
- **Zapier** : Automatisation des tâches
- **IFTTT** : If This Then That

---

<!-- _class: chapter invert -->

# Bonnes pratiques de sécurité

Introduction aux bonnes pratiques de sécurité pour protéger vos données et votre vie privée dans un environnement numérique.

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité des mots de passe

- **Longueur** : 12 caractères minimum
- **Complexité** : majuscules, minuscules, chiffres, caractères spéciaux
- **Authentification à deux facteurs** : 2FA
- **Gestionnaire de mots de passe** : Bitwarden, LastPass, 1Password

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité des données

- **Chiffrement** : BitLocker, FileVault
- **Sauvegarde** : Time Machine, Backblaze
- **VPN** : Virtual Private Network
- **Firewall** : pare-feu

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité des appareils

- **Mises à jour** : système d'exploitation, applications
- **Codes d'accès** : verrouillage de l'écran
- **Localisation** : géolocalisation
- **Effacement à distance** : Find My iPhone, Android Device Manager
- **Antivirus** : Windows Defender, Malwarebytes

**NB : Éviter de télécharger des applications tierces sans vérification**

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité sur le web

- **HTTPS** : HyperText Transfer Protocol Secure
- **Extensions de navigateur** : uBlock Origin, Privacy Badger
- **Wi-Fi public** : méfiance des réseaux non sécurisés (hotspots)

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité des emails

- **Reconnaissance des emails frauduleux** : phishing
- **Vérification des pièces jointes** : fichiers .exe, .zip
- **Vérification des liens** : URL raccourcies
- **Signalement des emails suspects** : spam
- **Chiffrement des emails** : PGP, S/MIME

---

<!-- header: Bonnes pratiques de sécurité-->

## Protection des données personnelles

- **RGPD** : Règlement Général sur la Protection des Données
- **Consentement** : autorisation explicite
- **Droit à l'oubli** : suppression des données
- **Portabilité des données** : transfert des données
- **Notification des violations** : failles de sécurité

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité mobile

- **Mises à jour** : système d'exploitation, applications
- **Codes d'accès** : verrouillage de l'écran
- **Localisation** : géolocalisation
- **Effacement à distance** : Find My iPhone, Android Device Manager
- **Ne pas le laisser sans surveillance** : risque de vol

---

<!-- header: Bonnes pratiques de sécurité-->

## Sécurité des réseaux sociaux

- **Paramètres de confidentialité** : visibilité des publications
- **Authentification à deux facteurs** : 2FA
- **Vérification des applications tierces** : accès aux données
- **Signalement des contenus abusifs** : harcèlement, fake news

---

<!-- header: Bonnes pratiques de sécurité-->

## Sensibilisation à l'ingénierie sociale

- **Phishing** : usurpation d'identité
- **Spear phishing** : ciblage spécifique
- **Social engineering** : manipulation psychologique

---

<!-- header: Bonnes pratiques de sécurité-->

## Gestion des incidents de sécurité

Etapes à suivre en cas de compromission :

- **Isolation** : déconnexion des appareils
- **Analyse** : identification de la faille
- **Correction** : résolution du problème
- **Prévention** : mise en place de mesures de sécurité
- **Reporting** : documentation des incidents
- **Signalement** : déclaration des incidents

---

<!-- header: Bonnes pratiques de sécurité-->

## Sensibilisation à la sécurité

- **Formation** : sensibilisation des employés
- **Exercices** : simulations d'attaques
- **Tests** : évaluation des compétences
- **Veille** : surveillance des menaces

---

<!-- header: Bonnes pratiques de sécurité-->

## Conclusion

La sécurité informatique est l'affaire de tous. Il est important de sensibiliser les utilisateurs aux bonnes pratiques de sécurité pour protéger les données et la vie privée.

---

<!-- _class: chapter invert -->

# Les formats de fichiers et ordres de grandeur

Introduction aux différents formats de fichiers et aux ordres de grandeur utilisés en informatique.

---

<!-- header: Formats de fichiers et ordres de grandeur-->

## Formats de fichiers

- **Texte** : .txt, .docx, .pdf _(±100 Ko)_
- **Image** : .jpg, .png, .gif _(±2 Mo)_
- **Audio** : .mp3, .wav, .flac _(±5 Mo)_
- **Vidéo** : .mp4, .avi, .mov _(±700 Mo)_
- **Archive** : .zip, .rar, .tar _(±50 Mo)_
- **Exécutable** : .exe, .app, .deb _(±20 Mo)_

---

<!-- header: Formats de fichiers et ordres de grandeur-->

## Ordres de grandeur

- **Bit** : 0 ou 1
- **Octet** : 8 bits (ex: 01001001 représente la lettre "I" et pèse 1 octet)
- **Kilo-octet** : 1024 octets
- **Méga-octet** : 1024 kilo-octets
- **Giga-octet** : 1024 méga-octets
- **Téra-octet** : 1024 giga-octets
- **Péta-octet** : 1024 téra-octets
- **Exa-octet** : 1024 péta-octets
- **Zetta-octet** : 1024 exa-octets
- **Yotta-octet** : 1024 zetta-octets

---

<!-- header: Formats de fichiers et ordres de grandeur-->

## Conversion des ordres de grandeur

- **1 Ko** = 1024 octets
- **1 Mo** = 1024 Ko
- **1 Go** = 1024 Mo
- **1 To** = 1024 Go
- **1 Po** = 1024 To
- **1 Eo** = 1024 Po
- **1 Zo** = 1024 Eo
- **1 Yo** = 1024 Zo

---

<!-- header: Formats de fichiers et ordres de grandeur-->

## Conclusion

Les formats de fichiers et les ordres de grandeur permettent de définir la taille des fichiers et des données en informatique. Il est important de connaître ces concepts pour gérer efficacement les ressources numériques.

---

<!-- _class: chapter invert -->

# Résolutions d'écran

Introduction aux différentes résolutions d'écran et aux normes utilisées en informatique.

---

<!-- header: Résolutions d'écran-->

## Résolutions d'écran

- **VGA** : 640x480 pixels
- **SVGA** : 800x600 pixels
- **XGA** : 1024x768 pixels
- **WXGA** : 1280x800 pixels
- **HD** : 1366x768 pixels
- **Full HD** : 1920x1080 pixels
- **QHD** : 2560x1440 pixels
- **4K** : 3840x2160 pixels
- **8K** : 7680x4320 pixels

---

<!-- header: Résolutions d'écran-->

## Aspect ratio

- **4:3** : VGA, XGA
- **16:9** : HD, Full HD, 4K
- **16:10** : WXGA
- **21:9** : UltraWide

---

<!-- header: Résolutions d'écran-->

## Densité de pixels

- **PPI** : Pixels Per Inch
- **DPI** : Dots Per Inch
- **Retina Display** : Apple
- **Pixel Density** : Samsung

---

<!-- header: Résolutions d'écran-->

## Tailles d'écran

- **Diagonale** : 15.6 pouces
- **Ratio** : 16:9
- **Résolution** : 1920x1080 pixels
- **Densité de pixels** : 141 PPI

---

<!-- header: Résolutions d'écran-->

## Conclusion

Les résolutions d'écran et les normes utilisées en informatique permettent de définir la qualité et la taille des écrans. Il est important de choisir une résolution adaptée à ses besoins pour une meilleure expérience visuelle.

---

<!-- _class: chapter invert -->

# Introduction aux bonnes pratiques du developpement web

Introduction aux bonnes pratiques du développement web pour créer des sites web performants et accessibles.

---

<!-- header: Bonnes pratiques du developpement web-->

## HTML

- **Utilisation des balises sémantiques** : header, footer, nav, main, section, article
- **Importance de la sémanthique** : accessibilité, SEO
- **Validation du code** : W3C Validator

---

<!-- header: Bonnes pratiques du developpement web-->

## CSS

- **Principe de base** : Cascade, Spécificité, Héritage
- **Utilisation des classes** : réutilisabilité, maintenabilité
- **Responsive design** : Media queries, Flexbox, Grid
- **Méthodologie** : BEM, SMACSS, OOCSS

---

<!-- header: Bonnes pratiques du developpement web-->

## JavaScript

- **Utilisation des événements** : click, hover, submit
- **Manipulation du DOM** : document.querySelector, document.createElement
- **Gestion des erreurs** : try, catch, throw

---

<!-- header: Bonnes pratiques du developpement web-->

## Accessibilité

Le Web Content Accessibility Guidelines (WCAG) est un ensemble de recommandations pour rendre les sites web accessibles à tous :

- **Contraste** : texte lisible
- **Navigation** : clavier, lecteur d'écran
- **Sémantique** : balises HTML
- **Aria** : Accessible Rich Internet Applications

---

<!-- header: Bonnes pratiques du developpement web-->

## Compatibilité des navigateurs

- **Test sur les navigateurs** : Chrome, Firefox, Safari, Edge
- **Utilisation de préfixes** : -webkit-, -moz-, -ms-, -o-
- **Polyfills** : JavaScript, CSS
- **fallbacks** : solutions de secours

---

<!-- header: Bonnes pratiques du developpement web-->

## SEO

- **Balises meta essentielles** : title, description, keywords
- **Structure des URLs** : lisibilité, mots-clés
- **Optimisation du contenu** : mots-clés, liens internes, liens externes

---

<!-- header: Bonnes pratiques du developpement web-->

## Tests et débogage

- **Outils de développement** : Chrome DevTools, Firefox DevTools
- **Tests de performance** : Lighthouse, GTmetrix
- **Tests de compatibilité** : BrowserStack, CrossBrowserTesting

---

<!-- header: Bonnes pratiques du developpement web-->

## Performance et expérience utilisateur

- **Temps de chargement et Core Web Vitals** : Interactivity, Layout Stability, Cumulative Layout Shift
- **Design intuitif** : navigation, ergonomie
- **Contenu de qualité** : texte, images, vidéos
- **Feedback utilisateur** : formulaires, boutons
- **Mobile first** : responsive design

---

<!-- header: Bonnes pratiques du developpement web-->

## Maintenance et évolution

- **Mises à jour régulières** : sécurité, performance
- **Analyse des données** : Google Analytics, Hotjar
- **Feedback utilisateur** : enquêtes, sondages

---

<!-- header: Bonnes pratiques du developpement web-->

## Conclusion

Les bonnes pratiques du développement web permettent de créer des sites web performants, accessibles et optimisés pour les moteurs de recherche. Il est important de suivre ces recommandations pour offrir une expérience utilisateur de qualité.

---

<!-- _class: cover invert -->

# Testez vos connaissances 🚀

Flashez le QR code pour accéder au quiz

![ w:300](../assets/quiz.svg)

---

<!-- _class: cover invert -->

# Merci !

# 🙂
