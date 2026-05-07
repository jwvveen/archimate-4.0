# archimate-4.0
ArchiMate 4.0 artifacts

## Hoe gebruik je dit?

  **Importeren in Archi:**
  1. Download `archisurance-3.0.xml`
  2. In Archi: File → Import → Open Exchange XML → kies het bestand
  3. Het model is direct werkbaar (139 elementen, 178 relaties, 17 views)

  **Eigen model migreren:**
  De volledige migratie-tool staat in een [aparte repo / niet hier] maar
  de output (`report.html`, `report.pdf`) toont wat je kunt verwachten
  voor een willekeurig 3.2-model. Onze experimenten op een productie-model
  van 5.000+ elementen lieten zien:
  - ~40% van de elementen krijgt een specialization-profile
  - 1–3% van de relaties is ongeldig in 4.0 en wordt automatisch gefixt
  - Een handvol relaties was al ongeldig in 3.2 (bron-fouten)

  ## Verantwoording / bronnen

  - ArchiMate® 4 Specification (C260) — The Open Group, april 2026
  - The Motivation for Changes in ArchiMate® 4 — W262, april 2026
  - ArchiSurance Case Study — The Open Group, 2010 (origineel AMEFF v2.1)
  - Archi tool — https://www.archimatetool.com/

  ArchiMate® is een geregistreerd handelsmerk van The Open Group.

  ## Licentie

  Het ArchiSurance-model valt onder de licentie van The Open Group
  (zie `<dc:rights>` in de XML). De relatiematrix en het audit-rapport
  zijn afgeleid werk en mogen vrij worden gebruikt voor educatieve en
  review-doeleinden, met bronvermelding.
