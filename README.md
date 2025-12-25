🟦 Mini-projet AWS – Hébergement d’un site web statique avec Amazon S3
🎯 Objectif du projet

Ce mini-projet a pour objectif de démontrer ma capacité à :

utiliser les services AWS de base

comprendre le fonctionnement d’un hébergement web statique

configurer correctement les accès publics et une bucket policy

documenter proprement une solution cloud, étape par étape

Le projet consiste à héberger un site web statique (HTML / CSS) sur Amazon S3, accessible publiquement via une URL AWS.



🛠️ Services AWS utilisés

Amazon S3

Création d’un bucket

Configuration de l’accès public

Hébergement de site statique

Mise en place d’une Bucket Policy




1️⃣ Création du bucket S3

Création d’un bucket unique

Région AWS sélectionnée

Paramètres par défaut conservés

📸 Capture : 1_Create_Bucket


2️⃣ Configuration de l’accès public

Désactivation du blocage des accès publics

Compréhension du risque et de l’objectif (site public)

📸 Capture : 2_Public_Access



3️⃣ Activation de l’hébergement statique

Activation de Static Website Hosting

Définition du document d’index : index.html

📸 Capture : 3_Static_Hosting


4️⃣ Upload des fichiers du site

Upload des fichiers HTML, CSS et images

Respect de l’arborescence du site

📸 Capture : 4_Upload_Files



5️⃣ Mise en place de la Bucket Policy

Autorisation de lecture publique (s3:GetObject)

Accès restreint au bucket concerné uniquement

📸 Capture : 5_Bucket_Policy


6️⃣ Validation du fonctionnement

Accès au site via l’URL S3

Vérification du chargement des pages et des ressources

📸 Capture : 6_Site_Working


✅ Résultat final

Le site est :

accessible publiquement

hébergé intégralement sur Amazon S3

fonctionnel sans serveur (serverless)

👉 Ce projet démontre une première maîtrise du cloud AWS et des bases de l’architecture web statique.
