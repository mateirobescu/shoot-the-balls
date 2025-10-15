# Shoot The Balls

**Shoot The Balls** este un joc arcade simplu, dezvoltat cu Python și framework-ul Kivy, în care scopul tău este să lovești "bilele" care cad de sus înainte ca acestea să atingă partea de jos a ecranului. Fii rapid, colectează monede și deblochează noi skin-uri!

## Caracteristici principale

* **Gameplay Arcade Clasic:** Lovitura distruge bilele inamice care cad de sus, dar pierzi o viață dacă o bilă atinge fundul ecranului.
* **Sistem de Scorul și Nivele:** Scorul crește pe măsură ce lovești bilele, iar atingerea anumitor praguri de scor (multipli de 1000) crește nivelul și dificultatea jocului.
* **Monede și Magazin (Shop):** Colectează monede (sunt bile speciale!) și folosește-le în magazin pentru a cumpăra skin-uri noi (de exemplu, `yellowBila.png` sau `greenBila.png`).
* **Statistici Persistente:** Urmărește cel mai mare scor (`Highscore`) și istoricul tuturor jocurilor jucate, inclusiv data și ora, folosind o bază de date SQLite.
* **Stil Pixel Art:** Jocul folosește o estetică simplă, cu grafică pixelată și un font personalizat.

## Tehnologii Utilizate

* **Limbaj:** Python 3
* **Framework GUI:** Kivy
* **Bază de date:** SQLite3 (pentru salvarea scorurilor și a istoricului jocurilor)
* **Pachete Suplimentare:** `pytz` și `datetime` (pentru gestionarea datelor și a fusului orar în statistici)
* **Compilare Mobilă:** Buildozer (pentru generarea pachetelor APK/AAB pentru Android).
