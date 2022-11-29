# poker-sk2-project
Project carried out by Kamil Stachowiak and Marcin Stacewicz for the subject SK2.

--------------------------- Sieciowa gra w pokera -----------------------

Gracz łączy się z siecią i wysyła swój nick (jezeli jest on juz zajety, proszony jest on o podanie nowego nicku).

Gracz jest w stanie dołączyć lub stworzyć nową grę. Gracz moze takze opuscic gre przedwcześnie (w tym wypadku jednak, pozostały mu depozyt pieniężny przepada).

Gracz tworzący rozgrywkę, może ją rozpocząć tylko jeśli do gry dołączył co najmniej jeden gracz. Do gry nie może dołączyć więcej niż 4 graczy.

Każda rozgrywka może, ale nie musi być "zahasłowana" - dostęp do niej może mież dowolna osoba lub tylko osoba znająca hasło.

Każdy, uczestnik gry rozpoczyna z takim samym depozytem pieniężnym ustalanym początkowo przez tworzacego rozgrywkę. Gra kończy się w momencie, w którym wszyscy gracze się wycofają (oprócz jednego) lub jeden gracz będzie posiadał depozyty innych graczy.

Gra ta będzie reprezentacją pięciokartowego pokera dobieranego, w którym:
- gracze otrzymują po pięć kart z pełnej talii bez jokerów (52 karty), talii składającej się z 32 kart (od 7) lub z 24 kart (od 9).
- Następnie pozbywają się niepotrzebnych kart (maksymalnie 4) ze swoich pięciu, można także pozostawić wszystkie karty w ręce.
- Później dobiera z talii tyle kart, aby gracz miał ich pięć.

Dane rozdanie kończy się w przypadku okazania kart gracza posiadających najsilniejszy układ kart według starszeństwa układów pokerowych. Jeśli w grze pozostanie tylko jeden gracz, podczas gdy inni gracze spasują, wygrywa on pulę niezależnie od posiadanych kart. Jeżeli gracze mają takie same karty, dzielą wygraną na połowę.

