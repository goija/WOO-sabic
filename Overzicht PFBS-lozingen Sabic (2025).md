markdown_content = """# Overzicht PFBS-lozingen Sabic (2025)

https://www.rechtspraak.nl/organisatie-en-contact/organisatie/rechtbanken/rechtbank-oost-brabant/nieuws/2025/10/plasticfabrikant-moet-lozen-van-pfbs-in-westerschelde-beperken

Op basis van de verstrekte documenten is hier een overzicht van de PFBS-lozingen door Sabic in 2025.

## Naleving van de Jaarvrachtlimiet
Sinds de beschikking van 25 maart 2025 (kenmerk D2024-00172939) is Sabic verplicht om maandelijks de geloosde vracht aan PFBS te rapporteren. Hoewel de jaarlijkse limiet van **2,75 kilogram** een harde grens is, wordt in de rapportages opgemerkt dat de sommatie van maandvrachten kan afwijken van de uiteindelijke bepaling van de jaarvracht door het gebruik van de voorgeschreven RWS-rekenmethode.

## Gemeten Maandvrachten (September - Oktober 2025)
De beschikbare data voor de tweede helft van 2025 toont een significante stijging in de lozingen door een specifiek incident:
* **September 2025:** Er is een verhoging van de lozingsvracht gerapporteerd op meetpunt 4 AWP.
* **Oktober 2025:** De verhoogde waarden hielden aan in deze maand.
* **Oorzaak:** Deze verhogingen in zowel september als oktober worden toegeschreven aan een incident dat is gemeld bij de Milieu Klachten Centrale (MKC) onder meldnummer **M25-11836**.

## Overige Meetgegevens 2025
* **Januari - Maart 2025:** In deze periode werd een verhoogde meetwaarde van 40 µg/l gerapporteerd voor meetpunt PIT1 LXF op 21 februari 2025. Na onderzoek bleek dit echter een verdunningsfout van het externe laboratorium te zijn; de werkelijke concentratie was 3,5 µg/l.
* **Mei 2025:** Sinds 8 mei 2025 is de nieuwe beschikking van kracht die striktere rapportage van analyserapporten en debieten vereist.

---

> **Kritiek Inzicht:**
> De overschrijdingen of verhoogde lozingen in het najaar van 2025 zijn direct gekoppeld aan het incident M25-11836. Sabic hanteert de RWS-rekenmethode (*gemiddelde concentratie × gemiddeld debiet op meetdagen × aantal dagen*) om de maandelijkse vrachten vast te stellen voor toezichthouder OMWB.
"""

```python
markdown_content = """## Meetgegevens Mei 2025 (Meetpunt 4 AWP)

Hieronder vindt u een overzicht van de beschikbare meetgegevens van het afvalwater bij Sabic voor de maand mei 2025. Conform de beschikking met kenmerk D2024-00172939 rapporteert Sabic de analyserapporten en etmaaldebieten. In mei 2025 zijn de volgende resultaten vastgelegd voor de lozing van PFBS op de locatie AWP (meetpunt 4):

| Datum | Debiet (m³) | PFBS Concentratie (ng/l) | Vracht (g/dag) |
| :--- | :--- | :--- | :--- |
| 21 mei 2025 | 5109 | 30 | 0,0032 |
| 22 mei 2025 | 4944 | 30 | 0,0032 |

### Belangrijke Observaties
* **Nieuw Laboratorium:** Vanaf 1 mei 2025 worden de analyses uitgevoerd door het laboratorium van AL-West onder een nieuw raamcontract.
* **Controlemetingen:** Tijdens de bemonstering in mei heeft de Omgevingsdienst Midden- en West-Brabant (OMWB) gelijktijdig monsters genomen om de resultaten van Sabic en het toezichthoudend orgaan beter te kunnen vergelijken.
* **Methodiek:** De monsters op de locatie AWP zijn volumeproportionele verzamelmonsters. De vracht wordt berekend door het debiet te vermenigvuldigen met de gemeten concentratie.
"""

file_path = "PFBS_lozingen_Sabic_Mei_2025_Aanvulling.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"File {file_path} generated successfully.")


```

```text
File PFBS_lozingen_Sabic_Mei_2025_Aanvulling.md generated successfully.


```

