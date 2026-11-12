# Saavuta 2026 – poimintoja

Muistiinpanot ja nostot Saavuta 2026 -tapahtumasta.

1. Traficom: saavutettavuusvalvonnan ajankohtaiskatsaus
2. Verkkokauppojen saavutettavuus
3. hel.fi: saavutettavuus osana kehitysprosessia
4. eBay: saavutettavuustiimin kokemuksia
5. Paneeli: Oral, OP, YLE, Kesko

---

## 1. Traficom: saavutettavuusvalvonnan ajankohtaiskatsaus

### Proaktiivisesti vai määräyksen voimalla?

Valvonnan prosessi:

1. **Valvontaohjelma** – vuosittainen ohjelma, jossa palveluntarjoajat valitaan osin harkiten, osin arpomalla. Tarkastukset tehdään sekä automaattisesti että asiantuntijavoimin.
2. **Kantelut** – kantelujen käsittely johtaa hallinnolliseen ohjaukseen.
3. **Määräykset** – tarvittaessa korjaamaan velvoitetaan määräyksellä, uhkasakon voimalla.

### Velvoitteet

- Tekniset vaatimukset
- Palautekanava sekä prosessit palautteen käsittelyyn

### Traficomin suositukset

- Huomioi saavutettavuus alusta asti – jo hankinnassa
- Huomioi sekä kehitystyö että sisältötyö
- Rakenna prosessit palautteen vastaanottamiseen
- Tee saavutettavuuden kehittämisestä jatkuvaa työtä

### Valvonta lukuina

**Vuonna 2026:**

- 234 automaattista tarkastusta
- Asiantuntijatarkastus: 22 verkkosivustoa ja 12 mobiilisovellusta
- Lisäksi korjaustarkastuksia

**Vuodesta 2020 yhteensä:** 1 451 tarkastusta, 1 055 palvelua

### Ketä valvotaan?

Tarkastuksia tehdään valtakunnallisiin palveluihin sekä alueittain väestötiheyden mukaan. Valvottavia ovat mm.:

- kunnat, virastot ja hyvinvointialueet
- työttömyys- ja eläkekassat
- oppilaitokset ja kirkot
- yhdistykset, säätiöt ja osakeyhtiöt
- julkisoikeudelliset oikeushenkilöt

### Pelkkä WCAG ei riitä

> Esimerkiksi Turun kaupungin saavutettavuusselosteessa viitataan jo EN 301 549 -standardiin WCAG-kriteerien lisäksi. Pelkästään WCAG-kriteereitä vasten tehty auditointi ei useimmiten riitä. EN 301 549 -standardin uudessa versiossa on lisävaatimuksia myös verkkosivustoille, esimerkiksi vaatimus 9.7 *User preferences for web pages*.

Lähde: turku.fi/saavutettavuusseloste

### Havaintoja direktiivin toimeenpanosta

- Painopisteenä valvonta ja ennakoiva ohjaus: *”Kuulutte lain piiriin, kannattaa hoitaa – satunnaisotanta osuu kohdalle ennemmin tai myöhemmin.”*
- Verkkokauppoja koskevat kantelut ovat nousussa.
- Vaatimuksia on päivitetty (saavutettavuusvaatimukset.fi). WCAG 2.2 tulee voimaan vuonna 2027.

### Kysymykset ja vastaukset

- Q: HiQ:lta kysymys. Onko tuleva Traficomin saavutettavuustyökalu täysin FOSS?
  A: (ei täysin mutta pyritään siihen että perusosat olisivat.)

- Q: Näkyykö AI?
  A: ei suoranaisesti mutta erittäin merkittävästi noussut esille "saavutettavuuslisäosat" joita palveluiden tuotteisiin asennetaan, useimmat eivät ole saavutettavia edes oikein asennettuna. Usein nojaudutaan tuotteisiin mutta ei hankita osaamista niitten ymmärtämiseksi.

---

## 2. Verkkokauppojen saavutettavuus

### Tutkimusasetelma

- Pintapuolinen saavutettavuus- ja ruudunlukijatestaus (Orca ja NVDA)
- 30 suurta verkkokauppaa
- 9 kriteeriä – noin 16 % WCAG AA -tason kriteereistä; suurin osa jäi siis tarkastamatta

### Tulokset

