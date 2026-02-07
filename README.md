# 🌲 Pădurea Ioanei

O aplicație web interactivă tip "Surpriză Digitală", creată personalizat pentru o vacanță la Valea Doftanei. Proiectul este un mini-joc de relaxare care combină elemente de gamification cu un design modern și o experiență emoțională personalizată.

🎮 **Joacă aici:** [https://padurea-ioanei.netlify.app](https://padurea-ioanei.netlify.app)

![Game Preview](https://img.shields.io/badge/Status-Live-success) ![Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-blue)

## ✨ Funcționalități

* **Gameplay Interactiv:** Mecanică de tip "Catcher" (prinde obiecte, evită obstacole).
    * ✅ Obiecte bune: Brazi (🌲), Inimi de Aur (💛), Scrisori (💌).
    * ❌ Obstacole: Ploaie (🌧️), Urși (🐻).
* **Dificultate Progresivă:** Viteza de cădere a elementelor crește pe măsură ce scorul utilizatorului avansează.
* **UI/UX Modern:**
    * Design **Glassmorphism** (efect de sticlă mată).
    * Fundal Cinematic cu efect "Ken Burns" (Zoom lent).
    * Feedback haptic (vibrații pe mobil) și vizual (particule/confetti).
* **Elemente "Easter Egg":**
    * Titlu interactiv (declanșează o ploaie de inimi).
    * Scrisoare ascunsă care pune pauză jocului.
* **Sistem de Recompensă:**
    * Voucher digital generat la final.
    * Cronometru real-time (Countdown) până la revedere.
    * Integrare cu WhatsApp pentru revendicarea premiului.

## 🛠️ Tehnologii Folosite

Acest proiect este construit folosind tehnologii web standard, fără framework-uri greoaie, pentru performanță maximă:

* **HTML5** - Structura semantică.
* **CSS3** - Animații complexe (`@keyframes`), Flexbox, Responsive Design.
* **JavaScript (ES6+)** - Logica jocului, manipularea DOM, calculul timpului.
* **Canvas Confetti** - Librărie externă pentru efectele de particule.

## 🚀 Instalare și Rulare Locală

Deoarece este un site static, rularea lui este foarte simplă:

1.  Clonează acest repository:
    ```bash
    git clone [https://github.com/userul-tau/padurea-ioanei.git](https://github.com/userul-tau/padurea-ioanei.git)
    ```
2.  Deschide fișierul `index.html` în orice browser modern.

## 📂 Structura Proiectului

* `index.html` - Conține tot codul (HTML, CSS și JS) într-un singur fișier pentru portabilitate și deployment rapid.
* `assets/` (opțional) - Folder pentru imagini sau resurse audio externe (momentan sunt incluse prin CDN/Link-uri directe).

---

## 👨‍💻 Credite

Crafted with ❤️ & 🧠 by firaCODE

Această aplicație este dezvoltată și menținută de firaCODE. Construim produse digitale care pun accent pe utilitate, confidențialitate și design curat.

👉 Vizitează [firaCODE.ro](https://firacode.ro)
