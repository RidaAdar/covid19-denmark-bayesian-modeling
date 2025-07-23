# Modélisation bayésienne de l’épidémie de Covid-19 au Danemark (SIRHD)

## Objectif du projet

Ce projet a pour objectif de modéliser et prédire l’évolution de l’épidémie de Covid-19 au Danemark à partir de données publiques, en utilisant un modèle compartimental SIRHD calibré via des méthodes bayésiennes avancées.
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Flag_of_Denmark.svg" width="40" alt="Denmark flag" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/pymc-devs/brand/main/pymc/pymc_logos/PyMC_banner.svg" width="80" alt="PyMC Logo" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://mairiechambaronsurmorge.fr/sitemcsm/wp-content/uploads/2020/03/modele-logo-rouge-covid-19_23-2148501246.jpg" width="100" alt="Covid-19 Virus" />
</p>


---

## Contexte et méthode

- **Modèle SIRHD** : La population est divisée en cinq compartiments : Susceptibles (S), Infectés (I), Rétablis (R), Hospitalisés (H), Décédés (D).
- **Équations différentielles** : La dynamique de l’épidémie est décrite par un système d’équations différentielles.
- **Estimation probabiliste des paramètres** : Utilisation de PyMC et des algorithmes de chaîne de Markov par Monte Carlo (MCMC) pour estimer les paramètres épidémiologiques (taux d’infection, hospitalisation, mortalité, etc.).
- **Analyse de sensibilité** : Évaluation de la robustesse du modèle selon les variations de paramètres.
- **Prédiction et visualisation** : Simulation de scénarios futurs et visualisation de l’incertitude sur les prédictions.

---

## Étapes du notebook

1. **Exploration et préparation des données**
2. **Présentation et implémentation du modèle SIRHD**
3. **Estimation des paramètres par MCMC avec PyMC**
4. **Analyse de sensibilité**
5. **Simulation et prédiction de l’évolution de l’épidémie**
6. **Visualisations avancées**

---

## Fichiers du projet

- `covid19-data-denmark.csv` : Données publiques du Covid-19 au Danemark
- `Projet_MMMI_Final.ipynb` : Notebook Jupyter complet (exploration, modélisation, analyse, visualisation)
- `README.md` : Présentation du projet

---

## Outils et librairies utilisés

- Python 3.x
- PyMC (modélisation bayésienne)
- ArviZ (visualisation et analyse des résultats bayésiens)
- Numpy, Pandas (manipulation de données)
- Scipy (équations différentielles, statistiques)
- Pytensor, Numba (optimisation des calculs)
- Matplotlib (visualisation)

---

## Exécution

**Installer les dépendances :**
```bash
pip install numpy pandas scipy matplotlib pymc arviz pytensor numba
```
Lancer le notebook
```bash
jupyter notebook Projet_MMMI_Final.ipynb
```
