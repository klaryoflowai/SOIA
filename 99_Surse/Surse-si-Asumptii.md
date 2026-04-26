# Surse si Asumptii

## Surse folosite pentru acest vault

### Context existent

Sursele brute sunt pastrate acum in:

- `98_Imported/klaryoflow-context-archive`

- `klaryoflow-context/CLAUDE.md`
- `klaryoflow-context/README.md`
- `klaryoflow-context/00_AGENCY/despre-klaryoflow.md`
- `klaryoflow-context/00_AGENCY/pitch-uri.md`
- `klaryoflow-context/01_CLIENTI/client-template/fisa-client.md`
- `klaryoflow-context/02_PROIECTE/demo-prieten.md`
- `klaryoflow-context/03_SOPs/cum-facem-audit.md`
- `klaryoflow-context/04_TEMPLATES/oferta-client.md`

### Fisiere atasate de utilizator

- `KlaryoFlow_Plan_90_Zile_v2.docx`
- `SOIA_Interface_Mockup_v2.html`

## Ce am extras din planul de 90 zile

- identitatea actuala a KlaryoFlow AI
- arhitectura oficiala in 4 niveluri
- etapele comerciale SOIA CONTEXT / DATA / AUTO
- range-urile de pricing
- planul de lansare in 90 zile
- riscurile si planul B

## Ce am extras din mockup

- structura interfetei Telegram
- structura dashboard-ului
- tipurile de KPI, alerte, taskuri si loguri
- modul de prezentare a valorii catre client

## Asumptii facute

- `SOIA [AIOS]` este vault-ul Obsidian principal care trebuie populat
- `klaryoflow-context` este sursa veche / scheletul de pornire
- repo-ul final dorit pentru context este `https://github.com/klaryoflowai/SOIA`

## Lucruri inca de completat

- numele fondatorului
- email si telefon oficial
- clientul/demo-ul oficial
- eventualele exemple reale de KPI pe industrie
- forma finala a contractului

## Observatie despre Git

Vault-ul a fost mutat in folderul dedicat:

- `/Users/yuritimofte/Desktop/SOIA [AIOS]`

Directia curenta este clara:

- vault-ul urca singur ca repo separat in `https://github.com/klaryoflowai/SOIA`
- fisierele locale volatile se exclud prin `.gitignore`
- configuratia Obsidian comuna poate ramane versionata, iar starea locala de workspace trebuie ignorata

## Observatie despre migrare

In varianta curenta, contextul vechi este importat in interiorul vault-ului, in:

- `98_Imported/klaryoflow-context-archive`

Astfel:

- vault-ul nou ramane structurat si curat
- sursa veche ramane accesibila
- sursa legacy poate fi consultata fara sa afecteze structura principala
- maparea dintre sursa veche si notele active este documentata in `98_Imported/Migration-Map.md`

## Recomandare

Dupa fiecare material nou:

1. adauga-l in surse
2. extrage ideile in note curate
3. nu lasa informatia doar in fisiere brute
