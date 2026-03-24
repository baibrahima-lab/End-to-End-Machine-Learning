# ⚡ PowerPulse: Time-Series Forecasting 
### Architecture Prédictive de Consommation Électrique

<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=waving&color=00d2ff&height=200&section=header&text=Projet%20Machine%20Learning&fontSize=50&animation=fadeIn" width="100%" />
</p>

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

## 🌟 Vision du Projet
Comment anticiper la demande énergétique d'un foyer avec précision ? **PowerPulse** déchiffre la "signature énergétique" complexe à partir de millions de mesures infra-horaires. Ce projet transforme des données brutes en insights actionnables pour les Smart Grids de demain.

**👨‍💻 L'Équipe :**
* **Ibrahima BA**
* **Mahamat 

---

## 🛠️ Stack Technique
* **Cœur :** Python 🐍
* **Data Science :** Pandas, NumPy
* **Modélisation :** Scikit-Learn (Régression, Time-Series)
* **Visualisation :** Plotly (Interactivité), Matplotlib & Seaborn
* **Source :** UCI Machine Learning Repository (ID: 235)

---

## 🧬 Le Pipeline "End-to-End"

### 1. Rectification de Signal 🧼
Les données de séries temporelles sont souvent bruitées ou lacunaires. Nous avons implémenté :
* **Fusion temporelle :** Indexation précise par minute.
* **Interpolation Dynamique :** Traitement intelligent des 1,25% de valeurs manquantes pour maintenir la continuité du signal sans introduire de biais.

### 2. Feature Engineering Multidimensionnel 🧠
Extraction de la saisonnalité :
- Cycles journaliers (pics de soirée)
- Tendances hebdomadaires (impact du weekend)
- Variations saisonnières annuelles

### 3. Modélisation Multi-Horizon 📈
Nous avons développé deux moteurs de prédiction :
- ⏱️ **Modèle Minute :** Pour la réactivité en temps réel des infrastructures connectées.
- 📅 **Modèle Day-Ahead :** Pour l'optimisation des achats sur les marchés de gros (**+18.9% de précision** par rapport aux modèles de base).

---

## 💡 Impact & Recommandations

| Axe | Stratégie | Bénéfice |
| :--- | :--- | :--- |
| **OFFRE** | Pilotage via modèle *Day-Ahead* | Réduction des pénalités de déséquilibre financier. |
| **DEMANDE** | Déploiement via *Smart Meters* | Lissage de la courbe de charge par incitations tarifaires. |
| **DURABILITÉ** | Intégration variables météo | Meilleure anticipation de l'apport éolien/solaire local. |

---

## 🚀 Installation & Lancement

```bash
# 1. Cloner le repo
git clone [https://github.com/ton-username/votre-repo.git](https://github.com/ton-username/votre-repo.git)

# 2. Installer les bibliothèques nécessaires
pip install pandas scikit-learn matplotlib seaborn ucimlrepo

# 3. Ouvrir le notebook
jupyter notebook Projet_Machine_Learning.ipynb