Ik heb de aanvullende gegevens verwerkt en de samengeplakte data netjes gesplitst in een overzichtelijke tabel. Het document is succesvol opgeslagen als Markdown-bestand.

[file-tag: code-generated-file-0-1781581208039502583]

Hier is een weergave van hoe de aanvulling in de opmaak is gestructureerd:

## Meetgegevens Mei 2025 (Meetpunt 4 AWP)

Hieronder vindt u een overzicht van de beschikbare meetgegevens van het afvalwater bij Sabic voor de maand mei 2025. Conform de beschikking met kenmerk D2024-00172939 rapporteert Sabic de analyserapporten en etmaaldebieten. In mei 2025 zijn de volgende resultaten vastgelegd voor de lozing van PFBS op de locatie AWP (meetpunt 4):

| Datum | Debiet (m³) | PFBS Concentratie (ng/l) | Vracht (g/dag) |
| --- | --- | --- | --- |
| 21 mei 2025 | 5109 | 30 | 0,0032 |
| 22 mei 2025 | 4944 | 30 | 0,0032 |

### Belangrijke Observaties

* **Nieuw Laboratorium:** Vanaf 1 mei 2025 worden de analyses uitgevoerd door het laboratorium van AL-West onder een nieuw raamcontract.
* **Controlemetingen:** Tijdens de bemonstering in mei heeft de Omgevingsdienst Midden- en West-Brabant (OMWB) gelijktijdig monsters genomen om de resultaten van Sabic en het toezichthoudend orgaan beter te kunnen vergelijken.
* **Methodiek:** De monsters op de locatie AWP zijn volumeproportionele verzamelmonsters. De vracht wordt berekend door het debiet te vermenigvuldigen met de gemeten concentratie.

```python
markdown_content = """## Meetgegevens September & Oktober 2025 (Locatie AWP)

Op basis van de beschikbare brondocumenten volgt hier een overzicht van de PFBS-meetgegevens van Sabic voor de maanden september en oktober 2025. In deze periode is een verhoogde lozingsvracht gerapporteerd die direct is gekoppeld aan incident M25-11836. De vrachten zijn berekend op basis van de voorgeschreven RWS-rekenmethode.

| Datum | Meetpunt | Debiet (m³) | PFBS Concentratie (ng/l) | Vracht (g/dag) |
| :--- | :--- | :--- | :--- | :--- |
| 03 sep 2025 | AWP (Sabic-14) | 5679 | 11 | 0,0625 |
| 04 sep 2025 | AWP (Sabic-15) | 5236 | -1 (LOD)* | -0,005 |
| 14 okt 2025 | AWP (Sabic-16) | [Niet vermeld] | 15 | [Niet vermeld] |
| 15 okt 2025 | AWP (Sabic-17) | [Niet vermeld] | 18 | [Niet vermeld] |

*\*LOD: Limit of Detection. Een negatieve waarde in de rapportage duidt op een resultaat onder de detectiegrens.*

### Belangrijke bevindingen over deze periode
* **Incident M25-11836:** De verhoogde concentraties in september en oktober worden direct toegeschreven aan dit incident, dat destijds werd gemeld bij de Milieu Klachten Centrale.
* **Rapportageverplichting:** Conform de beschikking van 25 maart 2025 is Sabic verplicht om deze analyserapporten en etmaaldebieten maandelijks te overleggen aan de Omgevingsdienst Midden- en West-Brabant (OMWB).
* **Analyseproblemen:** In augustus 2025 trad een fout op bij het externe laboratorium, waardoor de gewenste detectielimiet voor heranalyse niet kon worden gehaald vanwege een tekort aan monstervolume.
"""

file_path = "PFBS_lozingen_Sabic_Sep_Okt_2025_Aanvulling.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"File {file_path} generated successfully.")


```

```text
File PFBS_lozingen_Sabic_Sep_Okt_2025_Aanvulling.md generated successfully.


```

Je aanvulling is klaar en opgemaakt. De in elkaar weggewerkte gegevens in je tekst heb ik vertaald naar een duidelijke Markdown-tabel.

[file-tag: code-generated-file-0-1647481014876274640]

Hieronder kun je zien hoe de inhoud van het bestand er uit ziet. Net als bij de vorige versie heb ik de afrondende vraag ("Wilt u dat ik een overzicht maak...") eruit gehaald, zodat je een schoon document overhoudt.

