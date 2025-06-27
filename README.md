# 05. Projet - Distorsion

## Conditions d’achèvement

### Distorsion

Notre objectif va être de mettre au point un système de messagerie ressemblant fortement à des logiciels célèbres tels que **Slack** ou **Discord**.

Le principe est simple :  
Les messages sont affichés dans des salons distincts, lesquels sont rangés dans des catégories.

La particularité de notre projet, **Distorsion**, est qu'il ne sera pas nécessaire de créer un compte pour communiquer.  
Tous les messages sont anonymes.

---

## Fonctionnalités

- Créer des catégories
- Créer des salons
- Afficher la liste des catégories et de leurs salons respectifs avec la possibilité de naviguer d'un salon à l'autre
- Afficher les messages du salon sélectionné, ordonnés par date et heure d'envoi
- Envoyer des messages dans un salon
- Naviguer sur d'autres pages que celle du chat principal : par exemple *À propos*, *Paramètres*, etc.

---

## Contraintes techniques

- Pour chaque table de la base de données, un **Model** et un **Manager**
- Tout doit être en **POO**
- L'architecture doit être en **MVC**
- Faites de votre **routeur une classe**

### Bonus

- Utilisez des **namespaces** et un **autoloader**
- Mettre en place une **authentification** et des **rôles** :
    - L'administrateur a la possibilité d'ajouter des catégories et des salons, pas les users.
