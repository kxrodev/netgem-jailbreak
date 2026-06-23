# Netgem N7950 Alpine Linux -modi

> Elisa Viihde -boksin vapauttaminen Alpine Linuxilla.

**Founded & documented by KXRO**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📋 Sisällysluettelo

- [Mitä tämä on](#mitä-tämä-on)
- [Mitä tarvitset](#mitä-tarvitset)
- [Ohjeet](#ohjeet)
- [Vaihtaminen Elisan ja Linuxin välillä](#vaihtaminen)
- [Virheilmoitukset](#virheilmoitukset)

---

## Mitä tämä on

Tämä projekti sisältää ohjeet Elisa Viihde -boksin (Netgem N7950) modaamiseen.

Boksiin asennetaan Alpine Linux, ja sen voi bootata USB-tikulta.

---

## Mitä tarvitset

| Tarvike | Selitys |
|---------|---------|
| Elisa Viihde -boksi (Netgem N7950) | Projektiin tarvittava laite |
| TTL-sarja-adapteri (3.3V) | Yhteys tietokoneen ja boksin välille |
| Paperclipit (tai hyppylangat) | UART-pinnien kytkentä |
| Tietokone (Linux) | Nobara, Ubuntu, tms. |
| 8GB+ USB-tikku | Alpine Linuxin asennus |

---

## Ohjeet

1. Avaa boksi
2. Etsi UART-pinnit
3. Kytke TTL-adapteri
4. Yhdistä tietokoneeseen
5. Pysäytä U-Boot
6. Boottaa Alpine USB:ltä

Katso tarkemmat ohjeet [index.html](index.html):sta.

---

## Vaihtaminen Elisan ja Linuxin välillä

| Mitä haluat | Mitä teet |
|-------------|-----------|
| Käynnistä Alpine Linux | Aseta USB-tikku kiinni ja käynnistä boksi |
| Käynnistä Elisa | Poista USB-tikku ja käynnistä boksi |

---

## Virheilmoitukset

| Ongelma | Ratkaisu |
|---------|----------|
| Ei tekstiä terminaalissa | Vaihda TX ja RX keskenään |
| Roskamerkkejä | Kokeile baud-nopeutta 57600 tai 9600 |
| Paperclipit liikkuvat | Kiinnitä ne teipillä |

---

## Lisenssi

MIT License – katso [LICENSE](LICENSE)-tiedosto.

---

**ELISA COULD NEVER**
