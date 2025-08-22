# Activité de Marché Swap - Union Européenne de CIC (1992)
## Contexte
En 1992, la banque **Union Européenne de CIC** a créé une activité de marché structurée autour des **swaps** et des **warrants**. Cette initiative visait à répondre aux besoins de couverture et d'arbitrage des clients institutionnels, tout en développant une expertise interne en gestion quantitative des produits dérivés.
---
## Objectifs
- Émettre des swaps pour le compte de clients (banques du groupe, GAN, SOCAPI, etc.)
- Couvrir ces swaps via des instruments dérivés (warrants, futures, options, etc.)
- Réaliser des arbitrages sur les swaps et les options
- Optimiser la gestion des risques (delta, gamma) et la rentabilité
---
## Gestion des Risques
### Modèle Standard de Marché
- Modèle de marché : dXX=μdt+σdWXdX​=μdt+σdW
- Hypothèse d'absence d'arbitrage : le prix actualisé S~t=e−rtStS~t​=e−rtSt​ est une martingale.
- Conséquence : μ=σ22+rμ=2σ2​+r
### Gestion Dynamique de Portefeuille
- Valeur du portefeuille : Vn=V0+∑θi−1(X~i−X~i−1)Vn​=V0​+∑θi−1​(X~i​−X~i−1​)
- Sous les hypothèses standard, E(Vn)=V0E(Vn​)=V0​ : l'espérance de gain est nulle sans apport de stratégie.
### Couverture des Options
- Dans un marché complet, les options sont réplicables par une stratégie de couverture sans risque.
- Prix de l'option = V0V0​ (valeur initiale de la stratégie de couverture)
### Marchés Incomplets
- Dans un modèle réaliste (avec sauts, par exemple), les options ne sont pas parfaitement réplicables.
- On minimise alors le risque quadratique : E[(VT−H)2]E[(VT​−H)2]
- Utilisation de la projection de Kunita-Watanabe et de la dérivée de Malliavin pour la couverture optimale.
---
## Application aux Swaps
### Structure d'un Swap
Un swap est décomposé en :
- Flux certains (monétaire et indexé) : GA+GBGA​+GB​
- Composante de couverture dynamique : ∫θdX∫θdX
- Erreur de couverture : LTLT​ (à minimiser)
### Algèbre des Swaps
- Combinaison linéaire de plusieurs swaps possible.
- Contrainte : E∗(G1+…+Gn)=0E∗(G1​+…+Gn​)=0
### Garanties Optionnelles
- Possibilité d'ajouter des garanties supplémentaires (ex. : performance minimale, seuils de valorisation).
- La valeur de la garantie supplémentaire se traduit par une prime ϵϵ.
---
## Stratégies de Réduction du Risque
### Pour les Warrants et Swaps Émis
- **Gestion du delta** : ajustement de la position en underlying pour neutraliser le risque de prix.
- **Gestion du gamma** : coût lié aux variations du delta, particulièrement important à l'échéance et à la monnaie.
  - Coût = ∑iΓi(ΔXi)2∑i​Γi​(ΔXi​)2
### Techniques Employées
1. **Cappage** : Émission de calls capés (ex. : Call(Exercice) - Call(Exercice * 1.5)) pour limiter l'exposition.
2. **Diversification des Strikes** : Répartition des émissions sur plusieurs strikes pour lisser le gamma.
---
## Bilan Prévisionnel (Hors Bilan)
| Année | Montant (MF) | Cumul (MF) |
|-------|-------------|------------|
| 1     | 600         | 600        |
| 2     | 1 200       | 1 800      |
| 3-4   | 2 000       | 3 800      |
---
## Rentabilité
### Produit Net Bancaire (en millions de francs)
- **Couverture intermédiaire des swaps** : 1,5%×E×λ1,5%×E×λ
- **Adossement définitif** : 0,5%×E×(1−λ)0,5%×E×(1−λ)
- **Gestion du book de futures et d'options** : 10% × M
- **Participation à des émissions indexées** : 0,5%×k×5000,5%×k×500
### Hypothèses
- M = 300
- Année 1 : E=500,k=1,λ=80%E=500,k=1,λ=80%
- Année 2 : E=1200,k=2,λ=30%E=1200,k=2,λ=30%
- Année 3 : E=2100,k=2,λ=50%E=2100,k=2,λ=50%
### Résultats
| Année 1 | Année 2 | Année 3 |
|---------|---------|---------|
| 39      | 42,8    | 56      |
---
## Conclusion
Cette activité de marché swap, pionnière pour l'époque, s'appuyait sur :
- Une **modélisation mathématique avancée** (processus stochastiques, théorie des martingales)
- Une **gestion active des risques** (couverture delta-gamma, diversification)
- Une **offre structurée** pour clients institutionnels
Elle a permis à l'Union Européenne de CIC de développer une expertise en ingénierie financière et de réaliser des opérations significatives en hors-bilan.
---# BUE-Demarage-de-l-activit-Swap-Hybride
Start of the hybride swap activity at BUE in 1992
