# Moj krvni tlak

Slovenska Android aplikacija za beleženje krvnega tlaka.

## Vključeno v različici 0.1
- vnos sistoličnega in diastoličnega tlaka, utripa, opombe in zdravil;
- lokalna Room baza brez registracije;
- dnevnik meritev in brisanje;
- povprečja in osnovna razvrstitev;
- graf zadnjih 30 meritev;
- PDF in CSV izvoz prek Androidovega menija za deljenje;
- slovenski uporabniški vmesnik;
- brez oglasov in brez pošiljanja zdravstvenih podatkov tretjim osebam.

## Zagon
1. Razširite ZIP.
2. Odprite mapo `moj-krvni-tlak` v Android Studio.
3. Počakajte na Gradle Sync.
4. Zaženite na telefonu ali emulatorju z Android 8.0+.

## Naslednji moduli
Opomniki, glasovni vnos, urejanje obstoječih meritev, več uporabnikov, šifrirana varnostna kopija, biometrija in izbirna sinhronizacija v oblaku.

## Samodejna izdelava APK v GitHubu

Projekt vsebuje GitHub Actions postopek `.github/workflows/build-apk.yml`. Ob ročnem zagonu ali spremembi veje `main`/`master` izdela datoteko `MojKrvniTlak.apk` in jo shrani med Artifacts.
