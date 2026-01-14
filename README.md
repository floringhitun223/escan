# 🍏 e-scan — Nutriția ta, la o scanare distanță

![e-scan Banner](https://images.unsplash.com/photo-1510832198440-a52376950479?ixlib=rb-1.2.1&auto=format&fit=crop&w=1280&q=80)
> **Transformă-ți telefonul într-un aliat pentru sănătate. Scanează, analizează și alege conștient.**

[![Version](https://img.shields.io/badge/version-1.0.0--stable-blue?style=for-the-badge)](https://github.com/username/e-scan)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Cordova-orange?style=for-the-badge)](https://cordova.apache.org/)
[![Database](https://img.shields.io/badge/Data-OpenFoodFacts-red?style=for-the-badge)](https://world.openfoodfacts.org/)

---

## ✨ Povestea Proiectului
Într-o lume plină de etichete descifrate doar de chimiști, **e-scan** aduce claritatea în coșul tău de cumpărături. Aplicația traduce codurile de bare în informații vitale, ajutându-te să eviți aditivii nocivi și să alegi produsele care îți hrănesc cu adevărat corpul.

---

## 🚀 Caracteristici Principale

### 🔍 Scanare Ultra-Rapidă
Folosește motorul optimizat pentru a identifica instantaneu mii de produse alimentare din baza de date globală **OpenFoodFacts**.

### 🧪 Analiza Ingredientelor
* **Identificare Aditivi:** Detectează automat "E-urile" și le clasifică în funcție de gradul de risc.
* **Nutri-Score:** Afișează scorul oficial de sănătate (A-E) pentru o înțelegere rapidă.
* **Alergeni:** Evidențiază substanțele care îți pot provoca reacții adverse.

### 👥 Contribuție Comunitară
Produsul nu există în bază? Îl poți adăuga tu! Fă o poză etichetei și ajută mii de alți utilizatori să mănânce mai sănătos.

---

## 🛠️ Detalii Tehnice

Aplicația este construită pe o arhitectură hibridă, oferind performanță nativă prin **Apache Cordova**.

### Tehnologii folosite:
| Componentă | Tehnologie |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Flexbox/Grid), JS ES6 |
| **Framework** | Apache Cordova |
| **Sursă Date** | API OpenFoodFacts |
| **Scaner** | Cordova BarcodeScanner Plugin |

---

## ⚙️ Ghid de Instalare pentru Dezvoltatori

Dacă dorești să rulezi proiectul local sau să contribui la dezvoltarea lui, urmează pașii de mai jos:

### 1. Prerechizite
* Node.js instalat
* Cordova CLI: `npm install -g cordova`
* Android SDK / Xcode (pentru build-uri native)

### 2. Configurare
```bash
# Clonează repository-ul
git clone [https://github.com/username/e-scan.git](https://github.com/username/e-scan.git)

# Intră în folderul proiectului
cd e-scan

# Instalează platforma dorită
cordova platform add android
# cordova platform add ios

# Build și Run
cordova run android
