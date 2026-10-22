# Frontière efficiente de Markowitz (2025)

Construction de la frontière efficiente d'un portefeuille de 4 actions
(Thales, TotalEnergies, Tesla, LVMH) sur l'année 2025, en Python.

**Méthode**
- Rendements logarithmiques journaliers (données yfinance)
- Simulation de 10 000 portefeuilles aux poids aléatoires
- Optimisation sous contraintes (SciPy, SLSQP) : portefeuille au Sharpe maximal et frontière à variance minimale
- Résultats annualisés, taux sans risque de 2 % (€STR)

**Limites** : poids estimés sur une seule année (backward-looking), effet de change EUR/USD non traité.

Le notebook : [efficient_frontier.ipynb](efficient_frontier.ipynb)
