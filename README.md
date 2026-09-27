# 🐧 TuxBot Controller

**Contrôle le vrai TuxBot avec Python !**

Une petite interface qui permet d’envoyer des commandes au logiciel éducatif **TuxBot** (Académie de Nantes) en cliquant automatiquement sur ses boutons.

---

## 🇫🇷 Français

### Présentation

Ce programme permet de contrôler l’application officielle **TuxBot** depuis une interface simple.

Tu peux écrire des commandes comme :

```python
print("avancer")
print("droite")
print("gauche")
print("reculer")
print("go")
```

Le programme détecte la fenêtre TuxBot, déplace la souris et clique sur les bons boutons.

### Fonctionnalités

- Interface graphique claire
- Fenêtre toujours au-dessus de TuxBot
- Calibration facile des boutons
- Support des commandes `print("...")`
- Boutons rapides
- Journal des actions

### Prérequis

- Windows
- Python 3
- TuxBot installé et ouvert

```bash
pip install pyautogui pygetwindow
```

### Utilisation

1. Ouvre **TuxBot**
2. Lance `Lancer_TuxBot_Commandes.bat`
3. Clique sur **Calibrer** (une seule fois)
4. Écris tes commandes ou utilise les boutons

### Fichiers

| Fichier | Description |
|---------|-------------|
| `tuxbot_commandes.py` | Programme principal |
| `Lancer_TuxBot_Commandes.bat` | Lanceur Windows |
| `tuxbot_positions.json` | Positions sauvegardées (créé automatiquement) |

---

## 🇬🇧 English

### Overview

This tool lets you control the official **TuxBot** educational software (from Académie de Nantes) using simple Python-style commands.

You can type commands like:

```python
print("avancer")   # forward
print("droite")    # right
print("gauche")    # left
print("reculer")   # backward
print("go")        # execute
```

The program finds the TuxBot window, moves the mouse and clicks the correct buttons automatically.

### Features

- Clean graphical interface
- Always-on-top window
- Easy button calibration
- Support for `print("...")` commands
- Quick action buttons
- Action log

### Requirements

- Windows
- Python 3
- TuxBot installed and open

```bash
pip install pyautogui pygetwindow
```

### How to use

1. Open **TuxBot**
2. Run `Lancer_TuxBot_Commandes.bat`
3. Click **Calibrer** once to set button positions
4. Type your commands or use the quick buttons

### Files

| File | Description |
|------|-------------|
| `tuxbot_commandes.py` | Main program |
| `Lancer_TuxBot_Commandes.bat` | Windows launcher |
| `tuxbot_positions.json` | Saved positions (auto-generated) |

---

## 🇪🇸 Español

### Presentación

Este programa permite controlar la aplicación educativa oficial **TuxBot** (Académie de Nantes) con comandos simples.

Puedes escribir comandos como:

```python
print("avancer")   # avanzar
print("droite")    # derecha
print("gauche")    # izquierda
print("reculer")   # retroceder
print("go")        # ejecutar
```

El programa detecta la ventana de TuxBot, mueve el ratón y hace clic en los botones correspondientes.

### Características

- Interfaz gráfica sencilla
- Ventana siempre encima de TuxBot
- Calibración fácil de los botones
- Soporte para comandos `print("...")`
- Botones rápidos
- Registro de acciones

### Requisitos

- Windows
- Python 3
- TuxBot instalado y abierto

```bash
pip install pyautogui pygetwindow
```

### Uso

1. Abre **TuxBot**
2. Ejecuta `Lancer_TuxBot_Commandes.bat`
3. Haz clic en **Calibrer** (solo una vez)
4. Escribe tus comandos o usa los botones rápidos

### Archivos

| Archivo | Descripción |
|---------|-------------|
| `tuxbot_commandes.py` | Programa principal |
| `Lancer_TuxBot_Commandes.bat` | Lanzador para Windows |
| `tuxbot_positions.json` | Posiciones guardadas (se crea solo) |

---

## ⚠️ Notes

- This project is **not affiliated** with the official TuxBot developers.
- It works by simulating mouse clicks (UI automation).
- Calibration is required the first time or if you move/resize the TuxBot window.
- Made for educational purposes.

---

**Made with ❤️ for learning programming with TuxBot**
