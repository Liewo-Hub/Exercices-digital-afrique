# 🤖 Case Study 5 — EDG : L'IA qui Détecte 2 000 Fraudes par Mois

> **Durée estimée :** 60 minutes
> **Thème :** Intelligence Artificielle
> **Niveau :** Avancé

[← Case Study 4](./case-study-4-agl-cloud.md) | [Retour au sommaire](./README.md)

---

## L'Histoire

### 2022 : Le Gouffre Financier

EDG (Électricité de Guinée) perd **40% de sa production** :
- 30% = Pertes techniques (câbles vétustes)
- 10% = **FRAUDES !** 🚨

**Le calcul :**

| Élément | Valeur |
|---|---|
| 10% de 500 GWh/mois | 50 GWh volés |
| Valeur mensuelle | 15 milliards GNF |
| **Valeur annuelle** | **180 milliards GNF !** 💸 |

---

## Les 3 Types de Fraudes Principales

**Fraude 1 : Branchement Sauvage**
M. Diallo habite Ratoma. Il branche un câble AVANT le compteur.
→ Électricité gratuite !

**Fraude 2 : Compteur Trafiqué**
Mme Bah achète un aimant puissant sur le marché.
→ Compteur tourne moins vite → Facture divisée par 3 !

**Fraude 3 : Faux Abonnement**
Restaurant utilise le nom d'une mosquée (tarif réduit).
→ Économie de 80% !

---

## La Décision (Mars 2023)

**Solutions essayées et échecs :**

| Solution | Résultat |
|---|---|
| ❌ Patrouilles agents | Trop lent : 50 détections/mois |
| ❌ Dénonciations | Peu fiables |
| ❌ Contrôles aléatoires | 1% des fraudes détectées |

**Solution retenue : Intelligence Artificielle 🤖**

---

## Le Projet IA (Avril–Décembre 2023)

**Partenaire : Schneider Electric + EDG | Budget : 800 millions GNF**

### Phase 1 — Smart Meters (Compteurs Intelligents)

Remplacement de 50 000 compteurs :

| | Ancien compteur | Smart Meter |
|---|---|---|
| Lecture | Agent 1 fois/mois | Toutes les 15 minutes |
| Données temps réel | Aucune | En continu |
| Détection anomalie | Impossible | Automatique |
| Communication | Manuelle | GSM/4G |

Coût : 10 000 GNF/compteur × 50 000 = **500 millions GNF**

---

### Phase 2 — Plateforme IA de Détection

**Signal normal :**
```
Maison Mme Barry (4 personnes)
06h : 2 kWh   (douches, café)
12h : 3 kWh   (cuisine)
20h : 5 kWh   (pic — TV, lumières, cuisine)
23h : 0,5 kWh (veille)
```

**Signal suspect (Fraude détectée) :**
```
Maison M. Diallo (2 personnes déclarées)
06h : 15 kWh ⚠️
12h : 20 kWh ⚠️
20h : 35 kWh 🚨
23h : 25 kWh 🚨

IA : "Consommation × 5 par rapport aux voisins = SUSPECT"
→ Alerte automatique équipe
```

---

### Phase 3 — Les 10 Algorithmes de Détection

| Algorithme | Détection | Signal suspect |
|---|---|---|
| 1. Consommation Zéro | Branchement sauvage | 0 kWh / 3 jours MAIS maison occupée |
| 2. Profil Anormal | Atelier clandestin | Maison 2 chambres = 500 kWh (normale : 150) |
| 3. Baisse Subite | Compteur trafiqué | 200 kWh/mois → soudain 50 kWh (-75%) |
| 4. Pic Nocturne | Activité non déclarée | Restaurant fermé à 23h MAIS 20 kWh entre 23h-6h |
| 5. Tarif Frauduleux | Faux abonnement | Mosquée à 800 kWh/mois (réelle : 50-100 max) |
| … | + 5 autres | … |

---

## Cas Réel — Détection Automatique

```
15 Août 2024, 03h47

🚨 ALERTE IA

Abonné    : Restaurant Le Bon Goût
Adresse   : Matam, Conakry

Anomalie  : Consommation 02h-04h = 45 kWh
            (Restaurant déclaré fermé)
Profil    : +500% vs consommation normale
Proba     : 94%

Analyses automatiques :
✅ Photo satellite : Bâtiment agrandi (non déclaré)
✅ Historique : Conso × 3 en 6 mois
✅ Comparaison 10 restaurants similaires : ANORMAL

Recommandation : VISITE TERRAIN URGENTE
```

