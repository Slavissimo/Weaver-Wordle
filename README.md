<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=e8c547&height=200&section=header&text=TKÁČ&fontSize=90&fontColor=0f0e11&fontAlignY=38&desc=Slovenský%20Weaver%20Wordle&descAlignY=58&descColor=0f0e11" />

[![Live Demo](https://img.shields.io/badge/🌐%20Hrať%20online-saloncuk.sk/tkac-e8c547?style=for-the-badge&logoColor=black)](https://saloncuk.sk/tkac)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 🧵 O hre

**Tkáč** je slovenská verzia slovnej hry [Weaver](https://wordwormdormdork.com/). Cieľom hráča je dostať sa zo **štartovacieho slova** na **cieľové slovo** – krok za krokom, pričom každý krok zmení práve **jedno písmeno**.

```
BASA → JASA → JAVA → KAVA → KALA → KOLA
```

Všetky slová musia byť platné slovenské slová. Žiadne nápovedy – hráč hádá naslepo.

---

## 🎮 Funkcie

- 🇸🇰 **Slovenský slovník** – 3 300+ štvorpísmenových slov z oficiálneho hunspell slovníka
- 🔗 **25+ herných párov** algoritmicky overených BFS algoritmom (min. 3–6 krokov)
- ⌨️ **Slovenská klávesnica** s plnou diakritikou (ä, ľ, ŕ, ď, ť, ň, ...)
- 📊 **Štatistiky** – výhry, séria, najlepší výsledok, počet ťahov
- 🎨 **Animácie** – flip, shake, bounce
- 🌙 **Tmavý dizajn** konzistentný s ostatnými hrami na saloncuk.sk
- 📱 **Responzívny** – funguje na mobile aj desktope

---

## 🧠 Ako fungujú herné páry

Páry slov sú generované **BFS (Breadth-First Search) algoritmom**, ktorý prechádza grafom slov a hľadá najkratšiu cestu medzi dvoma slovami. Vyberajú sa iba páry so vzdialenosťou **3–6 krokov** pre optimálnu obtiažnosť.

```python
# Príklad BFS hľadania cesty
start = "basa"
end   = "kola"
path  = ["basa", "jasa", "java", "kava", "kala", "kola"]  # 5 krokov
```

---

## 🗂️ Štruktúra

```
index.html   ← celá hra (HTML + CSS + JS v jednom súbore)
render.yaml  ← konfigurácia pre Render.com
```

Hra je **single-file** aplikácia – žiadny build, žiadne závislosti, funguje priamo v prehliadači.

---

## 🚀 Spustenie lokálne

Stačí otvoriť `index.html` v prehliadači. Alebo:

```bash
git clone https://github.com/Slavissimo/Weaver-Wordle.git
cd Weaver-Wordle
# Otvor index.html v prehliadači
```

---

## 🌐 Nasadenie

Hra je nasadená ako **Static Site** na [Render.com](https://render.com) a dostupná na adrese [saloncuk.sk/tkac](https://saloncuk.sk/tkac) cez Cloudflare Worker routing.

---

<div align="center">

*Súčasť [saloncuk.sk](https://saloncuk.sk) – herného portálu Slava*

<img src="https://capsule-render.vercel.app/api?type=waving&color=e8c547&height=100&section=footer" />

</div>