## Meetgegevens September & Oktober 2025 (Locatie AWP)

Op basis van de beschikbare brondocumenten volgt hier een overzicht van de PFBS-meetgegevens van Sabic voor de maanden september en oktober 2025. In deze periode is een verhoogde lozingsvracht gerapporteerd die direct is gekoppeld aan incident M25-11836. De vrachten zijn berekend op basis van de voorgeschreven RWS-rekenmethode.

| Datum | Meetpunt | Debiet (m³) | PFBS Concentratie (ng/l) | Vracht (g/dag) |
| --- | --- | --- | --- | --- |
| 03 sep 2025 | AWP (Sabic-14) | 5679 | 11 | 0,0625 |
| 04 sep 2025 | AWP (Sabic-15) | 5236 | -1 (LOD)* | -0,005 |
| 14 okt 2025 | AWP (Sabic-16) | [Niet vermeld] | 15 | [Niet vermeld] |
| 15 okt 2025 | AWP (Sabic-17) | [Niet vermeld] | 18 | [Niet vermeld] |

**LOD: Limit of Detection. Een negatieve waarde in de rapportage duidt op een resultaat onder de detectiegrens.*

### Belangrijke bevindingen over deze periode

* **Incident M25-11836:** De verhoogde concentraties in september en oktober worden direct toegeschreven aan dit incident, dat destijds werd gemeld bij de Milieu Klachten Centrale.
* **Rapportageverplichting:** Conform de beschikking van 25 maart 2025 is Sabic verplicht om deze analyserapporten en etmaaldebieten maandelijks te overleggen aan de Omgevingsdienst Midden- en West-Brabant (OMWB).
* **Analyseproblemen:** In augustus 2025 trad een fout op bij het externe laboratorium, waardoor de gewenste detectielimiet voor heranalyse niet kon worden gehaald vanwege een tekort aan monstervolume.

## Meetgegevens Begin 2025 (Meetpunt AWP)

Hieronder vindt u de meetgegevens van begin 2025 (januari tot en met maart), ter vergelijking met de incidentperiode in het najaar. In het eerste kwartaal van 2025 werd de lozing maandelijks gemonitord. Opvallend in deze periode is de gecorrigeerde meetwaarde van februari na een laboratoriumfout.

| Datum | Debiet (m³) | PFBS Concentratie | Vracht (g/dag) |
| :--- | :--- | :--- | :--- |
| 29 jan 2025 | 52.583 | 6 ng/l | 0,32 |
| 30 jan 2025 | 53.919 | 6 ng/l | 0,32 |
| 21 feb 2025 | [Niet vermeld] | 3,5 µg/l* | [Niet vermeld] |
| 26 feb 2025 | 55.917 | 3 ng/l | 0,17 |
| 27 feb 2025 | 62.186 | 3 ng/l | 0,19 |
| 17 mrt 2025 | 5.246 | 2 ng/l | 0,01 |
| 18 mrt 2025 | 4.648 | 2 ng/l | 0,01 |

*\*De initiële meting van 40 µg/l op 21 februari bleek een verdunningsfout van het laboratorium; na heranalyse is dit gecorrigeerd naar 3,5 µg/l.*

### Kritieke Vergelijking
* **Incidentimpact:** De concentraties tijdens de normale bedrijfsvoering in het voorjaar (2-6 ng/l) liggen aanzienlijk lager dan de waarden gemeten tijdens het incident in september en oktober (11-18 ng/l).
* **Status Sabic:** Ondanks verbeteringen in de betrokkenheid van het bedrijf, bleef Sabic in de eerste helft van 2025 geclassificeerd als een "zorgdossier" of "aandachtsbedrijf".
* **Controle:** De Omgevingsdienst Midden- en West-Brabant (OMWB) voert maandelijks onafhankelijke bemonsteringen uit om de gerapporteerde cijfers van Sabic te verifiëren.

