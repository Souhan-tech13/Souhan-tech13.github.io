# Portfolio Professionnel TSSR - Session 2024

Bienvenue sur le dépôt centralisant mon **Dossier de Synthèse de Pratique Professionnelle (DSPP)** pour l'obtention du titre **Technicien Supérieur Systèmes et Réseaux (TSSR-2024)**. Ce dépôt sert de point d'entrée pour explorer l'ensemble de mes compétences en administration système, réseau et sécurité.

## Le Dossier Professionnel (DP)
Ce document de 2024 constitue la preuve formelle de ma capacité à concevoir, déployer et maintenir une infrastructure informatique complexe.

### **[Consulter le Dossier Professionnel Complet (PDF)](./dp_souhan_v3.pdf)**

---

## Projets Majeurs Documentés

### 1. Infrastructure Windows & Services Critiques
Mise en place d'un domaine racine `tssr-vm.tech` hautement disponible.
- **Gestion des Identités :** Architecture Active Directory basée sur l'organigramme métier (Direction, Production, Commercial, Ingénierie, Administratif).
- **Continuité de Service :** Cluster de basculement DHCP (Failover) et sécurisation par PKI à 2 niveaux.
- **Déploiement Industriel :** Industrialisation du parc via WDS et MDT (Conversion d'images .esd en .wim).

### 2. Sécurisation & Accès Distant (pfSense)
Mise en œuvre d'une passerelle de sécurité pour le travail nomade via pfSense 2.7.2.
- **Tunneling SSL :** Configuration d'un VPN Client-to-Site (OpenVPN) sur le tunnel `20.0.10.0/24`.
- **Sécurité PKI :** Authentification forte par certificats (CA-Infomatic-VPN).
- **Filtrage Avancé :** Règles de pare-feu strictes autorisant le flux UDP 1194 (VPN) et le RDP sécurisé (3389).

---

## Stack Technique
- **Systèmes :** Windows Server 2022, Debian 11, Ubuntu 24.04 LTS.
- **Réseau & Sécurité :** pfSense (Installation sur ZFS), OpenVPN, SSL/TLS.
- **Industrialisation :** Microsoft Deployment Toolkit (MDT), DISM, PowerShell.

---

## Méthodologie Professionnelle
Ce portfolio démontre ma maîtrise du cycle de vie d'un projet IT :
1. **Audit & Analyse :** Traduction des besoins de l'organigramme en contraintes techniques.
2. **Design :** Réalisation de schémas de topologie physique et logique.
3. **Implémentation :** Configuration pas-à-pas documentée dans les rapports techniques.
4. **Validation :** Tests de connectivité et vérification des logs de connexion.

---

## Contact
Pour toute opportunité ou échange technique :
- **LinkedIn :** [Souhan Fernandez](https://linkedin.com/in/souhan-fernandez)
---
**Auteur :** Souhan Fernandez - *Session TSSR 2024*
