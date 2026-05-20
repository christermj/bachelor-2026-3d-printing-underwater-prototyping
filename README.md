# Bachelor Oppgave 2026: 3D-Printing i Undervannsmiljøer

## 📚 En helhetlig studie av 3D-printet prototyping for bruk i undervannsmiljøer

**Hovedoppgaven:** [`Bachelor Maskiningeniør 2026.pdf`](./rapport/Bachelor%20Maskiningeni%C3%B8r%202026.pdf)

---

## 👥 Forfattere

- Christer Markussen Jusnes
- Tor Henrik Lehne
- Veronika Hesle
- Emilie Enerhaugen Thrane
- Jonatan Graff Ravnvik

## 🎓 Veiledere

- Karl Thomas Hjelmervik
- Agne Johannessen

## 🤝 Faglig oppfølging & Samarbeid

- **Kongsberg Discovery AS**
  - Robin Heggelund
  - Robert Kovacs

## 🏛️ Institusjon

**Universitetet i Sørøst-Norge (USN)**
- Fakultet for teknologi, naturvitenskap og maritime fag
- Institutt for mikrosystemer

---

## 📋 Abstrakt

Bacheloroppgaven undersøker hvordan FDM-printede polymerer påvirkes av langtidseksponering i saltvann, og hvordan enkle overflatebehandlinger kan redusere vanninntrengning i 3D-printede undervannskapslinger. PLA, PETG og ASA ble testet gjennom strekkprøving, vannopptaksmåling, Arrhenius-analyse, kompresjonstester, overflatebehandling og mikroskopi. Arbeidet er knyttet til utvikling av en 3D-printet elektronikkapsling for undervannsbruk i samarbeid med Kongsberg Discovery AS.

---

## 🔬 Hovedfunn & Resultater

| Funn | Detaljer |
|------|----------|
| **ASA - Best materiale** | ASA var det mest stabile materialet ved saltvannseksponering og anbefales som førstevalgsmateriale for videre prototyping i undervannsmiljøer. |
| **PLA degradering** | PLA viste betydelig hydrolytisk degradering og vurderes som lite egnet for marin bruk uten beskyttelse. |
| **PETG kompleks respons** | PETG viste en mer sammensatt respons, med tegn til både degradering og forbedrede mekaniske egenskaper ved høyere temperaturer. |
| **Materialsranking** | Ubehandlede materialer rangert som: **ASA > PETG > PLA** |
| **Termisk glødeeffekt** | Eksponering nær glasstransisjonstemperaturen kan gi en termisk glødeeffekt som forbedrer mekaniske egenskaper, særlig for PETG og ASA. |
| **Best overflatebehandling** | Jotun Vinyl Primer ga best resultat blant overflatebehandlingene, med **0 % masseøkning** i nedsenkningstest. |
| **Tetningskriteria** | Jevn overflatefinish og god pakningskontakt ble vurdert som avgjørende for tetning under hydrostatisk trykk. |
| **Prototypekapsling** | En FDM-printet prototypekapsling ble utviklet som konseptdemonstrator. |

---

## 📁 Filstruktur

```
.
├── README.md                           # Denne filen
├── rapport/Bachelor Maskiningeniør 2026.pdf
│   └── 
├── vedlegg/
│   ├── Vedlegg 1 - Strekkdata grafvedlegg.pdf
│   ├── Vedlegg 2 - Intervju med Olav Håskjold.pdf
│   ├── Vedlegg 3 - Intervju med Magnus Hesle.pdf
│   ├── Vedlegg 4 - Budsjett.pdf
│   └── Vedlegg_strekkmaskin-hastighet_v2.docx
├── data/
│   ├── filament-datablader/
│   │   ├── PLA-datasheet.pdf
│   │   ├── PETG-datasheet.pdf
│   │   └── ASA-datasheet.pdf
│   ├── ekstra/
│   │   ├── Beskrivelse av gjennomføring av veiing.docx
│   │   ├── Beskrivelse av strekktest og registrering av resultater.docx
│   │   ├── Liste over hva vi ser etter under mikroskopering.docx
│   │   ├── Møtereferat Magnus Hesle.docx
│   │   └──  Møtereferat Olav Håskjold.docx
│   ├── Gjennomsnitt strekkprøver.xlsx
│   ├── Vannopptak - masseendring over tid - Tabeller (Diagrammer for vektendring, permanent vektendring og prosentberegning).xlsx
│   ├── arrhenius_graph_endelig_versjon.xlsx
│   └── Lakkering.xlsx
├── figurer/
│   ├── mikroskopi/                     # Mikroskopibilder
│   └── illustrasjoner/                 # Andre bilder og illustrasjoner
└── cad/
    ├── prototypekapsling/              # 3D-modeller av kapslingen
    └── tegninger/                      # 2D tekniske tegninger
```

---

## 📂 Mapper

### 📄 [`rapport/`](./rapport/)
Hovedoppgaven i fullt format

### 📎 [`vedlegg/`](./vedlegg/)
Alle vedlegg til oppgaven:
- Strekkdata grafer (PDF)
- Intervjuer
- Budsjett

### 📊 [`data/`](./data/)
Rådata og datasett:
- **`filament-datablader/`** - Datablader fra produsenter for PLA, PETG og ASA
- **`ekstra/`** - Datafiler som er omarbeidet, strukturert eller brukt som grunnlag
- Strekkprøvedata (gjennomsnitt)
- Lakkerings-data

### 🖼️ [`figurer/`](./figurer/)
Supplerende visuell dokumentasjon fra prosjektet, for eksempel mikroskopibilder og prosjektbilder som ikke nødvendigvis inngår direkte i hovedrapporten.

### 🏗️ [`cad/`](./cad/)
CAD-modeller og tekniske tegninger av prototypekapslingen

---

## 🔬 Metodologi

Oppgaven undersøker:
- **FDM 3D-printing** av polymerer
- **Materialer testert**: PLA, PETG, ASA
- **Tester utført**:
  - Strekkprøving
  - Vannopptaksmåling
  - Arrhenius-analyse
  - Kompresjonstester
  - Overflatebehandlinger
  - Mikroskopi
- **Miljø**: Saltvannseksponering (marin miljø)

---

## 🎯 Konklusjon

ASA anbefales som førstevalgsmateriale for 3D-printede undervannsprototyper. Overflatebehandling med Jotun Vinyl Primer viste lovende resultater for ytterligere beskyttelse.

---

## 📧 Kontakt

**Forfattere:**
- Christer Markussen Jusnes - christermj@live.no
- Tor Henrik Lehne - thlehne@gmail.com
- Veronika Hesle - veronikahesle@gmail.com
- Emilie Enerhaugen Thrane - emiliethra98@hotmail.com
- Jonatan Graff Ravnvik - jonatan.graff@outlook.com

---

## 📅 Dato

**2026**

---

*Sist oppdatert: 2026-05-19*
