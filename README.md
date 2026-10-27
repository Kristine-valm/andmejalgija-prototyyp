# Andmejälgija kirje prototüüp

Prototüüp ettepanekule muuta [Andmejälgija](https://www.ria.ee/riigi-infosusteem/inimkeskne-andmehaldus/andmejalgija) kirje andmeväljad protokolli v3-s kohustuslikuks ja ühtseks ning luua ühine eesmärkide kataloog. Eesmärk on, et inimene saaks igast kirjest aru, **kes** ja **miks** tema andmeid vaatas.

TalTech · Digital Government Challenge 2026

## Vaated

| Fail | Sisu |
| --- | --- |
| `index.html` | Avaleht ja viited kõikidele vaadetele |
| `andmevaljad.html` | **Põhiettepanek:** üks kirje praegu ja ettepaneku järgi, iga välja seos v3 protokolliga |
| `praegune.html` | Lähteolukord: kirjed tabelina (koodid, tehnilised tegevuste nimed) |
| `uus.html` | Klikitav vaade hilisemate sammudega: filter, üksikasjad, grupeerimine, „Küsi selgitust“, „Ei tunne ära“ |
| `kusitlus.html` | Küsitluse A/B kõrvutus: sama sündmus kahel kujul |

## Avamine

Ava `index.html` brauseris. Kõik failid töötavad ilma serverita; fondid laaditakse Google Fontsist.

### GitHub Pages

1. **Settings › Pages**
2. Source: **Deploy from a branch**, branch **main**, kaust **/ (root)** › **Save**
3. Leht ilmub aadressile `https://<kasutajanimi>.github.io/<repo-nimi>/`

## Märkused

- Kõik andmed on **näidisandmed**. Registrikoodid ja kirje tunnused on välja mõeldud; nurksulgudes kohad (nt `§ [X]`) on meelega täitmata.
- Kujundus on neutraalne ega kopeeri eesti.ee-d.
- „Uue vaate“ nupud on simulatsioon: midagi ei saadeta ega salvestata.
- Väljanimed (`purposeCode`, `accessType` jne) on ettepanek; lõpliku kuju otsustab RIA.

## Allikad

- [e-gov/AJ](https://github.com/e-gov/AJ) – Andmejälgija dokumentatsioon, sh [protokoll v3](https://github.com/e-gov/AJ/blob/master/doc/spetsifikatsioonid/dumonitor-openapi-v3.yaml)
- [RIA: Andmejälgija uueneb](https://www.ria.ee/riigi-infosusteem/inimkeskne-andmehaldus/andmejalgija#uueneb)
