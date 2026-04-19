# 🔐 Case Study 2 — SGBG : Comment la Cybersécurité a Sauvé des Millions

> **Durée estimée :** 30 minutes
> **Thème :** Cybersécurité
> **Niveau :** Intermédiaire

[← Case Study 1](./case-study-1-orange-money.md) | [Retour au sommaire](./README.md) | [Case Study 3 →](./case-study-3-jumia-big-data.md)

---

## L'Histoire

### Vendredi 15 Mars 2024, 14h30

Ibrahima Sow, Directeur IT de Société Générale Guinée, reçoit une alerte :

> 🚨 *"Activité suspecte détectée : 247 tentatives de connexion en 3 minutes"*

Son cœur s'accélère. C'est une cyberattaque.

---

## Retour en arrière (2022)

### La Situation "Avant"

Société Générale Guinée, comme beaucoup de banques :
- Systèmes vieux de 10-15 ans
- Mots de passe simples (parfois écrits sur post-it !)
- Aucun système de détection d'intrusion
- Formation cybersécurité : **0**

### L'Incident qui a Tout Changé (Mai 2022)

Un employé reçoit cet email :

```
De : rh@societegenerale-guinee.com (FAUX !)
Objet : URGENT - Mise à jour salaire

Cher collaborateur,
Veuillez confirmer vos informations bancaires
en cliquant ici avant 17h.
Sinon votre salaire ne sera pas viré.

Lien : http://sg-guinee-salaires.tk
```

L'employé clique. Entre son login et mot de passe.
**❌ PIÉGÉ !**

---

## La Catastrophe Évitée de Justesse

### Ce qui s'est passé (Mai 2022)

| Heure | Événement |
|---|---|
| 23h00 | Les hackeurs se connectent avec le login volé |
| 23h15 | Tentent de transférer 500 millions GNF vers l'étranger |
| 23h17 | Le système BCRG bloque la transaction (suspect) |
| 23h30 | Ibrahima reçoit alerte et coupe tous les accès |

**Bilan :**
- Argent : 0 GNF perdu (sauvé de justesse !)
- Réputation : Clients paniquent
- Confiance : Ébranlée

> *La Direction décide : "Plus JAMAIS ça !"*

---

## Le Plan de Sauvetage (Juin 2022)

**Budget alloué : 2 milliards GNF**

### Résultat de l'Audit Initial

Une société spécialisée française vient auditer :
- 47 vulnérabilités critiques détectées
- 89% des employés utilisent des mots de passe faibles
- Aucun système anti-intrusion
- Logs gardés seulement 7 jours
- Sauvegardes dans le même bâtiment (risque incendie !)

**Note globale : 2/10 🔴**

---

## Les 5 Actions Mises en Place

### Action 1 — Authentification 2 Facteurs (2FA)

| | Avant | Après |
|---|---|---|
| Accès | Login + Mot de passe | Login + Mot de passe + Code SMS |

**Résultat :** Même si le hackeur vole le mot de passe, il ne peut PAS se connecter sans le téléphone de l'employé.
- Coût : 50 millions GNF
- Impact : **-99% risque piratage comptes**

---

### Action 2 — Formation Obligatoire (Tous les Employés)

**Programme 2 jours par employé :**

- **Jour 1 :** Reconnaître le phishing — 20 exemples d'emails frauduleux, quiz pratique
- **Jour 2 :** Bonnes pratiques — mots de passe forts, gestionnaire (Bitwarden), verrouillage PC

- Coût : 300 millions GNF (150 employés × 2M GNF/personne)
- Résultat : **94% de réussite au test final**

---

### Action 3 — Système de Détection d'Intrusion (IDS)

**Technologie déployée : IBM QRadar**

L'IA surveille 24/7 :
- Connexions inhabituelles *(Conakry puis Paris 5 min après ? SUSPECT !)*
- Transferts anormaux *(Jamais fait, puis 500M GNF ? SUSPECT !)*
- Horaires bizarres *(Connexion à 3h du matin ? SUSPECT !)*

**Cas réel — 12 Septembre 2023, 02h47 :**

```
🚨 ALERTE IDS

Utilisateur : M.Diallo (Comptable)
Action      : Tentative transfert 380 millions GNF
Destination : Compte Nigéria
Heure       : 02h47 (inhabituell — jamais connecté après 18h)

Décision IA : BLOQUER + Alerter Chef Sécurité
```

Le lendemain, M. Diallo confirme qu'il n'a rien fait. Son compte était piraté.
**→ 380 millions GNF sauvés !**

- Coût : 800 millions GNF
- ROI : **Rentabilisé en 1 seule attaque déjouée !**

---

### Action 4 — Sauvegardes Cloud Sécurisées

| | Avant | Après |
|---|---|---|
| Localisation | Serveur local (même bâtiment) | Microsoft Azure (Europe) |
| Fréquence | 1 fois/semaine | 3 fois/jour |
| Récupération | 2 jours | 2 heures |
| Chiffrement | Basique | Niveau militaire |

