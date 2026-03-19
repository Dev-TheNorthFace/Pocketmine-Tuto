# 🚀 PocketMine-Tuto

> 📘 Un guide complet pour comprendre, installer et résoudre les problèmes liés à PocketMine-MP.

---

## 📖 À propos

Ce tutoriel vous expliquera :

- ✅ Les erreurs les plus courantes sur **PocketMine-MP**
- ⚙️ Comment installer et configurer un serveur
- 🧠 Les bases à connaître pour bien débuter
- 🔧 Comment résoudre les problèmes fréquents

👉 Que vous soyez **débutant ou intermédiaire**, ce guide est fait pour vous.

---

## 🧱 Qu'est-ce que PocketMine-MP ?

**PocketMine-MP** est un logiciel permettant de créer un serveur **Minecraft Bedrock Edition**.

💡 Il est écrit en **PHP**, ce qui permet :

- Ajouter des plugins facilement  
- Modifier le comportement du serveur  
- Créer des systèmes personnalisés  

---

## ⚠️ Erreurs fréquentes (avec explications)

### ❌ 1. "Server stopped" ou crash au démarrage

**Cause :**
- Version PHP incorrecte  
- Plugin incompatible  

**Solution :**
- Vérifiez la version PHP requise  
- Supprimez les plugins récents  

---

### ❌ 2. Plugin ne fonctionne pas

**Cause :**
- Plugin pas compatible avec votre version  
- Mauvaise installation  

**Solution :**
- Vérifiez la version du plugin  
- Placez-le dans `/plugins`  
- Redémarrez le serveur  

---

### ❌ 3. Impossible de rejoindre le serveur

**Cause :**
- Port fermé  
- Serveur offline  
- Mauvaise IP  

**Solution :**
- Vérifiez que le serveur est lancé  
- Ouvrez le port **19132**  
- Vérifiez votre IP  

---

## 🛠️ Exemple d'installation simple

```bash
# Télécharger PocketMine
wget https://get.pmmp.io

# Lancer l'installation
php start.sh
