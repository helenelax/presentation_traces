## Les traces - comment les informations circulent sur Internet ?

---
Hélène Laxenaire  
L'Institut Agro - campus de Florac  
mai 2020

@snap[text-05 text-grey]
CC BY-SA 4.0
@snapend

---

## Objectifs
* Comprendre comment les informations circulent sur internet
* Quel opérateur a accès à quelle information ?
* Effleurer l'économie de la donnée avec des exemples d'usage de Google

---
## Plan
1. L'architecture du réseau Internet
2. Comment circulent les informations ? Quel opérateur a accès à quelle information ?
3. Les 3 niveaux d'identité numérique (+1)
4. Économie de la donnée quelques exemples d'usage de Google

---
## 1. Architecture du réseau

![Carte du réseau](http://www.lamerguez.com/presentations_GitPich/presentation-traces/Carte_reseau_internet_v2c.png "Schéma reprenant les différents opérateurs d'internet et comment ils sont reliés")

+++
### 1. Glossaire

* TCP/IP : protocole commun les serveurs peuvent "discuter" eux
* Internet = InterNetwork
* Serveur DNS : annuaire URL<--> IP
* IP publique = serveur/box
* IP privée = ordi du réseau
* PABX : central téléphonique

---
## 2. Circulation de l'information
* Exemples de circulation
    * Je vais voir un site web en notant son adresse URL
    * Je vais voir un site web en passant par un moteur de recherche
    * Je vais voir un site web en passant par un moteur de recherche et il a des pubs
    * Je vais voir un site web avec mon smartphone

---

### 2. Les informations qui circulent
* Expéditeur/destinataire 
* Contenu 

+++

### 2. Les informations qui circulent
* Données techniques de connexion
    * Horodatage 
    * Pour l'affichage
    * Pour personnaliser l'expérience


+++
### 2. Les informations qui circulent
* Cookies ![Icone](http://www.lamerguez.com/presentations_GitPich/presentation-traces/cookie.png  "dessin de cookies")

+++

Pour voir un cookie, cliquez sur la touche F12 (Firefox) et cherchez l'onglet **Stockage**

+++
![Copie écran Cookies](http://www.lamerguez.com/presentations_GitPich/presentation-traces/cookies_lemonde.png "Copie d'écran des cookies présents sur le site du monde")

@snap[text-05 text-grey]
Exemple pour le site du Monde, le 17 mai 2020
@snapend

+++

### 2. Les informations qui circulent

* Données des capteurs
* Données biométriques


+++
### 2. Les informations qui circulent

* "Détournements"
    * Fingerprinting (données techniques uniques pour identifier) 
    * Pixel transparent (qui a ouvert le mail)

---

### 2. Qui peut avoir accès aux informations ?

* les personnes qui ont accès à l'ordinateur
* le fournisseur d'accès internet (FAI)
* les différents serveurs par lesquels l'information transite
* le propriétaire du site web (et ses employés)

+++

### 2. Qui peut avoir accès aux informations ?
* les partenaires du site web : 
    * serveurs de publicité
    * identification par un service tiers (Facebook,..)
    * partenaires commerciaux du site web
    * service de statistiques
    * fournisseur d'application tiers (sur les réseaux sociaux)
    * ...

+++
### 2. Qui peut avoir accès aux informations ?
* la justice
* la police 
* les services de renseignements du pays où est hébergé le site

+++

### 2. Qui peut avoir accès aux informations ?
* personnes/organismes détournant les informations (satellite, câble sous-marin, virus, jeux, antenne, faux hotspot wifi, hacker *black hat*...)
* service de renseignements étrangers, maitre-chanteur, Cambridge Analytica,...

---

### 2. Que dit la loi ?
* En France, confidentialité des données 
* sauf consentement explicite
* Exceptions : police, justice et renseignements

+++

### 2. Que dit la loi ?
* "Secret des correspondances" :
    * contenu
    * identité des correspondants
    * intitulé mail
    * pièces jointes 

Note: opérateurs technique = aussi fournisseurs de contenu

+++

### 2. Que dit la loi ?
* Conservation des données pour un an par les FAI et hébergeurs
    * identifiant de l’utilisateur
    * horodatage 
    * localisation
    * identification du destinataire
Note:
* Loi sur la sécurité quotidienne de 2001 : conservation identifiants par FAI
* Loi de confiance dans l'économie numérique de 2004: : conservation identifiants par hébergeur
* Loi sur le renseignement de 2015
* Loi pour une République numérique de 2016 (Axelle Lemaire) : "secret des correspondances"

---

### 2.Qui peut avoir accès à quoi : deux exemples pratiques
* Je vais voir un site web
* Je vais sur Facebook

---


## 3. Les trois niveaux d'identité +1
Fanny Georges, 2009

* Identité déclarative  
* Identité agissante  
* Identité calculée

Note: Représentation de soi et identité numérique : Une approche sémiotique et quantitative de l'emprise culturelle du web 2.0 

+++

### Identité déclarative  
* ce que je dis de moi...

* ...ce que les autres disent de moi (ajout personnel)

+++

### Identité agissante  
* Ce que je fais en ligne
    * nouer des relations
    * visiter un service
    * jouer
    * se déplacer
    * lire
    * ...

+++

### Identité calculée  
* Statistiques découlant des deux identités précédentes
    * Nombre d'amis
    * Temps de visite
    * Nombre de message
* **C'est dans ce sens que l'entends Fanny Georges**

+++

### Identité calculée à l'heure des Big Data
* Big data
* Probabilité
* Corrélation

+++

![Les trois niveaux d'identité](https://www.lemonde.fr/blog/internetactu/files/2019/02/3_levels_digital-identity_panoptykon.jpg "Une épingle représentant la position")
@snap[text-05 text-grey]
Source : [Fondation Panoptykon](https://en.panoptykon.org/ "Lien vers le site de la fondation Panoptykon")
@snapend

+++

*Même si je ne dis rien, ce que disent ou font les personnes qui me ressemblent, parle de moi*


---

## 4. Économie de la donnée
* Des statistiques
* Des profils génériques
* Des profils précis : publicité ciblée

+++

### 4. Économie de la donnée
* Des statistiques

Répartition par âge des visiteurs d'un site  
![Statistiques par age des visiteurs d'un site](http://www.lamerguez.com/presentations_GitPich/presentation-traces/Google_analytics_age.png "Schéma détaillant la proportion de visiteurs par tranche d'âge")

+++

Répartition par genre des visiteurs d'un site  
![Statistiques par genre des visiteurs d'un site](http://www.lamerguez.com/presentations_GitPich/presentation-traces/Google_analytics_genre.png "Schéma détaillant la proportion de visiteurs par genre")


+++

### 4. Économie de la donnée
* Des profils génériques

![Statistiques par profils des visiteurs d'un site](http://www.lamerguez.com/presentations_GitPich/presentation-traces/Google_analytics_profil.png "Tableau détaillant la proportion de visiteurs par profil/centres d'intérêt")

+++
### 4. Des profils précis : publicité ciblée

* âge
* genre
* goûts
* CSP
* opinions politiques
* ...

+++

*"La représentation acquiert un caractère distinctif par son alimentation : plus le profil utilisateur comporte de signes, plus la représentation est distinctive."*  
  
Fanny Georges

---
## Bibliographie

* Georges Fanny, « Représentation de soi et identité numérique. Une approche sémiotique et quantitative de l'emprise culturelle du web 2.0 », *Réseaux*, 2009/2 (n° 154), p. 165-193. <https://www.cairn.info/revue-reseaux-2009-2-page-165.htm>

* Guillaud Hubert, « Les 3 niveaux de nos identités en ligne», *InternetActu*, 30/01/2019. <http://www.internetactu.net/a-lire-ailleurs/les-3-niveaux-de-nos-identites-en-ligne/>

