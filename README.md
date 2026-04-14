NAZIV PROJEKTA: Fitness Track App

1. Opis aplikacije:
   Ovo je Flutter aplikacija namijenjena praćenju fitness aktivnosti.
   Omogućuje korisnicima da kreiraju vlastite treninge (Workouts) koji se sastoje od niza vježbi (Exercises).
   Glavna karakteristika aplikacije je lokalna pohrana podataka, što osigurava privatnost i brzinu, te vizualni prikaz napretka putem kalendarske mape (Heat Map) koja bilježi dane kada je korisnik bio aktivan.

2.Glavne funkcionalnosti:

1.Kreiranje treninga: Organizacija vježbi u grupe (npr. Upper Body, Lower Body).
2.Detaljno praćenje vježbi: Unos naziva, težine, broja ponavljanja i setova.
3.Status dovršenosti: Označavanje vježbi kao završenih.
4.Lokalna baza podataka: Korištenje Hive baze za trajno čuvanje podataka na uređaju.
5.Heat Map: Vizualni prikaz aktivnosti kroz mjesece.

3.Upute za pokretanje (Setup Guide):
1.Provjerite imate li instaliran Flutter SDK na svom računalu. Pokrenite flutter doctor u terminalu za provjeru statusa.
2.Preuzimanje projekta: Preuzmite ovaj repozitorij kao .zip datoteku i raspakujte ga.
3.Dohvaćanje paketa: Otvoriti terminal u mapi projekta i pokrenuti: flutter pub get
4.Pokretanje aplikacije: Povezivanje simulatora ili fizičkog uređaja i pokretanje: flutter run

4. Spisak korištenih paketa (Dependencies): hive- Lagana i brza NoSQL baza podataka za Dart/Flutter.
hive_flutter- Proširenje za Hive koje olakšava korištenje s Flutterom.

flutter_heatmap_calendar- Paket za prikaz kalendara aktivnosti.

provider- Za upravljanje stanjima (state management).