- **40 %:** ostopolku estyi kokonaan tai oli erittäin vaikea
- **80 %:** näppäimistökäytön ongelmia
- **73 %:** näppäimistökohdistus puutteellinen tai rikki – yhdestä se puuttui kokonaan
- Suurin ongelma: dialogit ja mainokset keskeyttävät ja estävät käytön

### Saavutettavuusselosteiden tarkastus

Löytyykö seloste, sisältääkö se oikeat asiat ja pitävätkö tiedot paikkansa (ajantasaisuus, yhteystiedot ym.)?

- 70 %:lta seloste löytyi
- 14 selostetta sisälsi kaikki lain vaatimat tiedot
- 11 oli päivätty yli vuosi sitten
- Yksi oli päiväämätön
- Yksi oli päivätty tulevaisuuteen
- Tuore päiväys mutta vanha sisältö: vain päivämäärää oli päivitetty

### Verkkokaupassa minimivaatimukset eivät riitä

Ostopolun ja navigaation pitää toimia, eivätkä ylimääräiset elementit saa olla esteenä. Automaatiolla päästään alkuun, mutta ihmistestaajaa tarvitaan sekä valvomaan että laajentamaan testausta.

---

## 3. hel.fi: saavutettavuus osana kehitysprosessia

### Tuttu prosessi

1. Suunnittelu, käytettävyys ja UX
2. HTML-prototyyppi (osin tekoälyavusteisesti?) ja käyttäjätestaus
3. Tekninen iterointi HTML-prototyypin pohjalta
4. Ennakkoauditointi – erittäin suuri tyytyväisyys

Helsingin design-järjestelmä (HDS) on prosessissa iso tekijä. Kyse on pitkäjänteisestä työstä.

### Esimerkkiongelmia

- Vain luku -kenttä vs. käytöstä poistettu kenttä: visuaalinen suunnittelu ja käyttötavat

### Käyttäjätestaajat

- Vakituiset pääkäyttäjät
- Sisäiset työntekijät
- Saavutettavuustestauksessa ulkopuoliset testaajat

---

## 4. eBay: saavutettavuustiimin kokemuksia

- **Komponentit edellä:** eBay UI Core on tuottanut hyviä tuloksia. Toimintamalli: tehdään saavutettavat komponentit ja ohjataan kehittäjät käyttämään niitä – tai ainakin kopioimaan niiden mallit.
- **Pieni tiimi:** saavutettavuustiimissä on 4 henkeä.
- **Ei erillistä QA:ta:** se tekee työstä vaikeampaa.
- **Ei luoteta automaatioon:** sen päälle tehdään aina manuaalista testausta.
- **Nopea julkaisutahti:** ”julkaise nopeasti, korjaa nopeasti” ei jostain syystä ulotu saavutettavuuskorjauksiin. Haasteena on pitää saavutettavuus kehityssyklissä mukana ja estää regressiot.

---

## 5. Paneeli

### Panelistit

- Päivi Salo, Oral Hammaslääkärit Oy
- Heli Jeskanen, OP Pohjola
- Minna Pöntys, YLE
- Jesse Ukkonen, Kesko / K-Ruoka
- Marko Peltonen, Q-Factory Oy

### OP

- Lakisääteisyys on ollut parasta, mitä saavutettavuudelle on tapahtunut.
- Työ pitää silti tehdä alusta asti ja nähdä sisällöllisenä asiana – ei vain teknisenä.
- Johtoryhmän valistamisella on suuri merkitys.
- **Raha motivoi!** Puhutaan asiakaskokemuksesta ja asiakkaiden menettämisestä.
- Mittaaminen on vaikeaa.

### Kesko

- Asiakkaiden kysymyksissä sana ”saavutettavuus” ei esiinny – kysymykset koskevat tiedon löytymistä (”mistä löytyy X?”). Kyse on tiedon saavutettavuudesta.
- Tekeminen: pieniä tehtäviä, pieni yksikkökustannus.
- Liiketoiminta: kysymykset koskevat palvelua.

> Saavutettavuus tekee näkyväksi huonon suunnittelun ja toteutuksen – ja sitä kautta huonon asiakaskokemuksen.

### YLE

- Palvelukielet sekä kieliasu ja sen laatu ovat merkittäviä.
