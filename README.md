# 🚀 Born2beRoot 

## 🎯 Objectifs

- Créer et configurer une **machine virtuelle** (via VirtualBox ou UTM).
- Utiliser **Debian** (ou Rocky Linux) comme système d’exploitation.
- Appliquer des règles de sécurité poussées (SSH, sudo, UFW, mots de passe, etc.).
- Créer un **script de monitoring** système en bash.
- Apprendre les bases de l’**administration système Linux** et de la **cybersécurité**.

### 💿 Machine virtuelle
- Création d’une machine via **VirtualBox**
- Système d’exploitation : **Debian**
- Utilisation de **LVM** avec au moins **2 partitions chiffrées**

### 🔐 Sécurité
- Port SSH modifié : `4242`  
- Connexion root via SSH désactivée
- Utilisateur personnel avec mon login (`monlogin`)  
  ➜ membre des groupes `user42` et `sudo`  
- **Pare-feu UFW** actif avec uniquement le port 4242 ouvert  
- **Mot de passe fort obligatoire** :  
  - Minimum 10 caractères  
  - 1 majuscule, 1 minuscule, 1 chiffre  
  - Pas plus de 3 caractères identiques à la suite  
  - Ne pas contenir le nom d’utilisateur  
  - Expiration : 30 jours, modif mini : 2 jours, alerte : 7 jours

### 🧑‍💻 Sudo configuré strictement :
- 3 tentatives maximum
- Message personnalisé en cas d’erreur
- Logs d’utilisation de sudo enregistrés dans `/var/log/sudo/`

---

🧠 **Ce que j’ai appris**

- 🌐 Mise en place et configuration d’un OS serveur
- 🧱 Gestion des disques, du partitionnement et du chiffrement (LVM)
- 🔒 Renforcement de la sécurité (SSH, sudo, mots de passe)
- 🧰 Utilisation d’outils comme `apt`, `sudo`, `crontab`
- 🖥️ Surveillance système automatisée via scripts bash

---

✅ **STATUT:**  
📅 Date de rendu : 22.12.2024  
📝 Note obtenue : 100/100

---
