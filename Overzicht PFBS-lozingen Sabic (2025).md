markdown_content = """# Overzicht PFBS-lozingen Sabic (2025)

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

file_path = "PFBS_lozingen_Sabic_2025.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"File {file_path} generated successfully.")
