# Rock Paper Scissors – Joc Web (Piatră, Hârtie, Foarfecă)

Acest proiect reprezintă o implementare simplă și interactivă a jocului clasic Piatră, Hârtie, Foarfecă (Rock Paper Scissors) sub forma unei aplicații web. Jucătorul concurează împotriva calculatorului, iar scorul este afișat în timp real.

---

## Scopul Proiectului

Scopul principal al acestui proiect este de a demonstra conceptele fundamentale de dezvoltare web front-end, utilizând HTML pentru structură, CSS pentru stilizare și JavaScript pentru logica jocului și interactivitate.

---

## Descriere Generală și Funcționalități

Jocul oferă următoarele funcționalități cheie:
- Interfață Utilizator Intuitivă: O interfață curată și simplă, care afișează scorurile jucătorului și ale calculatorului, precum și alegerile fiecăruia.
- Alegerea Jucătorului: Jucătorul poate alege Piatră, Hârtie sau Foarfecă dând click pe imaginile corespunzătoare.
- Alegerea Calculatorului: Calculatorul face o alegere aleatorie (Piatră, Hârtie sau Foarfecă) pentru fiecare rundă.
- Logica Jocului: Determinarea automată a câștigătorului fiecărei runde conform regulilor clasice (Piatra bate Foarfeca, Foarfeca bate Hârtia, Hârtia bate Piatra).
- Scor în Timp Real: Scorul jucătorului și al calculatorului este actualizat și afișat după fiecare rundă.
- Condiție de Câștig/Final: Jocul se încheie atunci când un jucător (sau calculatorul) atinge un scor predefinit (implicit 3 puncte), afișând un mesaj de final.

---

## Componente Tehnologice Utilizate

Acest proiect este o aplicație web pur front-end, bazată pe tehnologiile web standard:
- HTML (index.html): Asigură structura paginii web, incluzând elementele pentru afișarea scorurilor, imaginile pentru alegeri și butoanele/imaginile pentru selecția jucătorului.
- CSS (style.css): Definește stilul vizual al jocului, cum ar fi fonturile, alinierea textului, dimensiunile și poziționarea imaginilor și a altor elemente.
- JavaScript (script.js): Conține logica principală a jocului:

Gestionarea evenimentelor de click pentru alegerile jucătorului.

Generarea alegerii aleatorii a calculatorului.

Implementarea regulilor jocului pentru a determina câștigătorul fiecărei runde.

Actualizarea scorurilor și afișarea mesajelor de final.

- Imagini (rock.png, paper.png, scissors.png): Resurse grafice utilizate pentru a reprezenta alegerile Piatră, Hârtie și Foarfecă.

---

## Structura Fișierelor

Proiectul are o structură de fișiere simplă și directă:

rock-paper-scissors/
├── index.html        # Structura principală a paginii web
├── style.css         # Fișierul de stiluri CSS
├── script.js         # Logica jocului în JavaScript
├── rock.png          # Imagine pentru alegerea "Piatră"
├── paper.png         # Imagine pentru alegerea "Hârtie"
└── scissors.png      # Imagine pentru alegerea "Foarfecă"

---

## Rulare și Utilizare

Acesta este un proiect web front-end, care rulează direct în browser. Nu necesită un server web sau instalări suplimentare.
1. Descărcați fișierele: Clonați repository-ul sau descărcați toate fișierele proiectului într-un director local.
2. Deschideți index.html: Pur și simplu deschideți fișierul index.html în browser-ul dumneavoastră web preferat (ex: Chrome, Firefox, Edge). Puteți face acest lucru prin dublu-click pe fișier.
3. Jucați: Interfața jocului se va încărca. Alegeți Piatră, Hârtie sau Foarfecă dând click pe imaginile corespunzătoare pentru a începe jocul. Scorul va fi actualizat după fiecare rundă. Jocul se termină când unul dintre jucători atinge scorul de 3.

---

## Realizat de

Proiect realizat de [bogdanch7](https://github.com/bogdanch7)

An universitar 2024–2025

---

## Licență

Acest proiect este creat pentru uz educațional.
