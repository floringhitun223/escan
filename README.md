# 🍏 e-scan — Nutriția ta, la o scanare distanță

| <img src="[https://github.com/floringhitun223/escan/blob/main/Media/Captur%C4%83%20de%20ecran%202026-01-14%20204350.png?raw=true" width="250" alt="Home-page"> | <img src="[LINK_POZA_2](https://github.com/floringhitun223/escan/blob/main/Media/Captur%C4%83%20de%20ecran%202026-01-14%20204923.png?raw=true)" width="250" alt="Additives"> | <img src="[LINK_POZA_3](https://github.com/floringhitun223/escan/blob/main/Media/Captur%C4%83%20de%20ecran%202026-01-14%20205003.png?raw=true)" width="250" alt="Settings"> |
> **Transformă-ți telefonul într-un aliat pentru sănătate. Scanează, analizează și alege conștient.**

[![Status: DEMO](https://img.shields.io/badge/status-DEMO-orange?style=for-the-badge)](https://your-download-link.com)
[![Version](https://img.shields.io/badge/version-0.5.2--beta-blue?style=for-the-badge)](https://github.com/username/e-scan)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Cordova-orange?style=for-the-badge)](https://cordova.apache.org/)

---

## 🏗️ Stadiul Proiectului: Versiunea DEMO
În prezent, **e-scan** se află în faza de testare publică. Această versiune este un prototip funcțional menit să demonstreze conceptul principal de scanare și analiză.

* ⚠️ **Atenție:** Pot apărea erori (bug-uri) sau întărzieri în procesarea datelor.
* 📊 **Baza de date:** Momentan limitată la produsele disponibile prin API-ul OpenFoodFacts.
* 🛠️ **Feedback:** Dacă întâmpini probleme, te rugăm să deschizi un [Issue](https://github.com/username/e-scan/issues).

---

## ✨ Povestea Proiectului
Într-o lume plină de etichete descifrate doar de chimiști, **e-scan** aduce claritatea în coșul tău de cumpărături. Aplicația traduce codurile de bare în informații vitale, ajutându-te să eviți aditivii nocivi și să alegi produsele care îți hrănesc cu adevărat corpul.

---

## 🚀 Ce poți face în versiunea DEMO?

### 🔍 Scanare Rapidă
Accesează camera telefonului și scanează codul de bare al oricărui produs alimentar ambalat.

### 🧪 Analiza Ingredientelor
* **Identificare Aditivi:** Vizualizează lista de "E-uri" raportată de baza de date.
* **Scor Nutritiv:** Vezi un scor orientativ de sănătate bazat pe calitatea nutrițională.

### ➕ Contribuție
Dacă un produs nu este găsit, aplicația te ghidează cum să îl adaugi în baza de date globală pentru a-i ajuta pe ceilalți.

---

## 🛣️ Drumul către Versiunea FULL
Lucrăm intens pentru a lansa versiunea completă pe Google Play și App Store. Iată ce va include:
- [ ] **Interfață UI/UX Completă:** Un design modern, fluid și mult mai intuitiv.
- [ ] **Istoric Personalizat:** Jurnalul scanărilor tale pentru a urmări evoluția alegerilor alimentare.
- [ ] **Offline Cache:** Posibilitatea de a vedea produsele scanate anterior fără conexiune la internet.
- [ ] **Alerte Personalizate:** Notificări automate dacă un produs conține alergeni setați de tine (ex: gluten, lactoză).

---

## ⚙️ Ghid de Instalare (Dezvoltare & Testare)

Dacă vrei să testezi versiunea demo pe dispozitivul tău:

### 1. Prerechizite
* Cordova CLI: `npm install -g cordova`
* Android SDK instalat corect pe sistem.

### 2. Configurare Rapidă
```bash
# Clonează proiectul
git clone [https://github.com/username/e-scan.git](https://github.com/username/e-scan.git)
cd e-scan

# Adaugă platforma și pornește demo-ul
cordova platform add android
cordova run android
