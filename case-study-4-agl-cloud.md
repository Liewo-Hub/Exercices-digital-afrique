# ☁️ Case Study 4 — AGL Conakry Terminal : Le Cloud qui a Transformé un Port

> **Durée estimée :** 40 minutes
> **Thème :** Cloud Computing
> **Niveau :** Intermédiaire

[← Case Study 3](./case-study-3-jumia-big-data.md) | [Retour au sommaire](./README.md) | [Case Study 5 →](./case-study-5-edg-ia.md)

---

## L'Histoire

### 2020 : Le Cauchemar

AGL Conakry Terminal = Plus grand port de Guinée.

**Scénario typique — Jeudi 11 Mars 2020, 08h**

Un bateau MSC arrive avec 200 conteneurs.

**Processus manuel :**
1. Agent papier note : *"Conteneur MSCU2847563 - Riz - 20 tonnes"*
2. Marche 500m vers bureau
3. Saisit dans Excel (vieux PC Windows XP !)
4. Imprime
5. Apporte à la douane
6. Douane vérifie le papier
7. Tampon manuel
8. Retour au conteneur (encore 500m)

**Temps total : 45 minutes PAR conteneur !**

| Calcul | Résultat |
|---|---|
| 200 conteneurs × 45 min | 150 heures = 6 jours complets |
| Bateau bloqué 6 jours | 50 000 USD/jour = **300 000 USD !** |

---

## Le Déclic (Mai 2020)

**COVID-19 frappe.** Le port doit fermer 2 semaines. Équipes en télétravail.

**Problème :** IMPOSSIBLE de travailler à distance !
- Données sur serveur local dans bâtiment fermé
- Aucun accès cloud
- Tout à l'arrêt

**Perte : 2 semaines = 5 millions USD !**

> *Direction MSC décide :* **"PLUS JAMAIS !"**

---

## Le Projet Cloud (Juin 2020 – Mars 2021)

**Partenaire : Microsoft Azure | Budget : 1 milliard GNF**

### Phase 1 — Migration Infrastructure (3 mois)

| Critère | Avant (Sur site) | Après (Cloud Azure) |
|---|---|---|
| Serveurs | 50 serveurs physiques | 0 serveur physique |
| Coupure électricité | Tout s'arrête | Cloud en Europe continue ! |
| Maintenance | Technicien sur place | Automatique (Microsoft) |
| Sauvegarde | 1 fois/semaine | Temps réel |
| Espace | 10 To (limité) | Illimité, évolutif |
| Coût mensuel | 80M GNF | **50M GNF** |

---

### Phase 2 — Application Mobile "AGL Mobile" (2 mois)

**Nouveau processus avec tablette :**

```
Avant (45 min)                    Après (2 min)
─────────────────                 ─────────────
1. Note papier                    1. Scan QR code (2 sec)
2. Marche 500m                    2. Données auto depuis cloud
3. Saisit dans Excel              3. Photo conteneur
4. Imprime                        4. Valide (1 clic)
5. Apporte à douane               5. Douane notifiée instantanément ✅
6. Tampon manuel
7. Retour 500m
```

**-73% de temps par conteneur !**

---

### Phase 3 — Tableau de Bord Temps Réel (1 mois)

**Power BI Dashboard accessible partout.**

Exemple : Directeur du Port en voyage à Dubaï → Ouvre son laptop → Voit EN DIRECT :
- 34 conteneurs traités aujourd'hui
- 5 bateaux en attente
- Délai moyen : 12 min/conteneur
- Équipe la plus rapide : Équipe B (8 min/conteneur)

---

## Les Résultats (2021 vs 2020)

| Indicateur | 2020 (Avant) | 2021 (Après) | Gain |
|---|---|---|---|
| Temps/conteneur | 45 min | 12 min | -73% ⚡ |
| Conteneurs/jour | 150 | 400 | +167% 🚀 |
| Erreurs de saisie | 15/jour | 1/semaine | -95% ✅ |
| Coûts IT | 80M GNF/mois | 50M GNF/mois | -37% 💰 |
| Accessibilité | 8h-18h uniquement | 24/7 partout | ♾️ |
| Temps d'arrêt | 2h/semaine | 5 min/mois | -99% ✅ |

