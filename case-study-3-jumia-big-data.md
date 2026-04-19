# 📊 Case Study 3 — Jumia Guinée : Big Data & Prédiction Client

> **Durée estimée :** 45 minutes
> **Thème :** Big Data & Intelligence Artificielle
> **Niveau :** Intermédiaire

[← Case Study 2](./case-study-2-sg-cybersecurite.md) | [Retour au sommaire](./README.md) | [Case Study 4 →](./case-study-4-agl-cloud.md)

---

## L'Histoire

### Décembre 2021 : Le Mystère

Fatoumata, Directrice Marketing chez Jumia Guinée, regarde ses chiffres.

**Problème bizarre :**
- Black Friday : Ventes explosent ! 🚀
- Une semaine après : Chute de 60% 📉
- Pourquoi les clients ne reviennent pas ?

Elle envoie 10 000 SMS promotionnels :
> *"🎉 -30% sur TOUT le site !"*

**Résultat : 2% de clics seulement. Échec total.**

> *Fatoumata :* "Comment Amazon fait pour que je clique toujours sur leurs pubs ?!"
> **La réponse : BIG DATA**

---

## La Découverte (Janvier 2022)

Jumia Africa envoie un expert Data Science : **Moussa**.

Moussa pose 1 question :
> *"Vous envoyez les MÊMES promos à TOUT LE MONDE ?"*

Il compare 3 profils clients :

| Client | Profil | Achats | Fréquence | Panier moyen |
|---|---|---|---|---|
| Aminata, 25 ans | Conakry | Vêtements mode, maquillage, chaussures | 1 fois/semaine | 500K GNF |
| Ibrahim, 45 ans | Labé | Outils bricolage, électroménager | 1 fois/mois | 1,5M GNF |
| Mme Diallo, 60 ans | Kankan | Livres religieux, tapis de prière | 1 fois/trimestre | 200K GNF |

> *Moussa :* "Vous leur envoyez TOUS '-30% sur chaussures Nike'. Normal que ça ne marche pas !"

---

## Le Projet Big Data (Février–Juin 2022)

**Budget : 500 millions GNF**

### Phase 1 — Collecter les Données

Jumia collecte TOUT sur chaque client :
- Produits consultés (même sans acheter)
- Temps passé sur chaque page
- Recherches effectuées
- Heure de connexion préférée
- Appareil utilisé (téléphone/ordinateur)
- Localisation
- Historique achats (2 ans)

**Résultat : 50 millions de données sur 200 000 clients !**

---

### Phase 2 — Analyse avec IA

L'algorithme découvre des **patterns surprenants** :

**Pattern 1 : "Les Jeudis Soir"**
- 40% des achats vêtements = Jeudi 20h-23h
- Raison : Les gens achètent pour sortir le weekend !
- Action Jumia : Promos vêtements les jeudis uniquement

**Pattern 2 : "L'Effet Salaire"**
- Pic achats électroménager : 25-30 du mois
- Raison : Les gens reçoivent leur salaire fin de mois
- Action Jumia : Promos électro fin de mois

**Pattern 3 : "Le Panier Maman"**
- Clients qui achètent couches bébé achètent aussi : lait, vêtements enfant, jouets
- Probabilité : **85% !**
- Action Jumia : Recommandations "Produits complémentaires"

---

### Phase 3 — Personnalisation Totale

L'algorithme crée **12 profils types** :

| Profil | Description |
|---|---|
| Fashionista | Femmes 18-30 ans, mode |
| Bricoleur | Hommes 30-50 ans, outils |
| Gamer | Jeunes, consoles, jeux vidéo |
| Maman Active | Femmes, produits bébé |
| Tech Addict | Smartphones, gadgets |
| Sportif | Équipements sport |
| … | + 6 autres profils |

---

## Exemple Concret — 1 Email, 3 Versions

**Aminata (Fashionista) reçoit :**
```
🎉 Aminata, POUR VOUS :
👗 Robe que vous avez vue hier : -40%
👠 Chaussures assorties : -30%
💄 Maquillage tendance : CADEAU dès 300K
```

**Ibrahim (Bricoleur) reçoit :**
```
🔨 Ibrahim, Promotions Bricolage :
🔧 Perceuse que vous cherchiez : -35%
📦 Pack 100 vis : OFFERT
🛠️ Nouveau marteau disponible
```

**Mme Diallo (Religieuse) reçoit :**
```
📿 Mme Diallo, Nouveautés :
📖 Coran français-arabe : -20%
🧎 Tapis prière qualité : -15%
🕌 Livres religieux : 2 achetés = 1 offert
```

