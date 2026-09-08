TCP/IP Tower - prosty prototyp gry 3D

URUCHOMIENIE
1. Otwórz plik index.html w przeglądarce.
2. Jeśli przeglądarka blokuje część funkcji, uruchom prosty serwer HTTP w tym katalogu:
   python -m http.server 8000
3. Wejdź na:
   http://localhost:8000

STEROWANIE
- WASD: ruch
- mysz: rozglądanie
- E: interakcja ze stanowiskiem
- 1-4: teleport między warstwami TCP/IP
- ESC: uwolnienie kursora / zamknięcie panelu

UWAGA
Gra korzysta z Three.js pobieranego z CDN, więc do pierwszego uruchomienia potrzebny jest internet.
