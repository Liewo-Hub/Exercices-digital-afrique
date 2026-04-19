# 📚 Exercices Pratiques — Digital & Data en Afrique Francophone

> Réponses détaillées des 5 exercices pratiques sur la transformation digitale, la cybersécurité, le Big Data, le Cloud et l'IA appliqués au contexte guinéen et africain.

---

## 📋 Exercice 1 : Orange Money — Diagnostic (15 min)

**Mission :** Évaluer si lancer Orange Money en 2015 est une bonne idée

### Tableau diagnostic

| Critère | Analyse | Note /10 |
|---|---|---|
| Taille du marché | Population adulte Guinée 2015 = 12M personnes. 70% sans banque = 8,4 millions. Marché énorme inexploité ! | 9/10 |
| Technologie disponible | Réseau mobile couvre 85% du territoire. 3G disponible dans les villes. Infrastructure télécoms correcte. | 7/10 |
| Concurrence | En 2015 : 0 concurrent majeur. Quelques services bancaires mobiles limités. Aucun acteur dominant. | 10/10 |
| Réglementation | BCRG autorise le mobile money. Directive UEMOA favorable. Cadre légal clair. | 9/10 |
| Coût lancement | Estimation : 5-8 milliards GNF (Infrastructure 3 Mrd, Formation 1 Mrd, Marketing 2 Mrd, Licences 1-2 Mrd) | 6/10 |
| ROI attendu | Rentable en 18-24 mois. Revenus commissions : 2% sur 50 Mrd/mois = 1 Mrd/mois. Break-even rapide. | 8/10 |

**Score total : 49/60 = 82%**

### ✅ Décision finale : LANCER

**1. Marché énorme inexploité**
- 8,4 millions de personnes sans accès bancaire = opportunité gigantesque
- Besoin réel et quotidien : envoyer argent famille, payer factures
- Pas de concurrent dominant = fenêtre d'opportunité unique

**2. Infrastructure technologique prête**
- 85% couverture réseau mobile déjà existante
- Pas besoin de construire infrastructure de zéro
- Partenariat avec Orange (groupe international) = expertise technique garantie

**3. Modèle économique viable**
- Commission 1-2% sur chaque transaction = revenus récurrents
- Coût marginal faible une fois plateforme lancée
- ROI en moins de 2 ans = projet rentable rapidement

**4. Soutien réglementaire**
- BCRG favorable au mobile money (inclusion financière)
- Cadre légal clair et sécurisé
- Alignement avec politique gouvernementale

**5. Timing parfait**
- Concurrent absent = first-mover advantage
- Population jeune habituée au mobile
- Urbanisation croissante = besoin transferts argent

---

## 📋 Exercice 2 : SG Guinée — Audit Cybersécurité (30 min)

**Mission :** Audit cybersécurité d'une entreprise moyenne

### Tableau audit

| Critère | Statut | Note /10 | Action nécessaire |
|---|---|---|---|
| Mots de passe forts obligatoires | ⚠️ Partiel | 5/10 | Imposer 12+ caractères, majuscules, chiffres, symboles |
| Authentification 2 facteurs | ❌ Non | 0/10 | **URGENT** : Déployer 2FA sur tous les comptes critiques |
| Formation cybersécurité employés | ❌ Non | 0/10 | **URGENT** : Formation obligatoire 2 jours/employé |
| Système détection intrusion | ❌ Non | 0/10 | **URGENT** : Installer IDS (QRadar ou similaire) |
| Sauvegardes quotidiennes cloud | ⚠️ Hebdo local | 3/10 | Migrer vers cloud avec backup 3×/jour |
| Antivirus à jour sur tous PC | ✅ Oui | 8/10 | Maintenir mises à jour automatiques |
| Politique d'accès (RBAC) | ⚠️ Partiel | 4/10 | Définir rôles et permissions |
| Tests sécurité réguliers | ❌ Non | 0/10 | Pentesting mensuel obligatoire |
| Plan de crise cyberattaque | ❌ Non | 0/10 | **URGENT** : Créer playbook incident response |
| Assurance cyber-risque | ❌ Non | 0/10 | Souscrire police assurance cyber |

**Score total : 20/100 = 20%**

### 🔴 Interprétation : DANGER ! TRÈS VULNÉRABLE

### Plan d'action — 3 priorités

**Action 1 : Authentification 2 facteurs (2FA)**
- Budget : 30 millions GNF | Délai : 1 mois
- Impact : Réduit 99% risque piratage comptes
- Outils : Google Authenticator ou Duo — obligatoire pour Email, VPN, systèmes critiques

**Action 2 : Formation cybersécurité obligatoire**
- Budget : 100 millions GNF (50 employés × 2M GNF) | Délai : 2 mois
- Impact : 89% des attaques commencent par erreur humaine
- Programme : Jour 1 — détecter phishing / Jour 2 — bonnes pratiques / Quiz 80% minimum

