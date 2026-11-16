# e-knjigovodstvo — mobilna aplikacija

[**Preuzmi Android 0.3.0 — jedan APK**](https://github.com/misetic99/e-knjigovodstvo-mobile/releases/download/android-v0.3.0/e-knjigovodstvo-0.3.0-android.apk)

Preuzmite datoteku na telefon, otvorite je i odaberite **Instaliraj** ili **Ažuriraj**. Naziv ispod ikone je **e-knjigovodstvo**. Instalirajte preko prethodne aplikacije (0.1.1–0.2.1), uz očuvanje podataka. Za rad se prijavljujete svojim postojećim računom na eknjigovodstvo.org.

## Novo mobilno iskustvo

- Vlastiti mobilni zasloni: Danas, Dokumenti, Novo, Obveze i Više, uz tamnu temu i prilagođene obrasce.
- Skener više stranica, fotografija, PDF/slike iz Androidova izbornika **Dijeli** i trajni red slanja. Napredni skener koristi Google Play usluge; prvo pokretanje može preuzeti njegov modul.
- Potvrđeni dokumenti nastavljaju slanje nakon povratka veze. Prethodno sačuvani dokumenti iste tvrtke i osobe ostaju dostupni za nastavak.
- Biometrijsko zaključavanje uz PIN uređaja i pregled prijavljenih uređaja.
- Pregled računa, račun/ponuda iz spremljene usluge, evidencija naplate, postojeća odobrenja i poruke uz dokument.
- Kilometri uz dokaz, pregled artikala i pretraga šifre barkodom/QR-om.
- Obavijesti uz pristanak korisnika: periodična provjera na uređaju. Mogu kasniti; nisu trenutačne push obavijesti.

Android 7 ili noviji. Jedan potpisani paket `org.eknjigovodstvo.mobile`, bez QA oznake i dodatnih procesorskih paketa. Nadogradnje imaju isti trajni potpis. Poslovni podaci i prava ostaju na postojećem sustavu; neposlane kopije čuvaju se privatno na uređaju.

**Ne deinstalirajte aplikaciju i ne brišite njezine podatke radi nadogradnje:** time biste uklonili privatne neposlane kopije. Ako Android traži dopuštenje instalacije iz preglednika ili mape Preuzimanja, dopustite instalaciju za taj izvor.

## Stanje razvoja

Ovo je Android predizdanje za izravnu instalaciju. Stavke MOBAPP-01–05 djelomično su implementirane. iOS, Google Play/App Store objava, puna kriptografska prijava uređaja, FCM/APNs push, bankovne aplikacije, inventura/primke skeniranjem i servisni nalozi s potpisom ostaju u razvoju. Barkod ovdje pretražuje šifru artikla i ne mijenja skladište.

Provjereno na Androidu 17 (API 37) emulatoru: prijava/restart, račun/naplata, kamera, dijeljenje, red kroz prekid veze i nadogradnju, pozadinsko slanje, poruke, prethodni red, ispis, tamna tema i zaključavanje s PIN-om. Fizički Samsung S25 Ultra, senzor biometrije i napredni Google skener zahtijevaju prihvat na uređaju.

[Napomene uz 0.3.0](https://github.com/misetic99/e-knjigovodstvo-mobile/releases/tag/android-v0.3.0) · [Sva mobilna izdanja](https://github.com/misetic99/e-knjigovodstvo-mobile/releases)

Ovaj javni repozitorij sadrži APK, kontrolni zbroj i napomene. Izvorni kod održava se zasebno. [Windows instalateri](https://github.com/misetic99/e-knjigovodstvo-windows) objavljuju se u zasebnom repozitoriju.


## Administracija i nadogradnje u 0.3.0

Zaglavlje prikazuje samo **e-knjigovodstvo**, a znak unutar Android ikone ima veći rub za zaobljene maske. **Više → Administracija** otvara svih sedam postojećih web/desktop administratorskih rubrika, s istim ovlastima i poslovnim komponentama, upakiranima u APK. Samo platformskom administratoru pripada taj pristup.

**Više → Ažuriranja aplikacije** provjerava javna izdanja i nudi novi APK. Na starijoj verziji najprije ručno preuzmite gornji APK. Otvorite ga i potvrdite Ažuriraj/Instaliraj preko postojeće aplikacije; nemojte je deinstalirati. Android i dalje traži vašu potvrdu instalacije.
