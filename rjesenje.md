# 1. Likovi
  Koristimo i postavljamo 2 lika:
  - igrač (majmun)
  - banane
# 2. varijable
  Napravimo 2 varijable koje trebaju biti dostupne svim likovima:
  - vrijeme
  - bodovi
# 3. Igrač - početak igre
  Na liku igrač slažemo blok koda:
  - Kada je kliknuta zelena zastavica
  - idi na x: 0 y: 0
  - postavi bodovi na 0
  - postavi vrijeme na 30
# 4. Igrač - kretanje pomoću tipki sa strelicama
  Na liku igrač slažemo novi blok koda za kretanje:
  - Gore: kada je tipka strelica gore pritisnuta -> promijeni y za 10
  - Dolje: kada je tipka strelica dolje pritisnuta -> promijeni y za -10
  - Lijevo: kada je tipka strelica lijevo pritisnuta -> promijeni x za -10
  - Desno: kada je tipka strelica desno pritisnuta -> promijeni x za 10
# 5. Banane - početni položaj
  Na liku banane slažemo blok koda:
  - Kada je kliknuta zelena zastavica
  - idi do nasumična pozicija
# 6. Banane - skupljanje
  Na liku banane dodajemo novi blok koda:
  - Kada je kliknuta zelena zastavica
  - ponavljaj 
    - ako dodiruje Majmun ? onda
      - promijeni bodovi za 1
      - idi do nasumična pozicija
# 7. Odbrojavanje vremena
  Na liku igrača dodajemo novi blok koda:
  - kada je kliknuta zelena zastavica
  - ponovi 30
    - čekaj (1) sekundi
    - promijeni vrijeme za (-1)
# 8. Slanje poruke Kraj igre
  Na liku igrača u bloku koda gdje smo postavili odbrojavanje vremena, dodamo na kraju
  - pošalji Kraj igre i čekaj
# 9. Završna poruka
  Na liku igrača dodajemo novi blok koda:
  - kada primim Kraj igre
  - govori
    - spoji Kraj igre! Osvojio/la si
        - spoji bodovi bodova.
    - 5 sekundi
  - zaustavi sve 
  