```python
markdown_content = """## Meetgegevens Begin 2025 (Meetpunt AWP)

Hieronder vindt u de meetgegevens van begin 2025 (januari tot en met maart), ter vergelijking met de incidentperiode in het najaar. In het eerste kwartaal van 2025 werd de lozing maandelijks gemonitord. Opvallend in deze periode is de gecorrigeerde meetwaarde van februari na een laboratoriumfout.

| Datum | Debiet (m³) | PFBS Concentratie | Vracht (g/dag) |
| :--- | :--- | :--- | :--- |
| 29 jan 2025 | 52.583 | 6 ng/l | 0,32 |
| 30 jan 2025 | 53.919 | 6 ng/l | 0,32 |
| 21 feb 2025 | [Niet vermeld] | 3,5 µg/l* | [Niet vermeld] |
| 26 feb 2025 | 55.917 | 3 ng/l | 0,17 |
| 27 feb 2025 | 62.186 | 3 ng/l | 0,19 |
| 17 mrt 2025 | 5.246 | 2 ng/l | 0,01 |
| 18 mrt 2025 | 4.648 | 2 ng/l | 0,01 |

*\*De initiële meting van 40 µg/l op 21 februari bleek een verdunningsfout van het laboratorium; na heranalyse is dit gecorrigeerd naar 3,5 µg/l.*

### Kritieke Vergelijking
* **Incidentimpact:** De concentraties tijdens de normale bedrijfsvoering in het voorjaar (2-6 ng/l) liggen aanzienlijk lager dan de waarden gemeten tijdens het incident in september en oktober (11-18 ng/l).
* **Status Sabic:** Ondanks verbeteringen in de betrokkenheid van het bedrijf, bleef Sabic in de eerste helft van 2025 geclassificeerd als een "zorgdossier" of "aandachtsbedrijf".
* **Controle:** De Omgevingsdienst Midden- en West-Brabant (OMWB) voert maandelijks onafhankelijke bemonsteringen uit om de gerapporteerde cijfers van Sabic te verifiëren.
"""

file_path = "PFBS_lozingen_Sabic_Begin_2025_Aanvulling.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"File {file_path} generated successfully.")

```

```text
File PFBS_lozingen_Sabic_Begin_2025_Aanvulling.md generated successfully.


```

Ik heb de meetgegevens van begin 2025 gestructureerd, omgezet naar een overzichtelijke tabel en opgeslagen in een Markdown-bestand. De afsluitende vraag heb ik, net als bij de eerdere bestanden, weggelaten voor een strak eindresultaat.

Hieronder zie je hoe het document eruitziet:

## Meetgegevens Begin 2025 (Meetpunt AWP)

Hieronder vindt u de meetgegevens van begin 2025 (januari tot en met maart), ter vergelijking met de incidentperiode in het najaar. In het eerste kwartaal van 2025 werd de lozing maandelijks gemonitord. Opvallend in deze periode is de gecorrigeerde meetwaarde van februari na een laboratoriumfout.

| Datum | Debiet (m³) | PFBS Concentratie | Vracht (g/dag) |
| --- | --- | --- | --- |
| 29 jan 2025 | 52.583 | 6 ng/l | 0,32 |
| 30 jan 2025 | 53.919 | 6 ng/l | 0,32 |
| 21 feb 2025 | [Niet vermeld] | 3,5 µg/l* | [Niet vermeld] |
| 26 feb 2025 | 55.917 | 3 ng/l | 0,17 |
| 27 feb 2025 | 62.186 | 3 ng/l | 0,19 |
| 17 mrt 2025 | 5.246 | 2 ng/l | 0,01 |
| 18 mrt 2025 | 4.648 | 2 ng/l | 0,01 |

**De initiële meting van 40 µg/l op 21 februari bleek een verdunningsfout van het laboratorium; na heranalyse is dit gecorrigeerd naar 3,5 µg/l.*

### Kritieke Vergelijking

* **Incidentimpact:** De concentraties tijdens de normale bedrijfsvoering in het voorjaar (2-6 ng/l) liggen aanzienlijk lager dan de waarden gemeten tijdens het incident in september en oktober (11-18 ng/l).
* **Status Sabic:** Ondanks verbeteringen in de betrokkenheid van het bedrijf, bleef Sabic in de eerste helft van 2025 geclassificeerd als een "zorgdossier" of "aandachtsbedrijf".
* **Controle:** De Omgevingsdienst Midden- en West-Brabant (OMWB) voert maandelijks onafhankelijke bemonsteringen uit om de gerapporteerde cijfers van Sabic te verifiëren.

## Verbetermaatregelen en Operationele Wijzigingen (2025)

