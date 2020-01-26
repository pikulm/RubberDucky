# RubberDucky
Making Rubber Ducky with FRDM-KL46Z

Projekt wykonany na MacBook Air - klawisze naciskane w trakcie wykonywania programu charakterystyczne są więc dla jego klawiatury.

Film:
https://drive.google.com/open?id=1zldisnPohNWWIJCXWL2o37GD6JwjpafQ

Opis projektu:
Rubber Ducky to nazwa określająca pendrive, który udaje klawiaturę podłączaną przez USB. Zawiera prekodowaną sekwencję klawiszy, która wysyłana jest do komputera.
Celem projektu jest utworzenie oprogramowania, które wgrane na płytkę FRMD-KL46Z będzie zachowywało się właśnie w opisany wyżej sposób.

Analiza problemu:
Płytka FRMD-KL46Z domyślnie rozpoznawana jest jako urządzenie, na które możemy wgrać jakiś program. Tym razem chcemy jednak, żeby urządzenie po podłączeniu przez USB widziane było jako klawiatura i przesłało na komputer program, który sami mu uprzednio wgraliśmy.

Plan realizacji:
Priorytetem w realizacji tego projektu jest zaprogramowanie płytki FRMD-KL46Z, żeby w managerze urządzeń na komputerze pojawiała się jako klawiatura. Realizacja następuje poprzez komunikację USB.
Kolejno wykorzystywany jest Capacitive Touch Slider, którego dotknięcie inicjuje wysłanie kombinacji odpowiednich klawiszy.
Kliknięcie lewej strony slidera powoduje wykonanie screenshot'a, a prawej strony - przechwycenie zawartości pliku id_rsa i przesłanie go na mojego maila.