---

## Les Résultats (6 mois après)

| Indicateur | Avant Big Data | Après Big Data | Évolution |
|---|---|---|---|
| Taux d'ouverture emails | 15% | 58% | +287% 🚀 |
| Taux de clic | 2% | 23% | +1050% 🚀 |
| Conversion | 0,5% | 8% | +1500% 🚀 |
| Panier moyen | 450K GNF | 780K GNF | +73% 🚀 |
| Clients récurrents | 18% | 52% | +189% 🚀 |
| CA mensuel | 300M GNF | 950M GNF | +217% 🚀 |

---

## Cas Réels — Prédictions Parfaites

### Cas 1 : Kadiatou et la Poussette

```
25 Mars 2023, 14h — Détection IA :
→ A cherché "poussette bébé" 5 fois cette semaine
→ A consulté 12 produits bébé
→ N'a rien acheté (hésite sur prix)
→ Probabilité achat 48h : 90%

Action automatique 20h :
"Kadiatou, la poussette que vous aimez : -25% AUJOURD'HUI SEULEMENT"
+ "Payez en 3 fois sans frais"

27 Mars, 09h : Kadiatou achète !
Poussette : 480 000 GNF
+ Couches, vêtements bébé, biberon
Total : 780 000 GNF (au lieu de 480K prévu !)
```

### Cas 2 : Déménagement Détecté

Client achète cartons + scotch + matériel emballage.
**Prédiction :** Déménagement imminent.
**Action :** Jumia propose meubles, décoration, électroménager.
**Résultat :** Panier moyen ×5 !

### Cas 3 : Cadeau d'Anniversaire

15 jours avant l'anniversaire (détecté via date de naissance du compte) :
Email automatique : *"🎂 Offre spéciale anniversaire : -30%"*
**Résultat :** 40% des clients achètent pour leur propre anniversaire !

---

## Comment ça Marche Techniquement

```
1. COLLECTE       → Chaque clic enregistré (cookies, app mobile, historique)
        ↓
2. STOCKAGE       → AWS Afrique du Sud — 2 pétaoctets, temps réel
        ↓
3. ANALYSE        → TensorFlow + Python — 50+ modèles prédictifs
        ↓
4. ACTION         → Emails personnalisés auto + notifications push ciblées
```

---

## Leçons pour Entreprises

| # | Leçon |
|---|---|
| 1 | Données = Nouvel Or — on SAIT ce que veut le client avant qu'il le sache |
| 2 | 1 email personnalisé = 10× plus efficace que 100 emails génériques |
| 3 | Commencez simple — historique + âge + localisation suffisent pour débuter |
| 4 | Privacy d'abord — demandez toujours la permission avant d'utiliser les données |
| 5 | L'IA s'améliore avec le temps — plus de données = meilleures prédictions |

---

## 📋 Exercice Pratique (45 min)

### Partie 1 — Identification des Données (15 min)

Listez 10 données à collecter sur vos clients :

| # | Type de donnée | Comment la collecter | Utilité business |
|---|---|---|---|
| 1 | Ex: Historique achats | Système de vente | Prédire prochains achats |
| 2 | | | |
| 3 | | | |
| 4 | | | |
| 5 | | | |
| 6 | | | |
| 7 | | | |
| 8 | | | |
| 9 | | | |
| 10 | | | |

### Partie 2 — Analyse de Patterns (15 min)

Identifiez 3 patterns possibles dans vos données :

**Pattern 1 :** _______________
**Action business :** _______________

**Pattern 2 :** _______________
**Action business :** _______________

**Pattern 3 :** _______________
**Action business :** _______________

### Partie 3 — Plan d'Action (15 min)

| Phase | Action | Outil | Coût | Délai |
|---|---|---|---|---|
| 1 | Collecter données | Ex: Google Analytics | Gratuit | 1 semaine |
| 2 | | | | |
| 3 | | | | |

---

## ✅ Critères de Réussite

- [ ] 10 données identifiées
- [ ] 3 patterns découverts avec actions concrètes
- [ ] Plan 3 phases avec budget réaliste
- [ ] Compréhension éthique : Privacy respectée

---

[← Case Study 2](./case-study-2-sg-cybersecurite.md) | [Retour au sommaire](./README.md) | [Case Study 4 →](./case-study-4-agl-cloud.md)

*© 2026 [LIEWO Hub](https://www.liewo-hub.com)*
