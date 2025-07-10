---
title: Käyttöjärjestelmät
layout: home
nav_order: 4
---

# Käyttöjärjestelmät
Useat käyttöjärjestelmät ovat täynnä seurantaa, ja jopa mahdollisia takaovia/haavoittuvuuksia.

Täältä löydät monia käyttöjärjestelmiä puhelimille ja tietokoneille.

---
# Android käyttöjärjestelmät
## GrapheneOS --- Turvallisuuden ja yksityisyyden kultastandardi

 - **Google-riippumattomuus:** Ei sisällä Googlen palveluita oletuksena
 - **Sovellustuki:** Tukee Android-sovelluksia; Google Play -tuki saatavilla eristettynä (valinnaisesti)
 - **Yksityisyys:** Ei sisäänrakennettua seurantaa tai telemetriaa
 - **Turvallisuus:** Kovennetut suojausasetukset ja päivitetyt suojaustasot
 - **Käyttöoikeudet:** Tarkka hallinta sijaintiin, kameraan ja mikrofoniin
 - **Profiilit:** Useiden käyttäjä- tai työtunnusten tuki, täydellä eristyksellä

**[Tästä GrapheneOS:n ohjeisiin!]**

---
## CalyxOS --- Helppokäyttöisempi kuin GrapheneOS

 - **Google-riippumattomuus:** Ei sisällä Googlen palveluita oletuksena, mutta Google Play -palvelut voi asentaa helposti
 - **Sovellustuki:** Tukee Android-sovelluksia; Play-palvelut valinnaisesti esiasennettavissa sandboxattuna
 - **Yksityisyys:** Ei sisäänrakennettua telemetriaa; sisältää yksityisyyttä parantavia oletussovelluksia
 - **Turvallisuus:** Käyttää osin samoja suojaustekniikoita kuin GrapheneOS, mutta ei yhtä kovennettu
 - **Käyttöoikeudet:** Tarkka hallinta sijaintiin, kameraan ja mikrofoniin; integroitu Privacy Guard
 - **Profiilit:** Tukee Androidin monikäyttäjäominaisuutta, mutta ei yhtä eristetysti kuin GrapheneOS

**[Tästä CalyxOS:n ohjeisiin!]**

---
## LineageOS --- Hyvä vaihtoehto muille kuin Google puhelimille

 - **Google-riippumattomuus:** Ei sisällä Googlen palveluita oletuksena; MicroG-versio saatavilla erikseen
 - **Sovellustuki:** Tukee Android-sovelluksia; Google Play -tuki mahdollista erillisellä GApps-asennuksella
 - **Yksityisyys:** Perus-AOSP-tasoinen yksityisyys; MicroG-versiossa vähemmän riippuvuutta Googleen
 - **Turvallisuus:** Ei erityisiä kovennuksia oletuksena; riippuu pitkälti laitekohtaisista päivityksistä
 - **Käyttöoikeudet:** Tarjoaa pääsyn sovellusoikeuksiin, mutta ei yhtä tarkkaa hallintaa kuin CalyxOS/GrapheneOS
 - **Profiilit:** Tukee useita käyttäjiä; ei lisäeristystä tai erillisiä suojausominaisuuksia

**[Tästä LineageOS:n ohjeisiin!]**

---
# Linux käyttöjärjestelmät
## Tails --- Kannettava käyttöjärjestelmä

 - **Toimintaperiaate:** Live-USB-käyttöjärjestelmä, joka ei jätä jälkiä koneeseen
 - **Yksityisyys:** Kaikki verkkoliikenne kulkee Tor-verkon kautta automaattisesti
 - **Muistin käyttö:** Käyttää ainoastaan RAM-muistia – sammuttaminen tyhjentää kaiken
 - **Tallennus:** Ei tallenna tiedostoja pysyvästi ilman erillistä salattua "Persistence"-asetusta
 - **Anonyymiteetti:** Suunniteltu käytettäväksi anonyymisti missä tahansa tietokoneessa
 - **Esiasennettu ohjelmisto:** Sisältää turvalliset sovellukset kuten Tor Selain, KeePassXC, OnionShare ja Kleopatra
 - **Käyttötarkoitus:** Aktivistit, journalistit, ilmiantajat – käyttäjät jotka tarvitsevat korkean tason yksityisyyttä

**[Siirry tästä Tails:in ohjeisiin!]**

---
## QubesOS --- Kohtuullisen turvallinen käyttöjärjestelmä

 - **Toimintaperiaate:** Eristää eri toiminnot virtuaalikoneisiin (“qubes”) suojaten niitä toisiltaan
 - **Yksityisyys:** Sovellukset ja tiedot eroteltu turvallisuusalueisiin, esim. pankki, työ ja henkilökohtainen
 - **Muistin käyttö:** Jokainen "qube" toimii omassa eristetyssä tilassaan, joka voidaan sulkea milloin tahansa
 - **Tallennus:** Jokaisella qubellä on oma tiedostojärjestelmä, pysyvä tai tilapäinen käyttäjän asetusten mukaan
 - **Anonyymiteetti:** Tukee Whonix-qubea Tor-verkkoa varten täysin eristettynä muista qubeista
 - **Esiasennettu ohjelmisto:** Sisältää työpöytäsovelluksia kuten Firefox, Thunderbird ja tiedostoselaimet erillään
 - **Käyttötarkoitus:** Kehittyneille käyttäjille, jotka tarvitsevat maksimaalista suojaa ja lokeroitua ympäristöä

**[Siirry tästä QubesOS:n ohjeisiin!]**

---
**Siirry seuraavaksi [salaukseen]**


[Tästä GrapheneOS:n ohjeisiin!]: https://grapheneos.org/install/web
[Tästä CalyxOS:n ohjeisiin!]: https://calyxos.org/install/
[Tästä LineageOS:n ohjeisiin!]: https://wiki.lineageos.org/devices/
[Siirry tästä Tails:in ohjeisiin!]: https://tails.net/install/index.en.html
[Siirry tästä QubesOS:n ohjeisiin!]: https://www.qubes-os.org/downloads/
[salaukseen]: https://yksityisyys.fi/salaus.html