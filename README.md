# QAProjectFERIT

Projekt je izradjen u JMeter programu; testirana je webshop stranica https://petstore.octoperf.com/

Izradjeni su izvještaji za 5, 100 te 200 korisnika istovremeno. Testirani su glavni scenariji poput slanja API requestova, prijave, naručivanja iz trgovine. Zaključak je kako je prosječan response time stranice priblizno 3 sekunde, što predstavlja prihvatljivo vrijeme odziva. Pri testovima s 5 i 100 korisnika relativno je malo palih testova (ispod 3%), dok pri 200 korisnika pada 12% testova, što je znatno više. Throughput(propusnost stranice) pod testom je 72177/minute, što znači da stranica moze procesirati 72 tisuće zahtjeva u minuti (vidljivo u prilogu na repozitoriju) dok je vrijednost devijacije 18931 (isto vidljivo u prilogu), što je poprilicno veliko odstupanje. Sve u svemu, moze se zakljuciti da testirana stranica nema najbolje performanse pri vise od 100 korisnika.