**Action 3 : Système détection intrusion (IDS)**
- Budget : 500 millions GNF | Délai : 3 mois
- Impact : Détection attaques en 2 minutes (vs jamais actuellement)
- Solution : IBM QRadar ou Splunk — surveillance 24/7, alertes instantanées

---

## 📋 Exercice 3 : Jumia — Stratégie Big Data (45 min)

### Partie 1 — 10 données à collecter

| # | Type de donnée | Comment la collecter | Utilité business |
|---|---|---|---|
| 1 | Historique achats complet | Base de données e-commerce | Prédire prochains achats (85% précision) |
| 2 | Produits consultés sans achat | Cookies + Analytics | Identifier intentions d'achat |
| 3 | Temps passé par page | Google Analytics | Mesurer intérêt réel produit |
| 4 | Heure de connexion préférée | Logs serveur | Envoyer promos au bon moment |
| 5 | Appareil utilisé (mobile/PC) | User-Agent HTTP | Optimiser UX par device |
| 6 | Localisation géographique | IP + GPS (avec consentement) | Offres localisées |
| 7 | Recherches effectuées | Barre de recherche site | Comprendre besoins non satisfaits |
| 8 | Taux d'ouverture emails | SendGrid / Mailchimp | Personnaliser communications |
| 9 | Produits ajoutés au panier (non achetés) | Tracking e-commerce | Remarketing ciblé |
| 10 | Avis et notes produits | Base de données reviews | Segmenter clients actifs/passifs |

### Partie 2 — 3 patterns découverts

**Pattern 1 : "Le Jeudi Soir Mode"**
- Observation : 45% des achats vêtements se font jeudi 19h-23h
- Explication : Veille weekend + salaire reçu fin de mois
- Action : Promos mode exclusives jeudi 18h-minuit + email "Flash Sale" à 17h30
- Résultat attendu : Ventes mode ×3 le jeudi

**Pattern 2 : "Le Panier Maman"**
- Observation : Client achète couches bébé → 85% achète aussi lait + lingettes
- Explication : Besoins groupés, commodité, même urgence temporelle
- Action : Bundle promo Couches + Lait + Lingettes -15% + popup intelligent
- Résultat attendu : Panier moyen ×2,5

**Pattern 3 : "Anniversaire Anticipé"**
- Observation : 15 jours avant anniversaire → recherches cadeaux/gâteau
- Explication : Préparation événement, budget disponible, timing prévisible
- Action : Email automatique J-15 avec suggestions personnalisées -20%
- Résultat attendu : 40% conversions clients anniversaire

### Partie 3 — Plan d'action

| Phase | Action | Outil | Coût | Délai |
|---|---|---|---|---|
| 1. Collecte | Tracking complet | Google Analytics 360 | 5M GNF/an | 1 semaine |
| 1. Collecte | Consentement RGPD | OneTrust / Cookiebot | 2M GNF/an | 3 jours |
| 1. Collecte | Base données centralisée | PostgreSQL + Redis | 10M GNF | 2 semaines |
| 2. Analyse | Plateforme Big Data | BigQuery ou AWS Redshift | 15M GNF/an | 1 mois |
| 2. Analyse | Machine Learning | TensorFlow + Python | 30M GNF | 2 mois |
| 2. Analyse | Dashboard | Tableau ou Power BI | 8M GNF/an | 2 semaines |
| 3. Action | Marketing automation | HubSpot ou Mailchimp Pro | 12M GNF/an | 1 mois |
| 3. Action | Tests A/B | Optimizely | 5M GNF/an | 1 mois |
| 3. Action | Formation équipe | Consultant externe | 10M GNF | 1 semaine |

**Coût total année 1 : ~100 millions GNF**
**ROI attendu : +200% dès la 1ère année** (taux conversion +50%, panier moyen +40%)

---

## 📋 Exercice 4 : AGL — Cloud Readiness Assessment (40 min)

### Tableau Cloud Readiness

| Critère | Statut | Priorité | Action |
|---|---|---|---|
| Données critiques sur serveur local | ✅ Oui | 🔴 HAUTE | Migrer vers Azure/AWS |
| Besoin accès données hors bureau | ✅ Oui | 🔴 HAUTE | Cloud = accès 24/7 partout |
| Collaboration avec partenaires externes | ✅ Oui | 🟡 MOYENNE | SharePoint Online ou Google Workspace |
| Coûts IT > 30% budget | ✅ Oui (35%) | 🔴 HAUTE | Cloud réduit coûts 30-40% |
| Peur perdre données (incendie, vol) | ✅ Oui | 🔴 HAUTE | Cloud = backup Europe sécurisé |
| Équipe IT surchargée maintenance | ✅ Oui | 🟡 MOYENNE | Cloud = maintenance automatique |
| Croissance rapide prévue | ✅ Oui (+50%/an) | 🔴 HAUTE | Cloud scaling automatique |
| Besoin flexibilité (scaling) | ✅ Oui | 🔴 HAUTE | Augmenter/réduire capacité en 1 clic |
| Sécurité actuelle insuffisante | ✅ Oui | 🔴 HAUTE | Azure = sécurité militaire |
| Conformité réglementaire | ⚠️ Partiel | 🟡 MOYENNE | Vérifier certifications ISO 27001 |