**06h00 — Équipe EDG arrive et découvre :**
Restaurant + Cyber café + Atelier soudure cachés !
**Fraude estimée : 25 millions GNF/an**

---

## Les 3 Niveaux d'Alerte

| Niveau | Probabilité | Action automatique |
|---|---|---|
| 1 | 70-85% | Email client + notification agent + visite J+7 |
| 2 | 85-95% | Visite terrain sous 48h + photo compteur obligatoire |
| 3 | >95% | Visite immédiate 24h + coupure préventive + procédure judiciaire |

---

## Les Résultats (Janvier–Juin 2024)

| Indicateur | Avant IA | Après IA | Évolution |
|---|---|---|---|
| Fraudes détectées/mois | 50 | 2 000 | +3900% 🚀 |
| Temps de détection | 6 mois | 24 heures | -99% ⚡ |
| Taux de détection | 5% | 87% | +1640% ✅ |
| Pertes fraude/mois | 15 Mrd GNF | 3 Mrd GNF | -80% 💰 |
| Recouvrement/mois | 500M GNF | 8 Mrd GNF | +1500% 💰 |

**Économies 6 mois : 72 milliards GNF**
**ROI : Moins de 2 mois ! 🎯**

---

## Impact Social Inattendu

**Avant (fraudes non détectées) :**
Clients honnêtes payaient pour les fraudeurs → Factures trop élevées → Colère population.

**Après (fraudes -80%) :**
EDG baisse les tarifs de **15% !**

| Partie | Résultat |
|---|---|
| Clients honnêtes | Paient moins ✅ |
| EDG | Gagne plus ✅ |
| Guinée | Électricité pour tous ✅ |

---

## L'IA Apprend en Continu

**Mars 2024 — Nouvelle Fraude Détectée**

Des fraudeurs intelligents copient un profil normal, mais l'IA détecte :
- Pic exact TOUJOURS à 12h15 (trop précis = robot !)
- Jamais de variation (suspect)

Enquête : Compteur reprogrammé avec Arduino !
**→ IA mise à jour pour détecter les "patterns trop parfaits"**

---

## Leçons pour Entreprises

| # | Leçon |
|---|---|
| 1 | IA > Humain pour tâches répétitives — 1 agent = 2 fraudes/jour ; IA = 2000/mois |
| 2 | Données = Carburant IA — plus de compteurs = IA plus précise (60% → 94%) |
| 3 | ROI ultrarapide — 800M investis, 12 Mrd/mois économisés = rentable en 20 jours |
| 4 | IA éthique — informer les clients et respecter leur consentement |
| 5 | Humain + IA = Parfait — IA détecte, humain vérifie, pas de sanction automatique |

---

## 📋 Exercice Pratique (60 min)

### Étape 1 — Identifier 5 Types de Fraudes (20 min)

| Type de fraude | Fréquence | Perte/an | Détectable par IA ? |
|---|---|---|---|
| Ex: Fausses factures | Fréquent | 50M GNF | OUI (patterns) |
| 1. | | | |
| 2. | | | |
| 3. | | | |
| 4. | | | |
| 5. | | | |

### Étape 2 — Concevoir l'Algorithme (20 min)

**Fraude ciblée :** _______________

**Signaux suspects (5 minimum) :**
1. _______________
2. _______________
3. _______________
4. _______________
5. _______________

**Seuil d'alerte :** _______________

**Action automatique :** _______________

### Étape 3 — Budget et ROI (20 min)

| Poste | Coût estimé |
|---|---|
| Collecte données (capteurs, logiciel) | ___ GNF |
| Plateforme IA (licence/développement) | ___ GNF |
| Formation équipe | ___ GNF |
| **TOTAL INVESTISSEMENT** | **___ GNF** |

**Gains attendus :**
- Fraudes détectées/mois : ___
- Montant récupéré/mois : ___ GNF
- ROI en ___ mois

---

## ✅ Critères de Réussite

- [ ] 5 fraudes identifiées avec pertes estimées
- [ ] 1 algorithme conçu avec 5+ signaux suspects
- [ ] Budget réaliste calculé
- [ ] ROI estimé de façon cohérente

---

[← Case Study 4](./case-study-4-agl-cloud.md) | [Retour au sommaire](./README.md)

*© 2026 [LIEWO Hub](https://www.liewo-hub.com)*
