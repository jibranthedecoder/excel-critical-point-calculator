# Excel-kriittisen pisteen laskuri

Interaktiivinen HTML-versio Excel-taulukosta, jossa lasketaan kriittinen piste eli break-even-piste.

## Portfolio-tarkoitus

Tämä projekti näyttää, miten taulukkolaskentaan perustuva laskenta voidaan muuntaa pieneksi selaimessa toimivaksi laskurityökaluksi. Alkuperäinen Excel-tehtävä laski valmistusmäärän, myynnin, kiinteät kustannukset, muuttuvat kustannukset, kokonaiskustannukset, voiton ja voittoprosentin.

## HTML-laskuri

Päätyökalu on tiedostossa [`index.html`](index.html).

## Alkuperäinen todistusaineisto

Alkuperäinen tehtävä-/raporttitiedosto on mukana PDF-muodossa:

- [`Tehtävä 1 Kriittinen piste(1).pdf`](Teht%C3%A4v%C3%A4%201%20Kriittinen%20piste(1).pdf)

## Alkuperäiset arvot

| Lähtötieto | Arvo |
|---|---:|
| Lähtöarvo | 8 kpl/kk |
| Askellus | 1 kpl |
| Koneen myyntihinta | 890 €/kpl |
| Kiinteät kulut | 1900 €/kk |
| Valmistus- ja materiaalikulut | 700 €/kpl |

## Kaavat

```text
Nettomyynti = valmistusmäärä × myyntihinta
Muuttuvat kulut = valmistusmäärä × muuttuva kulu per kappale
Kokonaiskulut = kiinteät kulut + muuttuvat kulut
Voitto = nettomyynti − kokonaiskulut
Voittoprosentti = voitto / nettomyynti
Kriittinen piste = kiinteät kulut / (myyntihinta − muuttuva kulu per kappale)
```

## Tiedostot

| Tiedosto | Kuvaus |
|---|---|
| `index.html` | Excel-mallista tehty interaktiivinen laskuri |
| `Tehtävä 1 Kriittinen piste(1).pdf` | Alkuperäinen PDF-todiste Excel-tehtävästä |

## Osoitetut taidot

- Excel-laskentalogiikka
- kriittisen pisteen laskenta
- HTML/CSS/JavaScript-muunnos
- interaktiivisten syötteiden käsittely
- responsiivinen käyttöliittymäsuunnittelu
- tekninen dokumentointi

## Lisenssi

MIT License