**Gain financier annuel : 500 millions GNF**
**ROI : 6 mois !**

---

## 4 Avantages Cloud Concrets

### Avantage 1 — Accessibilité Mondiale

**Cas réel — Décembre 2021 :**

Directeur AGL en vacances au Maroc. Problème urgent : douane bloque un conteneur suspect.

- Ouvre app depuis Marrakech
- Consulte documents
- Autorise le dédouanement
- **Temps : 5 minutes depuis le Maroc !**

*Avant ? Il devait rentrer à Conakry (vol 6h + trajet).*

---

### Avantage 2 — Collaboration Instantanée

| | Avant | Après (Cloud) |
|---|---|---|
| Flux | Email Excel → Attente → Conflits de version | 1 seul fichier en ligne |
| Collaboration | Impossible en simultané | AGL + MSC modifient en même temps |
| Mises à jour | Décalées | Instantanées |

---

### Avantage 3 — Sécurité Renforcée

**Incident Avril 2019 (Avant Cloud) :**
Incendie dans le bâtiment serveurs → Perte de TOUTES les données 2018 → 6 mois de reconstruction.

**Avec Cloud aujourd'hui :**
Incendie ? Inondation ? Tremblement de terre ?
**Données en sécurité en Europe ✅**

Test de simulation panne complète : **Reprise en 10 minutes !**

---

### Avantage 4 — Évolutivité

**Black Friday 2022 :** Trafic port ×3 (fêtes de fin d'année)

- Avant : Serveurs surchargés → Plantages
- Avec Cloud : Azure ajoute automatiquement la capacité
- Coût : +30% en décembre seulement (pas d'achat de serveurs permanents)

---

## Leçons pour Entreprises

| # | Leçon |
|---|---|
| 1 | Cloud ≠ Compliqué — Microsoft forme en 2 semaines |
| 2 | Commencez petit — migrez 1 application test d'abord |
| 3 | Cloud = Économies — 50M vs 80M/mois + 0 achat serveurs |
| 4 | Disaster Recovery — 6 mois → 10 minutes en cas d'incident |
| 5 | Green IT — datacenter Microsoft à énergie solaire, -80% impact écologique |

---

## 📋 Exercice Pratique (40 min)

**Mission :** Cloud Readiness Assessment de votre entreprise

### Tableau d'Évaluation

| Critère | Oui/Non | Priorité | Action |
|---|---|---|---|
| Données critiques sur serveur local | | | |
| Besoin accès données hors bureau | | | |
| Collaboration avec partenaires externes | | | |
| Coûts IT > 30% budget | | | |
| Peur perdre données (incendie, vol) | | | |
| Équipe IT surchargée maintenance | | | |
| Croissance rapide prévue | | | |
| Besoin flexibilité (scaling) | | | |
| Sécurité actuelle insuffisante | | | |
| Conformité réglementaire stricte | | | |
| **SCORE** | **/10 OUI** | | |

**Interprétation :**
- 7-10 OUI : ☁️ Cloud URGENT
- 4-6 OUI : Cloud recommandé
- 0-3 OUI : Cloud optionnel (mais inévitable)

### Plan de Migration Cloud

| Phase | Durée | Application | Coût estimé |
|---|---|---|---|
| 1 | 1 mois | Migration emails (Office 365) | 5M GNF |
| 2 | | | |
| 3 | | | |

---

## ✅ Critères de Réussite

- [ ] Assessment complété
- [ ] Score interprété
- [ ] Plan migration 3 phases
- [ ] Budget estimé réaliste

---

[← Case Study 3](./case-study-3-jumia-big-data.md) | [Retour au sommaire](./README.md) | [Case Study 5 →](./case-study-5-edg-ia.md)

*© 2026 [LIEWO Hub](https://www.liewo-hub.com)*
