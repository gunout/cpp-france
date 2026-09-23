<div align="center">

# 🇫🇷 Comptes des partis politiques français

**Dashboard interactif des finances des partis politiques français (2021–2024)**

[![Données CNCCFP](https://img.shields.io/badge/Source-CNCCFP-002395?style=for-the-badge)](https://www.data.gouv.fr/datasets/comptes-des-partis-et-groupements-politiques)
[![Data.gouv.fr](https://img.shields.io/badge/Data.gouv.fr-Officiel-ED2939?style=for-the-badge)](https://www.data.gouv.fr)
[![Licence Ouverte](https://img.shields.io/badge/Licence-Ouverte%202.0-00A650?style=for-the-badge)](https://www.etalab.gouv.fr/licence-ouverte-open-licence)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-4.4-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-002395?style=flat-square&logo=github)](https://gunout.github.io/cpp-france/)
[![Dernière mise à jour](https://img.shields.io/github/last-commit/gunout/cpp-france?style=flat-square&color=ED2939)](https://github.com/gunout/cpp-france/commits)
[![Partis analysés](https://img.shields.io/badge/Partis%20analysés-36-002395?style=flat-square)]()
[![Graphiques](https://img.shields.io/badge/Graphiques-31-ED2939?style=flat-square)]()
[![Taille du repo](https://img.shields.io/github/repo-size/gunout/cpp-france?style=flat-square&color=002395)](https://github.com/gunout/cpp-france)
[![Licence MIT](https://img.shields.io/github/license/gunout/cpp-france?style=flat-square&color=00A650)](https://github.com/gunout/cpp-france/blob/main/LICENSE)

**[🔗 Voir le dashboard en ligne](https://gunout.github.io/cpp-france/)** · **[📊 Source des données](https://www.data.gouv.fr/datasets/comptes-des-partis-et-groupements-politiques)** · **[🐛 Signaler un bug](https://github.com/gunout/cpp-france/issues)**

</div>

---

## 📖 À propos

Ce projet met en forme **les comptes financiers officiels des partis politiques français** publiés par la **CNCCFP** (Commission nationale des comptes de campagne et des financements politiques), accessibles en open data sur **data.gouv.fr**.

Il propose un **dashboard interactif** (HTML/CSS/JS pur, aucune dépendance backend) permettant d'explorer, comparer et exporter ces données, avec une identité visuelle **Bleu-Blanc-Rouge**.

> ⚠️ **Les données sont celles des comptes consolidés déposés à la CNCCFP** — elles ne contiennent ni le nombre d'adhérents, ni les scores électoraux, ni les élus locaux. Ces informations ne sont pas du ressort de la CNCCFP.

---

## ✨ Fonctionnalités

| 📊 Analyse par parti | ⚖️ Comparaison multi-partis |
|---|---|
| 8 indicateurs clés (KPI) par exercice | 2 à 4 partis superposés |
| Produits vs charges | 8 graphiques d'évolution |
| Résultat net | 2021 → 2024 |
| Aide publique vs cotisations | Couleurs officielles par parti |
| Structures (produits/charges) | |
| Endettement & fonds propres | |

| 📐 Ratios financiers | 🏆 Classement dynamique |
|---|---|
| Dépendance à l'aide publique | 10 indicateurs au choix |
| Part des salaires | Top 10 / 20 / tous |
| Part de la communication | Barres horizontales animées |
| Ratio dettes/produits | Filtre par année |
| Taux de résultat net | |
| Part des cotisations | |

| 🔍 Analyse par poste | 🏦 Bilan détaillé |
|---|---|
| 17 postes comptables | Composition des dettes (banques, particuliers, partis) |
| Comparaison jusqu'à 6 partis | Fonds propres vs provisions |
| Évolution pluriannuelle | Actif vs passif |
| | Liquidités |

| 💾 Export |
|---|
| JSON complet |
| CSV (compatible Excel) |
| Copie presse-papier |

---

## 🚀 Démo en ligne

**[https://gunout.github.io/cpp-france/](https://gunout.github.io/cpp-france/)**

> 💡 Aucune installation requise — le dashboard tourne entièrement dans le navigateur.

---

## 🏗️ Stack technique

| Composant | Technologie |
|-----------|-------------|
| **Frontend** | HTML5 · CSS3 · JavaScript vanilla |
| **Graphiques** | Chart.js 4.4 + plugins datalabels et annotation |
| **Extraction** | Python 3.10+ · pandas · requests |
| **Source** | API data.gouv.fr |
| **Hébergement** | GitHub Pages |

---

## 📁 Structure du projet

| Fichier | Description |
|---------|-------------|
| index.html | Dashboard interactif (HTML/CSS/JS) |
| partis_comptes_filtered.json | Données des 36 partis politiques (2021-2024) |
| LICENSE | Licence MIT |
| README.md | Ce fichier |

---

## 📊 Source des données

|  |  |
|---|---|
| **Producteur** | CNCCFP (Commission nationale des comptes de campagne et des financements politiques) |
| **Cadre légal** | Article 11-7 de la loi du 11 mars 1988 (transparence financière de la vie politique) |
| **Référentiel comptable** | Règlement ANC n° 2018-03 (à partir de 2018) |
| **Diffuseur** | data.gouv.fr |
| **Licence** | Licence Ouverte / Open Licence 2.0 (Etalab) |
| **Couverture** | 4 exercices (2021-2024) · 36 partis significatifs |

### Partis inclus

Les partis dont le total de produits 2024 dépasse **500 000 €** ou figurant parmi les 15 formations majeures :

RN · PCF · PS · EELV · LR · Modem · Renaissance · LFI · Reconquête · Horizons · Ensemble · UDI · LO · NPA · Les Patriotes · + 21 autres

---

## 🖥️ Utilisation en local

### Option 1 — Consultation directe (rapide)

Ouvre un terminal dans le dossier du projet et exécute :

    git clone https://github.com/gunout/cpp-france.git
    cd cpp-france
    python3 -m http.server 8080

Puis ouvre ton navigateur à l'adresse : **http://localhost:8080**

### Option 2 — Régénérer les données

Installation des dépendances Python :

    pip install pandas requests

Puis, dans l'ordre :

    python3 scrap_partis.py
    python3 filter_partis.py
    python3 -m http.server 8080

La première commande produit `partis_comptes.json` (718 partis).
La deuxième produit `partis_comptes_filtered.json` (36 partis significatifs).

---

## 📸 Aperçu

> Ajouter ici une capture d'écran du dashboard : onglet Parti avec le RN sélectionné.

Pour ajouter une capture :

1. Faire une capture d'écran du dashboard
2. La placer dans `docs/screenshot.png`
3. Remplacer la ligne ci-dessus par :

    ![Aperçu du dashboard](docs/screenshot.png)

---

## 🔄 Mise à jour des données

Les comptes des partis sont publiés **annuellement** par la CNCCFP (généralement à l'été pour l'exercice précédent).

Pour mettre à jour :

    python3 scrap_partis.py
    python3 filter_partis.py
    git add partis_comptes_filtered.json
    git commit -m "data: mise à jour exercice 2025"
    git push

GitHub Pages redéploie automatiquement.

---

## ⚠️ Avertissements

- **Données brutes** : aucun retraitement statistique n'est appliqué (pas de déflation, pas de consolidation de groupes politiques).
- **Structure comptable** : le référentiel ANC 2018-03 s'applique à partir de 2018. Les exercices antérieurs ne sont pas inclus dans ce dashboard.
- **Partis consolidés** : certains partis (comme le PCF) consolident les comptes de structures associées, ce qui peut expliquer des totaux plus élevés.
- **Ce projet n'a aucune affiliation politique** — il s'agit d'un outil d'analyse de données publiques.

---

## 🤝 Contribution

Les contributions sont bienvenues !

1. Fork le projet
2. Créer une branche : `git checkout -b feature/amelioration`
3. Commit : `git commit -m "feat: ajout d'un graphique radar"`
4. Push : `git push origin feature/amelioration`
5. Ouvrir une Pull Request

### Idées d'amélioration

- [ ] Carte de France des résultats électoraux par département (module E)
- [ ] Comparaison année N vs N-1 (radar, waterfall)
- [ ] Export PDF automatique
- [ ] Mode sombre
- [ ] Ajout d'exercices 2018-2020 (format ancien)
- [ ] Workflow GitHub Actions pour mise à jour automatique

---

## 📜 Licence

- **Code** : MIT
- **Données** : Licence Ouverte 2.0 (Etalab)

---

## 🙏 Remerciements

- **CNCCFP** pour la publication des comptes
- **Etalab / data.gouv.fr** pour la plateforme open data
- **Chart.js** pour la bibliothèque de graphiques
- La communauté open data française 🇫🇷

---

<div align="center">

**⭐ Si ce projet vous est utile, n'hésitez pas à lui mettre une étoile !**

Fait avec ❤️ et beaucoup de café ☕

[⬆ Retour en haut](#-comptes-des-partis-politiques-français)

</div>

---

<div align="center">

### 🇫🇷 Gunout · 2026

![Made in France](https://img.shields.io/badge/Made_in-France-002395?style=flat-square&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzAwMjM5NSIvPjxyZWN0IHdpZHRoPSI5MDAiIGhlaWdodD0iNDAwIiB5PSIxMDAiIGZpbGw9IiNmZmYiLz48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjIwMCIgeT0iNDAwIiBmaWxsPSIjZWQyOTM5Ii8+PC9zdmc+)
![GitHub](https://img.shields.io/badge/GitHub-gunout-181717?style=flat-square&logo=github&logoColor=white)
![Year](https://img.shields.io/badge/2026-ED2939?style=flat-square&labelColor=FFFFFF)

<sub>© 2026 <strong>Gunout</strong> — Tous droits réservés.</sub>

</div>

