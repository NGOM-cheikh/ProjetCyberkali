# Analyse d'une Infrastructure Existante

## **Description**
Ce projet consiste à analyser une infrastructure existante pour identifier les failles de sécurité et proposer des recommandations, en mettant en pratique les connaissances acquises dans les modules de Cybersécurité et Pentest.

---

## **Table des Matières**
1. [Objectifs](#objectifs)
2. [Travail à Réaliser](#travail-à-réaliser)
   - [Projet Local : SpringBoot](#a-projet-local-springboot)
   - [Pentest du Lab](#b-pentest-du-lab)
3. [Travaux à Rendre](#travaux-à-rendre)

---

## **Objectifs**
- Appliquer les concepts vus dans les cours de **Cybersécurité** et **Pentest**.
- Identifier et analyser les vulnérabilités d'une infrastructure.
- Fournir des recommandations pratiques pour améliorer la sécurité.

---

## **Travail à Réaliser**

### **A. Projet Local : SpringBoot**
1. **Télécharger le projet** :
   - Récupérer le projet fourni par **C. GERMAIN**.
2. **Configurer l'environnement** :
   - Importer le projet **Maven** dans votre IDE.
   - Créer une base de données nommée **biblio** dans MySQL.
3. **Exécuter le projet** :
   - Lancer l'application SpringBoot depuis votre IDE.
4. **Tests des mappings REST** :
   - **Tester le lien principal :**
     - Accédez à `http://localhost:9898/`.
     - Ajouter un utilisateur (username et password) dans la table **User** pour se connecter.
   - **Tester les endpoints suivants** :
     - `http://localhost:9898/api/clients`
     - `http://localhost:9898/client/add`
5. **Pentest des endpoints** :
   - Utiliser des outils comme **Metasploit** et **sqlmap** pour détecter des failles de sécurité.
6. **Rapports et analyses** :
   - Documenter les résultats des tests.
   - Proposer des recommandations pour sécuriser les endpoints.

---

### **B. Pentest du Lab**
1. **VM BIG DATA** :
   - Scanner `node179686-env-1839015-etudiant-d02-01.sh1.hidora.com` à l'aide des outils suivants :
     - **nmap** : pour détecter les ports ouverts et les services en cours d'exécution.
     - **httrack** : pour analyser la structure des sites.
     - **foremost** : pour analyser les données récupérables.
2. **Application Laravel** :
   - Effectuer un audit de l'application hébergée sur `http://45.86.36.184/public/`.
   - Identifier les vulnérabilités potentielles liées à **Apache** et **OpenSSH**

---

## **Technologies et Outils**
- **Framework Backend** : SpringBoot
- **Base de données** : MySQL
- **Outils de Pentest** :
  - Metasploit
  - sqlmap
  - nmap
  - httrack
  - foremost
  - nikto

---

## **Auteurs**
Projet réalisés par Alexis GUIZARD et Cheikh NGOM  dans le cadre d’une formation en Cybersécurité et Pentest 

