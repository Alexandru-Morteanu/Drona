# 🛸 Proiect Modelare 3D - Dronă FPV Minimalistă (High-Quality Video)

Acest depozit conține toate fișierele sursă și documentația tehnică pentru proiectul de modelare 3D al unei drone minimalistice personalizate, optimizată pentru filmări de înaltă calitate și performanță stabilă. Proiectul a fost realizat integral în **Autodesk Fusion 360**.

---

## 📺 Demonstrație Video
Funcționalitatea completă a ansamblului tridimensional, mișcările componentelor și randarea pot fi vizualizate în clipul de mai jos:

👉 [**Urmărește demonstrația pe YouTube**](https://youtu.be/zicYjp4gcpw?si=uIy2IhgHI5totVo0)

---

## 📐 Concept și Inspirație
Designul structural și geometria cadrului principal s-au inspirat de la modelul de drone cinematice [Minifilmer25](https://grabcad.com/library/minifilmer25-1) de pe GrabCAD Community. 

### 🔄 Diferențe cheie și îmbunătățiri aduse de mine:
Spre deosebire de modelul original care folosește o placă electronică combinată de tip All-in-One (AIO), **proiectul meu folosește o configurație de tip "Split Stack" formată din două plăci dedicate separate**, oferind o mentenanță mai ușoară și o disipare termică superioară:
1. **ESC separat:** DYS F30A 4-in-1 ESC.
2. **Flight Controller separat:** Hobbywing Xrotor F4.

---

## 🛠️ Lista Componentelor și Rolul Acestora

Mai jos este detaliată lista completă a componentelor folosite în ansamblul 3D (atât structura CAD, cât și piesele electronice preluate și adaptate din comunitatea GrabCAD):

### 1. Electronică și Propulsie
* **Flight Controller (FC) - Hobbywing Xrotor F4:** Creierul dronei. Procesează datele de la senzori (giroscop) și trimite comenzi corective către motoare pentru a menține stabilitatea.
* **Electronic Speed Controller (ESC) - DYS F30A 4-in-1:** Controlerul de viteză al motoarelor. Primește semnalul de la FC și distribuie puterea necesară (până la 30A per motor) direct de la baterie.
* **Motoare - Brushless 2207:** Motoare de înaltă performanță, ideale pentru cadre de dimensiuni mici-medii, oferind raportul optim de putere/greutate necesar zborului acrobatic sau cinematic.
* **Sistem O3 AIO / Cameră FPV:** Unitatea digitală responsabilă pentru transmiterea fluxului video în timp real către ochelarii FPV și pentru înregistrarea cadrelor la rezoluție înaltă.
* **Modul GPS - M10 (GPS-M10:1):** Asigură poziționarea globală, telemetria vitezei și funcția de siguranță "Return to Home" în caz de pierdere a semnalului.

### 2. Structură și Hardware (Elemente de fixare)
* **Șasiu Jos (Sasiu jos:1 / Frame 1:1):** Placa de bază din fibră de carbon care preia toate forțele mecanice și pe care se montează stack-ul electronic și brațele motoarelor.
* **Distanțiere (Standoffs):** Sunt necesare **5 distantiere metalice/nailon** pentru a crea spațiul vertical de siguranță între plăcile de carbon și pentru a proteja stack-ul electronic.
* **Suruburi de fixare:** O serie de șuruburi metrice (M2/M3) utilizate pentru strângerea motoarelor pe brațe, prinderea distanțierelor și securizarea componentelor electronice.
* **Elici (Propellers):** Elementele aerodinamice montate pe axul motoarelor responsabile pentru generarea forței de portanță.

---

## 🖼️ Galerie Foto (Workspace Fusion 360)

### Configurația Stack-ului Electronic (Rigid Group)
Plăcile electronice au fost grupate rigid pentru a simula corect prinderea lor fizică pe șuruburi.

![Stack Electronic Fusion 360](cale_catre_imaginea_ta_1.png)

### Alinierea Componentelor pe Cadrul de Carbon
Vizualizare de sus a plasării motorizării și a modulelor de navigație.

![Ansamblu Joint Dronă](cale_catre_imaginea_ta_2.png)

---

## 📚 Resurse Utilizate

* **Software Modelare:** Autodesk Fusion 360 (Licență Studențească).
* **Componente Electronice:** Preluat de pe [GrabCAD Community](https://grabcad.com/).
* **Modelul de Referință pentru Cadru:** [Minifilmer25-1 pe GrabCAD](https://grabcad.com/library/minifilmer25-1).

---

## 📂 Structura Fișierelor din Repository
* `/Fisiere_Sursa_F3D/` -> Conține fișierele native exportate din Fusion 360 (`.f3d`, `.step`).
* `/Componente_Individuale/` -> Modelele 3D separate pentru motoare, elici și plăci electronice.
* `/Screenshots/` -> Imaginile utilizate în acest document.

---
*Proiect realizat în cadrul laboratorului de Modelare 3D.*
