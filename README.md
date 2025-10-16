# VentoyWin11Bypass
VentoyWin11Bypass est un ensemble de fichiers de configuration permettant de contourner les restrictions TPM 2.0, Secure Boot et RAM lors de l'installation de Windows 11 via une clé USB Ventoy. Idéal pour les utilisateurs souhaitant installer Windows 11 sur des machines non compatibles officiellement, sans modifier le matériel ou le BIOS.

# Ventoy Bypass Windows 11 TPM/Secure Boot/RAM

Ce projet fournit les fichiers nécessaires pour contourner les vérifications **TPM 2.0**, **Secure Boot** et **RAM** lors de l'installation de **Windows 11** via une clé USB Ventoy.

---

## 📌 Prérequis
- Une clé USB formatée avec [Ventoy](https://www.ventoy.net/).
- Une image ISO de Windows 11 (x64).
- Les fichiers fournis dans ce dépôt.

---

## 📂 Fichiers inclus
| Fichier | Description |
|---------|-------------|
| `ventoy.json` | Fichier de configuration **obligatoire** pour Ventoy. Permet de charger automatiquement le fichier de contournement. |
| `win11_tpm_bypass.xml` | Fichier XML de configuration pour contourner les vérifications TPM, Secure Boot et RAM. |

---

## 🔧 Installation

### 1. Préparer la clé Ventoy
- Téléchargez et installez [Ventoy](https://www.ventoy.net/) sur votre clé USB.
- Copiez l'ISO de Windows 11 dans la clé Ventoy.

### 2. Ajouter les fichiers de contournement
- Copiez **les deux fichiers** (`ventoy.json` et `win11_tpm_bypass.xml`) **à la racine** de votre clé Ventoy.

### 3. Démarrer l'installation
- Redémarrez votre PC et boot sur la clé Ventoy.
- Sélectionnez l'ISO de Windows 11.
- L'installation devrait démarrer **sans vérifier le TPM, Secure Boot ou la RAM**.

---

## ⚠️ Avertissements
- Ce contournement est destiné à des fins de test et de compatibilité.
- Assurez-vous que votre matériel est compatible avec Windows 11 avant de procéder à l'installation.
- L'utilisation de ces fichiers est sous votre propre responsabilité.

---

## 📜 Licence
Ce projet est sous licence **GNU GENERAL PUBLIC LICENSE**. Vous êtes libre de l'utiliser, le modifier et le partager.
