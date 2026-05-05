## 📚 Popis projektu

Projekt implementuje **3D Model Customizer**, ktorý umožňuje používateľovi nielen zobraziť 3D model, ale aj aktívne meniť jeho vizuálne vlastnosti.

Na rozdiel od klasického 3D vieweru aplikácia poskytuje interaktívne nástroje na úpravu materiálov a vzhľadu modelu.

---

## 🎮 Funkcionalita aplikácie

### 📦 Načítanie modelu (INPUT)

Používateľ môže nahrať vlastný 3D model vo formáte:
- `.glb`
- `.gltf`

---

### 🎨 Úprava vzhľadu modelu (Customizer)

Používateľ môže meniť:
- farbu materiálu modelu  
- emissive (svietiacu) farbu  
- vizuálny štýl (napr. matte / metal)  
- aplikovať farebné presety  

---

### 💡 Interaktívne ovládanie
- rotácia modelu myšou  
- zoom pomocou scrollu  
- posúvanie kamery  

---

### 📊 Automatické nastavenie scény
- kamera sa automaticky prispôsobí veľkosti modelu  
- model je centrovaný v scéne  

---

## ⚙️ Použité technológie

- **Three.js** – 3D rendering v prehliadači  
- **WebGL** – grafické vykresľovanie  
- **JavaScript / HTML / CSS** – frontend  

---

## ⚠️ Backend

Projekt je implementovaný ako čisto frontendová aplikácia:

- nevyužíva žiadny server  
- všetky výpočty prebiehajú v prehliadači  

---

## 📥 Vstup a Výstup (In/Out)

### INPUT:
- 3D model (.glb / .gltf)

### OUTPUT:
- interaktívna vizualizácia modelu  
- upravený vzhľad modelu v reálnom čase  
