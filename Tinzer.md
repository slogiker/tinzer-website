## Tinzer – Seznam funkcionalnosti

## Seznam funkcionalnosti

| ID | Ime funkcionalnosti | Opis | Prioriteta |
|---|---|---|---|
| F01 | Registracija uporabnika | Uporabnik lahko ustvari nov račun z vnosom zahtevanih podatkov. Sistem preveri pravilnost podatkov in shrani uporabniški račun. | Visoka |
| F02 | Prijava uporabnika | Uporabnik se lahko prijavi v svoj račun z uporabniškim imenom in geslom. Sistem preveri podatke in omogoči dostop do računa. | Visoka |
| F03 | Odjava uporabnika | Uporabnik se lahko odjavi iz svojega računa. S tem se zaključi njegova prijavljena seja. | Srednja |
| F04 | Virtualno stanje | Uporabnik lahko spremlja količino virtualnega denarja na svojem računu. Stanje se posodablja glede na rezultate igranja. | Visoka |
| F05 | Igra Mines | Uporabnik lahko igra igro Mines na mreži velikosti 5 × 5. Pri igranju izbira polja in poskuša doseči čim boljši rezultat. | Visoka |
| F06 | Igra Balloon | Uporabnik lahko igra igro Balloon, v kateri spremlja naraščanje množitelja. Cilj je pravočasno zaključiti igro in doseči čim boljši rezultat. | Visoka |
| F07 | Igra Cards | Uporabnik lahko igra igro s kartami in na podlagi pravil igre dosega rezultate. | Visoka |
| F08 | Igra Click | Uporabnik lahko igra igro Click, ki temelji na klikanju in doseganju čim boljšega rezultata. | Srednja |
| F09 | Shranjevanje rezultatov | Sistem shranjuje rezultate uporabnika v podatkovno bazo. Uporabnik lahko tako ohrani svoje dosežke tudi po ponovni prijavi. | Visoka |
| F10 | Lestvica najboljših | Uporabnik lahko pregleda lestvico najboljših igralcev in primerja svoje rezultate z drugimi uporabniki. | Srednja |
| F11 | Uporabniški profil | Uporabnik lahko dostopa do svojega profila in pregleda osnovne podatke svojega računa. | Srednja |
| F12 | Preverjanje uporabniških podatkov | Sistem preverja pravilnost podatkov pri registraciji in prijavi. S tem preprečuje vnos neveljavnih podatkov. | Visoka |
| F13 | Avtentikacija uporabnikov | Sistem uporablja JWT za preverjanje identitete prijavljenega uporabnika in zaščito dostopa do uporabniških podatkov. | Visoka |
| F14 | Varno shranjevanje gesel | Sistem gesla uporabnikov pred shranjevanjem obdela z uporabo bcrypt. Gesla se tako ne shranjujejo v navadni besedilni obliki. | Visoka |

## Ocena prioritet

- **Visoka** – funkcionalnost je nujna za osnovno delovanje aplikacije.
- **Srednja** – funkcionalnost izboljšuje uporabniško izkušnjo, vendar ni nujna za osnovno delovanje sistema.
- **Nizka** – funkcionalnost je dodatna in jo je mogoče implementirati pozneje.