**Score : 9,5/10 — ☁️ CLOUD URGENT ET NÉCESSAIRE**

### Plan migration cloud — 3 phases

**Phase 1 : Emails & Collaboration (1 mois)**
- Migration emails vers Office 365
- Coût : 5M GNF setup + 500K GNF/mois
- Bénéfices : Accès partout, OneDrive 1TB/utilisateur, Teams, zéro maintenance

**Phase 2 : Données & Fichiers (2 mois)**
- Migration serveurs fichiers vers SharePoint Online
- Coût : 10M GNF migration + 1M GNF/mois
- Bénéfices : Backup 3×/jour, versioning, partage sécurisé, accès mobile

**Phase 3 : Applications Métier (3 mois)**
- ERP/CRM vers Azure Cloud
- Coût : 30M GNF migration + 5M GNF/mois
- Bénéfices : 99,9% disponibilité, scaling automatique, disaster recovery

**Budget total année 1 : 123M GNF**
**Économies année 1 : 85M GNF** (serveurs, électricité, licences, salaire admin)
**ROI : Positif dès année 2 !**

---

## 📋 Exercice 5 : EDG — Concevoir une IA Anti-Fraude (60 min)

### Partie 1 — 5 types de fraudes identifiées

| Type de fraude | Fréquence | Perte/an | Détectable par IA |
|---|---|---|---|
| Branchement sauvage (avant compteur) | Très fréquent | 80 Mrd GNF | ✅ OUI |
| Compteur trafiqué (aimant) | Fréquent | 45 Mrd GNF | ✅ OUI |
| Faux abonnement (tarif réduit) | Moyen | 30 Mrd GNF | ✅ OUI |
| Vol direct câbles (revente cuivre) | Rare | 15 Mrd GNF | ⚠️ DIFFICILE |
| Consommation non déclarée (atelier) | Fréquent | 30 Mrd GNF | ✅ OUI |

**Total pertes : 200 Mrd GNF/an = 10% de la production**

### Partie 2 — Algorithme de détection

**Fraude ciblée : Branchement sauvage**

5 signaux suspects :
1. Consommation = 0 kWh pendant 3+ jours consécutifs
2. Maison visiblement occupée (image satellite, conso eau)
3. Historique normal avant (150 kWh/mois → soudain 0, baisse >95%)
4. Voisins directs à consommation normale (comparaison 5 voisins)
5. Quartier connu pour fraudes (base données historique par zone)

**Seuil d'alerte : 4/5 signaux = probabilité fraude ≥ 90%**

Actions automatiques :
- **Niveau 1** (70-85%) : Email client + notification agent + visite J+7
- **Niveau 2** (85-95%) : Visite terrain sous 48h + photo compteur
- **Niveau 3** (>95%) : Visite immédiate 24h + coupure préventive + procédure judiciaire

### Partie 3 — Budget et ROI

| Poste | Coût |
|---|---|
| 50 000 smart meters @ 10K GNF | 500M GNF |
| Installation (main d'œuvre) | 100M GNF |
| Réseau communication GSM/4G | 50M GNF |
| Licence logiciel (Schneider Electric) | 200M GNF/an |
| Serveurs cloud (Azure) | 50M GNF/an |
| Développement algorithmes personnalisés | 100M GNF |
| Formation 50 agents terrain | 20M GNF |
| Formation 5 data scientists | 30M GNF |
| **TOTAL INVESTISSEMENT** | **1,05 milliard GNF** |

**Gains attendus :**
- Fraudes détectées : 50/mois → 2 000/mois (×40 !)
- Récupération : 2 000 × 500K GNF = **1 Mrd GNF/mois**
- ROI en **1 mois et 2 jours** 🚀
- Gains année 1 : **14 Mrd GNF** (récupération + effet dissuasif)
- **ROI = 1 233%**

---

## 🎓 Conclusion

### Ce que vous avez appris

| Exercice | Compétence clé |
|---|---|
| ✅ Orange Money | Évaluer opportunité marché + timing |
| ✅ SG Cybersécurité | Auditer vulnérabilités + prioriser actions |
| ✅ Jumia Big Data | Identifier patterns + créer stratégie data |
| ✅ AGL Cloud | Évaluer readiness + planifier migration |
| ✅ EDG IA | Concevoir algorithme + calculer ROI précis |

### Compétences acquises
- Analyse coût-bénéfice
- Priorisation budgétaire
- Calcul ROI réaliste
- Planification par phases
- Détection de patterns data

---

*Contenu produit dans le cadre des formations [Liewo Hub](https://www.liewo-hub.com) — Transformation Digitale & Data Analytics pour l'Afrique Francophone.*
