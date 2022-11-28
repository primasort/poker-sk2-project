# poker-sk2-project
Project carried out by Kamil Stachowiak and Marcin Stacewicz for the subject SK2.

--------------------------- Sieciowa gra w pokera -----------------------

Gracz łączy się z siecią i wysyła swój nick (jezeli jest on juz zajety, proszony jest on o podanie nowego nicku).

Gracz jest w stanie dołączyć, lub stworzyć nową grę. Gracz moze takze opuscic gre przedwczesnie (w tym wypadku jednak, caly jego depozyt pienięzny ktory mu pozostal przepada).

Gracz tworzący rozgrywkę, moze ja rozpoczac pod warunkiem ze do gry dolaczyl conajmniej jeden gracz. Do gry nie moze dolaczyc wiecej niz 4 graczy.

Kazda rozgrywka moze byc "zachaslowana" - dostep moze miec do niej dowolna osoba, lub tylko osoba znajaca haslo

Kazdy, uczestnik gry rozpoczyna z takim samym depozytem pienięznym ustalanym poczatkowo przez tworzacego rozgrywkę. Gra konczy sie w momencie w ktorym wszyscy gracze sie wycofają (oprócz jednego), lub jeden gracz bedzie posiadal depozyty innych graczy. 

Gra ta będzie reprezentacją pięciokartowego pokera dobieranego w którym: 
    - gracze otrzymują po pięć kart z pełnej talii bez jokerów (52 karty), talii składającej się z 32 kart (od 7) lub z 24 kart (od 9).
    - Następnie pozbywają się niepotrzebnych kart (maksymalnie 4) ze swoich pięciu, można także pozostawić wszystkie karty w ręce.
    - Później dobiera z talii tyle kart, aby miał ich pięć.

    - Dane rozdanie kończy się w przypadku okazania kart gracza posiadających najsilniejszy układ kart według starszeństwa układów. Jeśli w grze pozostanie     tylko jeden gracz podczas gdy inni gracze spasują, wygrywa on pulę niezależnie od posiadanych kart. Jezeli gracze maja takie same karty, dziela wygrana     na polowe.
