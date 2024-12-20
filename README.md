
```markdown
# **Site E-commerce de Chaussures de Football**

Ce projet est un site e-commerce développé avec **WordPress** et **WooCommerce**, permettant la vente en ligne de chaussures de football. Il est conçu pour offrir une expérience utilisateur intuitive, une gestion avancée des produits (variations de taille, couleur, type de terrain) et des fonctionnalités de paiement sécurisé.

---

## **Fonctionnalités principales**
- Catalogue de produits avec gestion des variations (taille, couleur, type de terrain).
- Paiement sécurisé via PayPal ou Stripe.
- Gestion des utilisateurs avec comptes clients.
- Responsive design optimisé pour les appareils mobiles.
- Options de filtrage et de tri des produits.

---

## **Instructions d'installation**

### **Prérequis**
- Serveur local comme **XAMPP**, **WAMP**, ou tout autre environnement PHP.
- Une base de données MySQL.
- Git installé sur votre machine.
- Navigateur moderne (Chrome, Firefox).

---

### **Étapes pour installer le projet**

#### **1. Cloner le dépôt**
Clonez le projet depuis GitHub :
```bash
git clone https://github.com/oussamaOugouzale/site-ecommerce-footbal.git
```
Accédez au répertoire du projet :
```bash
cd site-ecommerce-footbal
```

#### **2. Configurer le serveur local**
1. Placez les fichiers du projet dans le répertoire public de votre serveur local (par exemple : `htdocs` pour XAMPP).
2. Créez une base de données MySQL nommée `ecommerce` via phpMyAdmin.

#### **3. Importer la base de données**
1. Naviguez dans le dossier `Database` situé dans la racine du projet.
2. Importez le fichier `ecommerce.sql` dans votre base de données via phpMyAdmin :
   - Allez dans phpMyAdmin.
   - Sélectionnez la base de données `ecommerce`.
   - Cliquez sur l’onglet **Importer** et sélectionnez le fichier `ecommerce.sql`.

#### **4. Extraire le dossier des plugins**
1. Naviguez dans le répertoire `wp-content/`.
2. Extrayez le fichier compressé `plugins.zip` dans le dossier `wp-content/plugins/`.

#### **5. Configurer le fichier wp-config.php**
1. Ouvrez le fichier `wp-config.php` à la racine du projet.
2. Mettez à jour les paramètres de connexion à la base de données :
   ```php
   define('DB_NAME', 'ecommerce');
   define('DB_USER', 'root');
   define('DB_PASSWORD', '');
   define('DB_HOST', 'localhost');
   ```
   - **DB_USER** : Utilisateur de MySQL (par défaut : `root`).
   - **DB_PASSWORD** : Mot de passe de MySQL (vide par défaut sur XAMPP).

#### **6. Démarrer le serveur**
- Lancez Apache et MySQL depuis le panneau de contrôle XAMPP/WAMP.
- Accédez au site via `http://localhost/ecommerce`.

#### **7. Accéder à l'administration**
- URL d'accès : `http://localhost/ecommerce/wp-admin`
- Identifiants administrateur :
  - **Nom d'utilisateur :** `oussagou49@gmail.com`
  - **Mot de passe :** `oussamaWordpress@2024`


---

## **Structure du projet**
- **`wp-content/plugins/`** : Contient les plugins nécessaires (compressés dans `plugins.zip`).
- **`wp-content/themes/`** : Contient le thème personnalisé utilisé pour le projet.
- **`Database/database.sql`** : Fichier de base de données pour initialiser le projet.
- **`wp-config.php`** : Fichier de configuration de WordPress.

---

## **Plugins Utilisés**
### Plugins inclus :
1. **WooCommerce** - Gestion des produits et fonctionnalités e-commerce.
2. **Elementor** - Création et personnalisation des pages.
3. **Smart Slider 3** - Ajout de sliders dynamiques.
4. **Contact Form 7** - Formulaire de contact pour la page "Contact".

### Plugins à installer manuellement :
Certains plugins peuvent nécessiter des licences ou un téléchargement séparé. Consultez la documentation de chaque plugin si nécessaire.

---


## **Contact**
Si vous avez des questions, contactez-nous à :  
- **Email :** oussagou49@gmail.com
- **GitHub :** [ousamaOugouzale](https://github.com/oussamaOugouzale)
```

---
