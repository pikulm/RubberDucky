# RubberDucky
Making Rubber Ducky with FRDM-KL46Z

Opis projektu:
Rubber Ducky to nazwa określająca pendrive, który udaje klawiaturę podłączaną przez USB. Zawiera prekodowaną sekwencję klawiszy, która wysyłana jest do komputera.
Celem projektu jest utworzenie oprogramowania, które wgrane na płytkę FRMD-KL46Z będzie zachowywało się właśnie w opisany wyżej sposób.

Analiza problemu:
Płytka FRMD-KL46Z domyślnie rozpoznawana jest jako urządzenie, na które możemy wgrać jakiś program. Tym razem chcemy jednak, żeby urządzenie po podłączeniu przez USB widziane było jako klawiatura i przesłało na komputer program, który sami mu uprzednio wgraliśmy.

Plan realizacji:
Priorytetem w realizacji tego projektu jest zaprogramowanie płytki FRMD-KL46Z, żeby w managerze urządzeń na komputerze pojawiała się jako klawiatura. Realizacja nastąpi poprzez komunikację USB.
Kolejno, możemy zaprogramować płytkę tak, by jej podłączenie do komputera skutkowało zrobieniem printscreena całego ekranu. Zdecydowanie ciekawszą funkcją byłoby otworzenie terminala oraz wykorzystanie potencjału działań, które można w nim wykonać (np. skopiować dokumenty na serwer AGH).


