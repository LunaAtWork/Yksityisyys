---
title: Kleopatra
layout: home
nav_exclude: true
---
# Kleopatra
Tällä sivulla on lataus ja käyttöohjeet Kleopatraan Windowsille ja Linuxille

---
## Windows
Kleopatra Windows käyttöjärjestelmälle käy tästä linkistä: [Gpg4win] (Huom: Tämä asentaa myös muita lisäosia jotka näät [täältä])

---
## Linux
Kleopatra:n Linuxille voit asentaa täältä: [Flathub] (Huom: Tarvitset Flathub:in tätä varten, netistä löytyy ohjeita ilman Flathub:in asennusta sinun käyttöjärjestelmällesi) 

---
# Yleiset käyttöohjeet
### 1. Avaimen luominen

1. Avaa **Kleopatra**
2. Valitse **File > New OpenPGP key pair**
3. Syötä nimesi ja sähköpostiosoitteesi (voit käyttää valenimeä ja kertakäyttöpostia)
4. Valitse avaintyypiksi **RSA 4096** (suositeltu)
5. Aseta vahva salasana suojaamaan yksityisavaintasi
6. Valitse **Finish**

---
### 2. Tiedoston salaaminen

1. Valitse **Sign/Encrypt**
2. Valitse tiedosto, jonka haluat salata
3. Valitse vastaanottajan julkinen avain (tai oma, jos vain itselle)
4. Vapaaehtoisesti valitse **Sign as**, **Encrypt for me** ja valitse omat tietosi
5. Ohjelma luo salatun tiedoston (pääte `.gpg`)

---
### 3. Tekstin salaaminen

1. Avaa **Notepad** välilehti
2. Kirjoita tekstisi
3. Valitse vastaanottajan julkinen avain
4. Vaihtoehtoisesti voit valita **Encrypt for me** ja **Sign as**
5. Valitse **Encrypt Notepad** jonka jälkeen tekstisi muuttuu salatuksi
6. Lähetä salattu teksit haluamaasi kautta vastaanottajallesi

---
### 4. Allekirjoitus
 - Tiedostot tai viestit voi **allekirjoittaa** digitaalisesti varmistaaksesi aitouden
 - Valitse **Sign as** ja valitse omat tietosi
 - Vastaanottaja voi tarkistaa, ettei tiedostoa ole muokattu ja että se on sinulta

---
### 5. Avainten tuonti ja vienti

* **Tuonti:** File > Import → valitse .asc- tai .gpg-tiedosto
* **Vienti:** Valitse avain → hiiren oikealla → Export

---
### 6. Avaimen varmuuskopiointi

* Vie sekä **julkinen** että **salainen avain** (.asc tai .gpg)
* Säilytä salainen avain **vain luotettavassa ja salatussa paikassa** (esim. USB + LUKS)

---
### Yleisiä vinkkejä

* Käytä **vain julkista avainta** muiden kanssa jaettavaksi
* **Älä koskaan jaa yksityistä avaintasi tai salasanaasi**
* Voit käyttää **Tailsin Persistent Storagea** tallentaaksesi avaimet turvallisesti

---


[Gpg4win]: https://gpg4win.org/thanks-for-download.html
[täältä]: https://gpg4win.org/about.html
[Flathub]: https://flathub.org/apps/org.kde.kleopatra