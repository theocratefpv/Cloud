# Exercice : Quel type de cloud pour quels besoins ? ☁️💻

## Sommaire
- [Cas n°1 : Eldo, start-up dans le secteur du BTP 🛠️](#cas-n1--eldo-start-up-dans-le-secteur-du-btp-)
- [Cas n°2 : MySecureProtect, objets connectés de sécurité 🔒📱](#cas-n2--mysecureprotect-objets-connectés-de-sécurité-)
- [Cas n°3 : Paul, utilisateur particulier 📸](#cas-n3--paul-utilisateur-particulier-)
- [Cas n°4 : Grande entreprise de défense 🛡️](#cas-n4--grande-entreprise-de-défense-)
- [Cas n°5 : TheFoodStore, site e-commerce 🍔](#cas-n5--thefoodstore-site-e-commerce-)
- [Cas n°6 : DeliverEats, plateforme de livraison 🍽️](#cas-n6--delivereats-plateforme-de-livraison-)
- [Cas n°7 : Onenveutpa, télévendeurs à l'international 📞🌍](#cas-n7--onenveutpa-télévendeurs-à-linternational-)

---

## Cas n°1 : Eldo, start-up dans le secteur du BTP 🛠️

### Besoins :
Eldo développe un logiciel de mise en relation pour les professionnels du BTP ainsi qu'un CRM dédié. Avec une équipe de 60 employés, il est essentiel d'héberger les logiciels de manière évolutive.

### Solution recommandée :
- **Type de Cloud :** Public Cloud 🌍
- **XaaS :** Platform as a Service (PaaS)

### Pourquoi ?
Le PaaS permet à Eldo de se concentrer sur le développement sans se préoccuper de la gestion des serveurs. Cela permet de déployer rapidement leurs applications et de bénéficier de l'évolutivité d'un cloud public. Des solutions comme **AWS Elastic Beanstalk**, **Google App Engine**, ou **Azure App Services** peuvent répondre à ces besoins.

### Coût estimé :
Environ **100 à 500 USD** par mois, en fonction de la taille des applications et de l'utilisation des services. 💸

---

## Cas n°2 : MySecureProtect, objets connectés de sécurité 🔒📱

### Besoins :
MySecureProtect gère plus d'un million d'objets connectés en permanence. L'infrastructure doit gérer des pics d'activité principalement le matin, le soir, et lors des anomalies de sécurité.

### Solution recommandée :
- **Type de Cloud :** Hybrid Cloud ⚙️
- **XaaS :** Infrastructure as a Service (IaaS) avec Serverless (FaaS)

### Pourquoi ?
Un **cloud hybride** permet de maintenir certains services critiques sur des serveurs locaux tout en utilisant le cloud public pour gérer les pics d'activité grâce à des fonctions serverless comme **AWS Lambda** ou **Azure Functions**. Cela garantit l'élasticité et optimise les coûts en ne payant que pour l'infrastructure utilisée pendant les pics.

### Coût estimé :
Environ **2000 à 5000 USD** par mois, en fonction de l'ampleur des pics d'activité. 💼

---

## Cas n°3 : Paul, utilisateur particulier 📸

### Besoins :
Paul souhaite stocker ses **800 Go** de photos en ligne, avec un accès facile depuis plusieurs appareils. Ses compétences en informatique sont limitées et son besoin en stockage évolue très peu.

### Solution recommandée :
- **Type de Cloud :** Public Cloud 🌥️
- **XaaS :** Software as a Service (SaaS)

### Pourquoi ?
Des solutions comme **Google Drive**, **OneDrive** ou **iCloud** offrent un service simple et efficace pour stocker les données et y accéder depuis n'importe quel appareil. C'est une solution parfaite pour Paul qui souhaite de la simplicité.

### Coût estimé :
Environ **10 USD par mois** pour 1 To de stockage. 📦

---

## Cas n°4 : Grande entreprise de défense 🛡️

### Besoins :
Cette entreprise doit moderniser son infrastructure avec une grande flexibilité pour répondre à des besoins rapidement évolutifs. La sécurité est primordiale.

### Solution recommandée :
- **Type de Cloud :** Private Cloud ou Hybrid Cloud 🔐
- **XaaS :** Infrastructure as a Service (IaaS)

### Pourquoi ?
Un **cloud privé** ou hybride permet de conserver un contrôle total sur les données sensibles tout en offrant de l’évolutivité. Cette solution permet à l'entreprise de gérer de nombreux serveurs, des besoins de stockage importants, et des réseaux complexes tout en assurant une sécurité maximale.

### Coût estimé :
Une solution en cloud privé sur **OpenStack** ou **VMware** coûterait environ **20 000 à 50 000 USD** par mois, en fonction de l'infrastructure nécessaire. 💰

---

## Cas n°5 : TheFoodStore, site e-commerce 🍔

### Besoins :
TheFoodStore veut rapidement publier son site e-commerce pour commencer à vendre en ligne.

### Solution recommandée :
- **Type de Cloud :** Public Cloud ☁️
- **XaaS :** Software as a Service (SaaS)

### Pourquoi ?
Une solution SaaS comme **Shopify** ou **WooCommerce** est idéale pour un site e-commerce. Ces plateformes offrent toutes les fonctionnalités nécessaires pour gérer un site de vente en ligne (stocks, paiements, etc.) sans avoir à se soucier de l’infrastructure.

### Coût estimé :
Environ **30 à 100 USD par mois** selon les besoins. 🛒

---

## Cas n°6 : DeliverEats, plateforme de livraison 🍽️

### Besoins :
DeliverEats a besoin d'une architecture capable de gérer un site internet, une application mobile, et une forte demande lors des pics de commande.

### Solution recommandée :
- **Type de Cloud :** Public Cloud 🌐
- **XaaS :** Platform as a Service (PaaS) avec une composante Serverless (FaaS)

### Pourquoi ?
Une architecture basée sur **PaaS** comme **AWS Elastic Beanstalk** pour les applications principales, et des services serverless pour gérer les montées en charge, est idéale. Cela permet de gérer les pics de demande sans gaspiller de ressources.

### Coût estimé :
Environ **1000 à 3000 USD** par mois, selon les pics d'activité et l’utilisation des services serverless. ⚙️

---

## Cas n°7 : Onenveutpa, télévendeurs à l'international 📞🌍

### Besoins :
L'entreprise a besoin d'un CRM pour gérer les prospects et les informations client à l'échelle mondiale avec un grand nombre de télévendeurs.

### Solution recommandée :
- **Type de Cloud :** Public Cloud 🌐
- **XaaS :** Software as a Service (SaaS)

### Pourquoi ?
Des solutions comme **Salesforce** ou **Zoho CRM** permettent de gérer des données client à l'échelle internationale avec une facilité d'utilisation et sans gestion d'infrastructure lourde. C'est idéal pour une entreprise dispersée géographiquement.

### Coût estimé :
Environ **12 à 25 USD par utilisateur** par mois, soit environ **12 000 USD** par mois pour 1000 télévendeurs. 🧑‍💻