Op basis van de verstrekte documenten zijn de volgende verbetermaatregelen en operationele wijzigingen door Sabic in 2025 geïdentificeerd om de lozing van PFBS te beheersen en te voldoen aan de strengere rapportage-eisen:

### Operationele & Technologische Maatregelen
* **Masterbatch-methode:** Sabic is volledig overgegaan op de masterbatch-methode voor de productie, inclusief voor glasgevulde kwaliteiten (grades), om de emissies aan de bron te minimaliseren.
* **Incidentbeheersing:** Naar aanleiding van de verhoogde lozingen in september en oktober 2025 is het incident gemeld bij de Milieuklachten Centrale (MKC) onder nummer M25-11836 voor verdere opvolging en analyse.

### Verbetering van Monitoring & Laboratoriumonderzoek
* **Nieuw Laboratoriumcontract:** Sinds 1 mei 2025 heeft Sabic een nieuw raamcontract met het laboratorium AL-West voor de uitvoering van alle afvalwateranalyses.
* **Striktere Rapportage:** Vanaf 8 mei 2025 is een nieuwe beschikking (D2024-00172939) van kracht, waarbij Sabic verplicht is om maandelijks gedetailleerde analyserapporten en etmaaldebieten te overleggen.
* **Detectiegrenzen en Heranalyses:** Bij afwijkende meetwaarden, zoals in februari 2025, voert Sabic proactief onderzoek uit en laat het monsters heranalyseren om fouten (zoals verdunningsfouten) in de laboratoriumrapportages uit te sluiten.

### Samenwerking met Toezichthouders
* **Vergelijking van Meetresultaten:** Tijdens de bemonsteringen in mei 2025 heeft de Omgevingsdienst Midden- en West-Brabant (OMWB) gelijktijdig monsters genomen. Omdat beide partijen gebruikmaken van hetzelfde laboratorium (AL-West) en dezelfde monsterpotten, kunnen de resultaten beter vergeleken en gevalideerd worden.
* **Verbeterde Houding:** In bestuurlijke verslagen wordt opgemerkt dat de houding van Sabic is verbeterd en dat het bedrijf meer betrokken is bij de PFAS-problematiek, hoewel het dossier vanwege de complexiteit nog wel als "zorgdossier" of "aandachtsbedrijf" geclassificeerd blijft.

> **Kritiek Punt:** Ondanks de verbeteringen traden in het najaar van 2025 nog incidentele verhogingen op (tot 18 ng/l PFBS), wat onderstreept dat de beheersing van de afvalwaterstroom een continu aandachtspunt blijft voor zowel Sabic als de OMWB.

```python
markdown_content = """## Verbetermaatregelen en Operationele Wijzigingen (2025)

Op basis van de verstrekte documenten zijn de volgende verbetermaatregelen en operationele wijzigingen door Sabic in 2025 geïdentificeerd om de lozing van PFBS te beheersen en te voldoen aan de strengere rapportage-eisen:

### Operationele & Technologische Maatregelen
* **Masterbatch-methode:** Sabic is volledig overgegaan op de masterbatch-methode voor de productie, inclusief voor glasgevulde kwaliteiten (grades), om de emissies aan de bron te minimaliseren.
* **Incidentbeheersing:** Naar aanleiding van de verhoogde lozingen in september en oktober 2025 is het incident gemeld bij de Milieuklachten Centrale (MKC) onder nummer M25-11836 voor verdere opvolging en analyse.

### Verbetering van Monitoring & Laboratoriumonderzoek
* **Nieuw Laboratoriumcontract:** Sinds 1 mei 2025 heeft Sabic een nieuw raamcontract met het laboratorium AL-West voor de uitvoering van alle afvalwateranalyses.
* **Striktere Rapportage:** Vanaf 8 mei 2025 is een nieuwe beschikking (D2024-00172939) van kracht, waarbij Sabic verplicht is om maandelijks gedetailleerde analyserapporten en etmaaldebieten te overleggen.
* **Detectiegrenzen en Heranalyses:** Bij afwijkende meetwaarden, zoals in februari 2025, voert Sabic proactief onderzoek uit en laat het monsters heranalyseren om fouten (zoals verdunningsfouten) in de laboratoriumrapportages uit te sluiten.

### Samenwerking met Toezichthouders
* **Vergelijking van Meetresultaten:** Tijdens de bemonsteringen in mei 2025 heeft de Omgevingsdienst Midden- en West-Brabant (OMWB) gelijktijdig monsters genomen. Omdat beide partijen gebruikmaken van hetzelfde laboratorium (AL-West) en dezelfde monsterpotten, kunnen de resultaten beter vergeleken en gevalideerd worden.
* **Verbeterde Houding:** In bestuurlijke verslagen wordt opgemerkt dat de houding van Sabic is verbeterd en dat het bedrijf meer betrokken is bij de PFAS-problematiek, hoewel het dossier vanwege de complexiteit nog wel als "zorgdossier" of "aandachtsbedrijf" geclassificeerd blijft.

> **Kritiek Punt:** Ondanks de verbeteringen traden in het najaar van 2025 nog incidentele verhogingen op (tot 18 ng/l PFBS), wat onderstreept dat de beheersing van de afvalwaterstroom een continu aandachtspunt blijft voor zowel Sabic als de OMWB.
"""

file_path = "PFBS_lozingen_Sabic_Verbetermaatregelen_2025.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"File {file_path} generated successfully.")

```