- Coût : 500 millions GNF/an
- Valeur : **INESTIMABLE**

---

### Action 5 — Pentesting Mensuel

**Principe :** SG Guinée PAYE des hackeurs éthiques pour ATTAQUER la banque.

**Processus mensuel :**
1. Hackeurs éthiques attaquent pendant 1 semaine
2. Ils trouvent les failles
3. Rapport détaillé
4. Équipe IT corrige
5. Re-test le mois suivant

**Évolution des vulnérabilités :**

| Date | Vulnérabilités |
|---|---|
| Mai 2022 | 47 🔴 |
| Juin 2023 | 12 🟠 |
| Mars 2024 | 2 🟢 (mineures) |

- Coût : 50 millions GNF/an
- Valeur : Amélioration continue

---

## Retour au 15 Mars 2024 (L'Attaque)

| Heure | Action |
|---|---|
| 14h30 | Alerte : 247 tentatives de connexion depuis Chine, Russie, Nigéria |
| 14h32 | IDS bloque automatiquement toutes les IPs suspectes |
| 14h32 | Emails envoyés aux clients concernés |
| 15h00 | **Attaque repoussée. 0 GNF volé. 0 compte piraté.** |

**Sans les mesures de 2022, il y aurait eu :**
- 2 milliards GNF volés
- 500+ comptes compromis
- Panique bancaire
- Faillite possible

---

## Bilan Cybersécurité (2022–2024)

| Indicateur | 2022 (Avant) | 2024 (Après) | Évolution |
|---|---|---|---|
| Attaques réussies | 1 | 0 | -100% ✅ |
| Temps de détection | Jamais | 2 minutes | ✅ |
| Temps de réaction | Aucun | 5 minutes | ✅ |
| Employés formés | 0% | 100% | +100% ✅ |
| Argent sauvé (2 ans) | — | 5+ milliards GNF | 💰 |

---

## Le ROI de la Cybersécurité

**Investissement total (2022–2024)**

| Poste | Coût |
|---|---|
| Audit | 200M GNF |
| 2FA | 50M GNF |
| Formation | 300M GNF |
| IDS | 800M GNF |
| Cloud sauvegardes | 1 milliard GNF |
| Pentesting | 100M GNF |
| **TOTAL** | **2,45 milliards GNF** |

**Bénéfices (2022–2024)**
- Attaques déjouées : 5+ milliards GNF sauvés
- Conformité BCRG garantie
- Confiance clients : +25% nouveaux comptes

**ROI : +200% 🚀**

---

## Leçons pour Entreprises

| # | Leçon |
|---|---|
| 1 | La cybersécurité n'est pas une dépense — c'est un investissement |
| 2 | L'humain est le maillon faible — 89% des attaques commencent par un clic |
| 3 | Détection rapide > Prévention parfaite — détecter en 2 min et réagir en 5 |
| 4 | Testez-vous avant qu'un vrai hackeur le fasse — le pentesting, c'est le vaccin |
| 5 | Cloud ≠ Risque — Azure est 1000× plus sécurisé que votre serveur local |

---

## 📋 Exercice Pratique (30 min)

**Mission :** Audit cybersécurité de votre entreprise

### Tableau d'Audit

| Critère | Oui/Non | Note /10 | Action nécessaire |
|---|---|---|---|
| Mots de passe forts obligatoires | | | |
| Authentification 2 facteurs active | | | |
| Formation cybersécurité employés | | | |
| Système détection intrusion | | | |
| Sauvegardes quotidiennes cloud | | | |
| Antivirus à jour sur tous PC | | | |
| Politique d'accès (qui voit quoi) | | | |
| Tests sécurité réguliers | | | |
| Plan de crise cyberattaque | | | |
| Assurance cyber-risque | | | |
| **TOTAL** | | **/100** | |

**Interprétation :**
- 80–100 : ✅ Excellent
- 60–79 : ⚠️ Correct mais améliorations nécessaires
- 40–59 : 🟠 Risqué, actions urgentes
- 0–39 : 🔴 DANGER ! Très vulnérable

### Plan d'Action — 3 Priorités

| # | Action | Budget (GNF) | Délai |
|---|---|---|---|
| 1 | | | mois |
| 2 | | | mois |
| 3 | | | mois |

---

## ✅ Critères de Réussite

- [ ] Audit complété honnêtement
- [ ] Score calculé et interprété
- [ ] 3 actions prioritaires avec budget réaliste
- [ ] Compréhension des 5 piliers cybersécurité

---

[← Case Study 1](./case-study-1-orange-money.md) | [Retour au sommaire](./README.md) | [Case Study 3 →](./case-study-3-jumia-big-data.md)

*© 2026 [LIEWO Hub](https://www.liewo-hub.com)*
