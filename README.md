# Analyseur de spectre audio en temps réel

Ce projet capture le son du microphone, calcule la transformée de Fourier rapide (FFT) et affiche le spectre audio en temps réel.

---

## Objectif

- Capturer un flux audio depuis le micro.
- Appliquer une fenêtre (Hann, Hamming, etc.) et calculer la FFT.
- Afficher le spectre de fréquences en temps réel avec `matplotlib` ou `pyqtgraph`.

---

## Installation

### 1. Cloner le dépôt

```bash
git clone https://github.com/ton-utilisateur/realtime_audio_spectrum.git
cd realtime_audio_spectrum
```

### 2. Créer un environnement virtuel
1. Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```
2. Windows (Powershell)
```bash
python -m venv venv
venv\Scripts\activate
```

3. Installer les dépendances
```bash
pip install -r requirements.txt
```


### 3. Exécution
```bash
python src/main.py
```

### 4. Améliorations possibles

Ajouter un affichage temps-fréquence (spectrogramme).

Détection automatique de la note jouée.

Version C++ + SDL2 pour un rendu plus fluide.

Interface graphique avec PyQt5.


### 5. Auteur
Projet réalisé par Joigneau Valentin
Junior Developer — Python / C++