```text
File PFBS_lozingen_Sabic_Verbetermaatregelen_2025.md generated successfully.


```

Ik heb de informatie over de verbetermaatregelen overzichtelijk gestructureerd met koppen en opsommingstekens, en het geheel weer netjes weggeschreven naar een Markdown-bestand.

Hieronder kun je zien hoe de inhoud van deze aanvulling er in het bestand uitziet:

## Verbetermaatregelen en Operationele Wijzigingen (2025)

Op basis van de verstrekte documenten zijn de volgende verbetermaatregelen en operationele wijzigingen door Sabic in 2025 geïdentificeerd om de lozing van PFBS te beheersen en te voldoen aan de strengere rapportage-eisen:

### Operationele & Technologische Maatregelen

* **Masterbatch-methode:** Sabic is volledig overgegaan op de masterbatch-methode voor de productie, inclusief voor glasgevulde kwaliteiten (grades), om de emissies aan de bron te minimaliseren.
* **Incidentbeheersing:** Naar aanleiding van de verhoogde lozingen in september en oktober 2025 is het incident gemeld bij de Milieuklachten Centrale (MKC) onder nummer M25-11836 voor verdere opvolging en analyse.

### Verbetering van Monitoring & Laboratoriumonderzoek

* **Nieuw Laboratoriumcontract:** Sinds 1 mei 2025 heeft Sabic een nieuw raamcontract met het laboratorium AL-West voor de uitvoering van alle afvalwateranalyses.
* **Striktere Rapportage:** Vanaf 8 mei 2025 is een nieuwe beschikking (D2024-00172939) van kracht, waarbij Sabic verplicht is om maandelijks gedetailleerde analyserapporten en etmaaldebieten te overleggen.
* **Detectiegrenzen en Heranalyses:** Bij afwijkende meetwaarden, zoals in februari 2025, voert Sabic proactief onderzoek uit en laat het monsters heranalyseren om fouten (zoals verdunningsfouten) in de laboratoriumrapportages uit te sluiten.

### Samenwerking met Toezichthouders

* **Vergelijking van Meetresultaten:** Tijdens de bemonsteringen in mei 2025 heeft de Omgevingsdienst Midden- en West-Brabant (OMWB) gelijktijdig monsters genomen. Omdat beide partijen gebruikmaken van hetzelfde laboratorium (AL-West) en dezelfde monsterpotten, kunnen de resultaten beter vergeleken en gevalideerd worden.
* **Verbeterde Houding:** In bestuurlijke verslagen wordt opgemerkt dat de houding van Sabic is verbeterd en dat het bedrijf meer betrokken is bij de PFAS-problematiek, hoewel het dossier vanwege de complexiteit nog wel als "zorgdossier" of "aandachtsbedrijf" geclassificeerd blijft.

> **Kritiek Punt:** Ondanks de verbeteringen traden in het najaar van 2025 nog incidentele verhogingen op (tot 18 ng/l PFBS), wat onderstreept dat de beheersing van de afvalwaterstroom een continu aandachtspunt blijft voor zowel Sabic als de OMWB.
