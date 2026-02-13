[README.md](https://github.com/user-attachments/files/25289316/README.md)
# Vizītkarte Mājaslapa | One-Page Website

## 📋 Projekta Apraksts

Šis ir personīgās vizītkartes mājaslapa, kas izveidota kā viena HTML lappuse ar responsīvu dizainu. Mājaslapa atbilst visiem norādītajiem kritērijiem un ir gatava iesniegšanai.

---

## 📁 Failu Struktūra

```
PDAJtīmekļalappuse/
├── index.html           # Galvenais HTML fails
├── style.css            # Paša izstrādātie stili
├── dog1.jpg             # Galerijas attēls 1
├── dog2.jpg             # Galerijas attēls 2
├── dog3.webp            # Galerijas attēls 3
├── favicon.ico          # Mājas lapas ikona
└── README.md            # Šis fails
```

---

## 🎯 Sekcijas

### 1. **Header (Galvene)**
- Mājas lapas nosaukums un navigācijas izvēlne
- Navigācijas pogas ar якорными saitēm (#id)
- Vienkāršs, tīrs dizains ar melniem tekstiem
- Responsīvs - pielāgojās dažādiem ekrānu izmēriem

### 2. **Par Mani (About Section)**
- Teksta sadaļa ar aprakstu
- Pelēka fona krāsa (#e9ecef) - atšķirat no pārējām sadaļām
- Centrēts saturs ar ērtām atstarpēm
- Maksimāla platuma ограничение - saturs nesniedzas līdz ekrāna malām

### 3. **Prasmes un Intereses (Skills Section)**
- **4 kolonas** ar dažādām prāsmēm
- Katra kolonna satur: ikonu, virsrakstu, aprakstu
- Bootstrap Flexbox izkārtojums - uz mobilajiem ekrāniem kolonas kļūst par vienu rindu
- Hover efekts - kolonas "pacel" uz augšu (translateY)

### 4. **Galerija (Gallery Section)**
- Trīs attēli no `/images` mapes
- Gluda attēlu pārejas animācija (0.3s transition)
- Hover efekts - attēli pieaug par 5% (scale 1.05)
- Pelēka fona krāsa

### 5. **Kājene/Footer**
- Autortiesību zīme (©) ar gadu
- Sociālo tīklu ikonas (Facebook, Twitter, Instagram)
- Ikonas ir saitnes uz sociālo tīklu lapām
- Tumša fona krāsa (#343a40) - labi kontrastē ar baltiem tekstiem

---

## 🛠️ Tehnoloģijas un Bibliotēkas

### HTML5
- Semantiska HTML5 struktūra
- Meta tagi responsīvumam
- Korektā kodējuma deklarācija (UTF-8)

### CSS3
- **Paša izstrādātie stili** (style.css)
- **Bootstrap 5.3.8** - Responsive Grid sistēma
- **Bootstrap Icons** - Ikonu bibliotēka
- **Google Fonts** - Roboto fonts (wght: 400, 500, 700)

### Dinamiskie Elementi
- Hover efekti (nav-link, skill cards, galerijas attēli)
- Krāsu pārejas (color transitions)
- Transformācijas (transform: scale, translateY)

---

## 📱 Responsīvums

Mājaslapa ir pilnīgi pielāgojama visiem ekrānu izmēriem:

- **Desktop** (lg ≥ 992px): Visas 4 prasmes kolonas blakus
- **Tablet** (md ≥ 768px): Pielāgots izkārtojums
- **Mobile** (xs < 576px): Viena kolonna, viena attēla platumā

Bootstrap grid sistēma nodrošina automātisku pielāgošanu!

---

## 🎨 Krāšu Paleta

| Nosaukums | Krāsa | Lietojums |
|-----------|-------|----------|
| Balta | #ffffff | Header fons |
| Pelēka | #e9ecef | Skill cards, About bg |
| Tumšā pelēka | #f8f9fa | Body background |
| Melna | #212529 | Teksts |
| Zila | #007bff | Accent krāsa (hover) |
| Tumšā | #343a40 | Footer background |

---

## 🚀 Ieslēgšana

1. Atvērt `index.html` failā ar pārlūkprogrammu
2. Navigācijas pogas darbojās - noklikšķinot tās, lapa skrola uz attiecīgo sadaļu
3. Pārbaudīt responsīvumu - izstiepiet pārlūka logu vai atvērt mobilā skatā

---

## ✅ Kritēriju Pārbaude

### Sintakse
- ✅ HTML5 struktūra ir korekta
- ✅ CSS pieraksts ir pareizs
- ✅ Ārējie elementi korekti pievienoti (Bootstrap, Google Fonts)
- ✅ Kods ir vizuāli pārskatāms ar komentāriem

### Noformējums
- ✅ Noformējums izmanto CSS
- ✅ Kombinēts savs + ārējais CSS
- ✅ Dinamiskie elementi (hover efekti, transitions)

### Dizains
- ✅ Mājaslapa ir vizuāli pievilcīga
- ✅ Saskaņotas krāsas, fonti, izkārtojums
- ✅ Saturs nesniedzas līdz ekrāna malām (container padding)

### Sadaļas
- ✅ 5 sadaļas (Header, About, Skills, Gallery, Footer)
- ✅ Katra sadaļa ir atšķirīga
- ✅ Katra sadaļa ir vizuāli atdalīta

### Navigācija
- ✅ Navigācijas pogas ar якорными saitēm
- ✅ Pogas ved uz attiecīgajām sadaļām

### Prasmes
- ✅ 4 kolonas uz desktop
- ✅ Automātiski pieaugam uz mobile (1 kolonna)

### Footer
- ✅ Autortiesību zīme
- ✅ Sociālo tīklu ikonas
- ✅ Ikonas ir saitnes

### Attēli
- ✅ 2+ attēli pievienoti
- ✅ Visi attēli vienā mapē
- ✅ Korekti ievietoti HTML
