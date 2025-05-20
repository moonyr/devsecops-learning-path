# 🛡️ Programme de montée en compétence DevSecOps

Ce programme personnel vise à développer des compétences solides en **Docker**, **CI/CD**, **Sécurité (OWASP, CompTIA)** et **Cloud (AWS)** dans une optique DevSecOps.

---

## ✅ Objectif global

- Acquérir les fondamentaux des conteneurs et du cloud.
- Automatiser les processus de CI/CD avec GitLab.
- Intégrer la sécurité dans la chaîne DevOps (SAST, DAST, SCA).
- Comprendre les risques OWASP et les bases de la cybersécurité (Security+).
- Se préparer aux certifications DevOps et sécurité.

---

## 🟩 Étape 1 – Conteneurs & Sécurité Web de base

### 🎯 Objectifs
- Comprendre les bases de Docker : images, volumes, réseaux, etc.
- Identifier les vulnérabilités critiques OWASP.

### 📚 Ressources
- Livre : `Docker Deep Dive` par Nigel Poulton
- OWASP Top 10 : https://owasp.org/www-project-top-ten/

### 📌 Tâches
- [ ] Lire et expérimenter chaque chapitre de Docker Deep Dive.
- [ ] Installer DVWA ou OWASP Juice Shop pour tester les vulnérabilités (XSS, SQLi...).
- [ ] Créer une image Docker customisée avec un serveur web.
- [ ] Documenter les vulnérabilités OWASP rencontrées.

---

## 🟨 Étape 2 – GitLab CI/CD & automatisation

### 🎯 Objectifs
- Créer des pipelines YAML pour build, test, analyse, déploiement.
- Intégrer des outils de sécurité (SAST/DAST) dans GitLab.

### 📚 Ressources
- `Automating DevOps with GitLab CI/CD` (cours Udemy ou autre)
- Documentation GitLab CI/CD : https://docs.gitlab.com/ee/ci/

### 📌 Tâches
- [ ] Créer un `.gitlab-ci.yml` pour builder une image Docker.
- [ ] Mettre en place un scan SAST (SonarQube, GitLab Code Quality...).
- [ ] Intégrer un scan DAST via OWASP ZAP.
- [ ] Déployer sur un serveur local ou cloud (préparation étape 4).

---

## 🟦 Étape 3 – Sécurité générale (CompTIA Security+)

### 🎯 Objectifs
- Comprendre les principes de la cybersécurité.
- Se préparer à la certification CompTIA Security+ (SY0-701).

### 📚 Ressources
- `CompTIA Security+ Get Certified` (Mike Meyers / Jason Dion)
- Notes OWASP + NIST + SDLC sécurisé

### 📌 Tâches
- [ ] Étudier les domaines (IAM, réseau, chiffrement, menaces...).
- [ ] Faire des quiz de validation.
- [ ] Documenter les notions clés dans un dossier `notes/security+`.

---

## 🟧 Étape 4 – Cloud AWS & certification

### 🎯 Objectifs
- Maîtriser les services AWS essentiels.
- Préparer les certifications :
  - AWS Cloud Practitioner *(optionnelle mais recommandée)*
  - AWS Solutions Architect – Associate

### 📚 Ressources
- `AWS Certified Solutions Architect - Associate` (Stephane Maarek ou autre)
- AWS Skill Builder + labs
- Documentation AWS : https://docs.aws.amazon.com/

### 📌 Tâches
- [ ] Comprendre IAM, EC2, S3, VPC, KMS, ECR, ECS, CloudTrail.
- [ ] Déployer un pipeline GitLab → ECR → ECS.
- [ ] Créer une infra cloud reproducible avec Terraform ou CloudFormation.
- [ ] Passer les certifications (facultatif mais valorisable).

---

## 🧠 À retenir

- Faire le lien entre les outils : **Docker + GitLab CI + Sécurité + AWS**.
- Documenter chaque étape (dossier `/notes` ou Trello perso).
- Ne pas hésiter à pratiquer avec des **labs** ou **challenges CTF**.

---

## 🔒 Bonus – Certifications associées

| Nom                           | Domaine         | Utilité                                      |
|------------------------------|------------------|----------------------------------------------|
| CompTIA Security+            | Cybersécurité     | Base solide, large spectre (IAM, réseau...)  |
| AWS Cloud Practitioner       | Cloud             | Fondamentaux AWS                             |
| AWS Solutions Architect Assoc| Cloud/Infra       | Déploiement cloud, haute dispo, sécurité     |
| GitLab CI/CD Specialist (non officiel) | DevOps  | Automation, pipelines, GitOps                |
| OWASP Top 10 (auto-formation)| Sécurité Web/API  | Risques applicatifs fondamentaux             |

---

