# UpravljanjeDejavnosti

Projekt pri predmetu NSA.

Člani skupine:
- Jan Tomšič Pivk
- Matic Vrtačnik
- Klemen Jesenovec






Naloga:


Je preprost informacijski sistem, ki uporabnikom primarno omogoča vpogled v dejavnosti, ki se v izobraževalni ustanovi odvijajo med šolskim letom; krožki, OIV, tekmovanja, … . Sicer mora sistem omogočati definicijo dejavnosti  s podanimi atributi, iskanje dejavnosti po danih parametrih, zaželena je prijava(vpis) k dejavnosti.

Grob opis zahtev je podan v posebnih dokumentih:
-	Iskalnik dejavnosti pojasnjuje kriterije želenih iskanj
-	Obrazec za mentorje pojasnjuje strukturo baze (tabel in zahtevanih atributov)
-	Pregled dejavnosti  je excelova tabela, ki dejansko predstavlja trenutni  'informacijski sistem'

Zaželena je možnost izvoza posamezne dejavnosti (v enega izmed 'standardnih' oblik) in uvoz dejavnosti, hkrati tudi izpis spiska dejavnosti z nosilci, ter izpis posamezne dejavnosti (obrazec za mentorje)

Omenjene datoteke opisov so podane v mapi DEJ_TemeProjektnihNalog201415

Vloge uporabnikov:

-	Uporabnik
-	Učitelj
-	Mentor
-	Administrator

Uporabnik: pregleduje, eventualno se registrira/vpiše k dejavnosti, lahko napreduje v učitelja
Učitelj == Uporabnik,  s tem, da lahko napreduje v vlogo mentorja
Mentor: pregleduje, lahko definira dejavnost, lahko povzdigne uporabnika v učitelja
Administrator: vse + definira uporabnike, spremeni poljubno vlogo, določa mentorje

