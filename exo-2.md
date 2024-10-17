# Comparatif des coûts pour 3 infrastructures sur 5 fournisseurs cloud ☁️

## Sommaire
- [Infrastructure n°1 : 1 serveur (16 Go de RAM, 4 vCPU, 100 Go de stockage SSD) 💻](#infrastructure-n1--1-serveur-16-go-de-ram-4-vcpu-100-go-de-stockage-ssd-)
- [Infrastructure n°2 : 6 serveurs (6 Go de RAM, 3 vCPU, 20 Go de stockage chacun) 🖥️](#infrastructure-n2--6-serveurs-6-go-de-ram-3-vcpu-20-go-de-stockage-chacun-)
- [Infrastructure n°3 : 3 serveurs + Load Balancer + Base de données managée 🗄️](#infrastructure-n3--3-serveurs--load-balancer--base-de-données-managée-)
- [Conclusion générale 🏁](#conclusion-générale-)


---

## Infrastructure n°1 : 1 serveur (16 Go de RAM, 4 vCPU, 100 Go de stockage SSD) 💻

| Fournisseur  | Coût de l'instance | Coût du stockage | Coût total |
|--------------|--------------------|------------------|------------|
| **AWS**      | 60 USD/mois         | 10 USD/mois      | **70 USD/mois** |
| **GCP**      | 138 USD/mois        | 10 USD/mois      | **148 USD/mois** |
| **Azure**    | 95 USD/mois         | 10 USD/mois      | **105 USD/mois** |
| **Scaleway** | 75 USD/mois         | 25 USD/mois      | **100 USD/mois** |
| **OVH**      | 65 USD/mois         | 10 USD/mois      | **75 USD/mois** |

### Détails des calculs :
- **AWS** :
  - **Coût de l'instance** : t3.large à 0,0832 USD/heure, soit **60 USD/mois** pour 720 heures.  
    Formule :  
    \[
    0,0832 \times 720 = 60 \, \text{USD/mois}
    \]
  - **Stockage EBS** : 100 Go à 0,10 USD/Go, soit **10 USD/mois**.  
    Formule :  
    \[
    0,10 \times 100 = 10 \, \text{USD/mois}
    \]
  - **Coût total AWS** : **70 USD/mois**

- **GCP** :
  - **Coût de l'instance** : n4-standard-4 à 138 USD/mois pour 4 vCPU et 16 Go de RAM.
  - **Stockage SSD** : 100 Go à 0,10 USD/Go, soit **10 USD/mois**.
  - **Coût total GCP** : **148 USD/mois**

- **Azure** :
  - **Coût de l'instance** : D2s v3 à 95 USD/mois.
  - **Stockage SSD** : 100 Go à 0,10 USD/Go, soit **10 USD/mois**.
  - **Coût total Azure** : **105 USD/mois**

- **Scaleway** :
  - **Coût de l'instance** : DEV1-L à 75 USD/mois.
  - **Stockage Block** : 100 Go à 0,25 USD/Go, soit **25 USD/mois**.
  - **Coût total Scaleway** : **100 USD/mois**

- **OVH** :
  - **Coût de l'instance** : B2-15 à 65 USD/mois.
  - **Stockage SSD** : 100 Go à 0,10 USD/Go, soit **10 USD/mois**.
  - **Coût total OVH** : **75 USD/mois**

---

## Infrastructure n°2 : 6 serveurs (6 Go de RAM, 3 vCPU, 20 Go de stockage chacun) 🖥️

| Fournisseur  | Coût des instances | Coût du stockage | Coût total |
|--------------|--------------------|------------------|------------|
| **AWS**      | 200 USD/mois        | 12 USD/mois      | **212 USD/mois** |
| **GCP**      | 230 USD/mois        | 12 USD/mois      | **242 USD/mois** |
| **Azure**    | 240 USD/mois        | 12 USD/mois      | **252 USD/mois** |
| **Scaleway** | 200 USD/mois        | 12 USD/mois      | **212 USD/mois** |
| **OVH**      | 180 USD/mois        | 12 USD/mois      | **192 USD/mois** |

### Détails des calculs :
- **AWS** :
  - **Coût des instances** : t3.medium à 0,0416 USD/heure.  
    Formule :  
    \[
    (3 \times 30) + (3 \times 30 \times 0,67) = 200 \, \text{USD/mois}
    \]
  - **Stockage EBS** : 20 Go par serveur pour 6 serveurs.  
    Formule :  
    \[
    0,10 \times 20 \times 6 = 12 \, \text{USD/mois}
    \]
  - **Coût total AWS** : **212 USD/mois**

- **GCP** :
  - **Coût des instances** : 230 USD/mois pour 6 serveurs.
  - **Stockage SSD** : 20 Go par serveur, soit 12 USD/mois.
  - **Coût total GCP** : **242 USD/mois**

- **Azure** :
  - **Coût des instances** : 240 USD/mois pour 6 serveurs.
  - **Stockage SSD** : 12 USD/mois pour 120 Go total.
  - **Coût total Azure** : **252 USD/mois**

- **Scaleway** :
  - **Coût des instances** : 200 USD/mois pour 6 serveurs.
  - **Stockage Block** : 12 USD/mois pour 120 Go.
  - **Coût total Scaleway** : **212 USD/mois**

- **OVH** :
  - **Coût des instances** : 180 USD/mois pour 6 serveurs.
  - **Stockage SSD** : 12 USD/mois pour 120 Go.
  - **Coût total OVH** : **192 USD/mois**

---

## Infrastructure n°3 : 3 serveurs + Load Balancer + Base de données managée 🗄️

| Fournisseur  | Coût des instances | Coût du stockage | Load Balancer | Base de données | Coût total |
|--------------|--------------------|------------------|---------------|-----------------|------------|
| **AWS**      | 45 USD/mois         | 15 USD/mois      | 18 USD/mois   | 28 USD/mois     | **106 USD/mois** |
| **GCP**      | 45 USD/mois         | 15 USD/mois      | 20 USD/mois   | 25 USD/mois     | **105 USD/mois** |
| **Azure**    | 48 USD/mois         | 15 USD/mois      | 25 USD/mois   | 30 USD/mois     | **118 USD/mois** |
| **Scaleway** | 40 USD/mois         | 15 USD/mois      | 20 USD/mois   | 30 USD/mois     | **105 USD/mois** |
| **OVH**      | 35 USD/mois         | 15 USD/mois      | 20 USD/mois   | 25 USD/mois     | **95 USD/mois** |

### Détails des calculs :

- **AWS** :
  - **Coût des instances** : t3.small à 0,0208 USD/heure.  
    Formule :  
    \[
    0,0208 \times 720 = 45 \, \text{USD/mois}
    \]
  - **Stockage EBS** : 50 Go par serveur pour 3 serveurs, soit **15 USD/mois**.  
    Formule :  
    \[
    0,10 \times 50 \times 3 = 15 \, \text{USD/mois}
    \]
  - **Load Balancer** : 18 USD/mois.
  - **Base de données RDS** : 28 USD/mois pour db.t3.small avec 10 Go de stockage.
  - **Coût total AWS** : **106 USD/mois**

- **GCP** :
  - **Coût des instances** : 45 USD/mois pour 3 serveurs.
  - **Stockage SSD** : 15 USD/mois pour 150 Go (50 Go par serveur).
  - **Load Balancer** : 20 USD/mois.
  - **Cloud SQL** : 25 USD/mois pour une petite base de données managée.
  - **Coût total GCP** : **105 USD/mois**

- **Azure** :
  - **Coût des instances** : 48 USD/mois pour 3 serveurs.
  - **Stockage SSD** : 15 USD/mois pour 150 Go.
  - **Load Balancer** : 25 USD/mois.
  - **Base de données managée** : 30 USD/mois pour une petite base SQL.
  - **Coût total Azure** : **118 USD/mois**

- **Scaleway** :
  - **Coût des instances** : 40 USD/mois pour 3 serveurs (DEV1-S).
  - **Stockage Block** : 15 USD/mois pour 150 Go.
  - **Load Balancer** : 20 USD/mois.
  - **Base de données managée** : 30 USD/mois pour une petite base.
  - **Coût total Scaleway** : **105 USD/mois**

- **OVH** :
  - **Coût des instances** : 35 USD/mois pour 3 serveurs.
  - **Stockage SSD** : 15 USD/mois pour 150 Go.
  - **Load Balancer** : 20 USD/mois.
  - **Base de données managée** : 25 USD/mois pour une base de données SQL.
  - **Coût total OVH** : **95 USD/mois**

---

### Conclusion générale 🏁

- **OVH** et **Scaleway** restent les solutions les plus compétitives sur cette infrastructure, avec des coûts totaux plus bas.
- **AWS** et **GCP** sont proches en termes de coût, mais AWS offre des fonctionnalités plus avancées pour le load balancing et les bases de données.
- **Azure** est le plus cher, principalement à cause des coûts du load balancer et des bases de données managées.
