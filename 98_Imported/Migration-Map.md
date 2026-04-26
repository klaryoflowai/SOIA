# Migration Map

Acest fisier explica unde a fost absorbit continutul util din contextul legacy si ce rol mai are arhiva.

## Regula

- structura activa de lucru este in `01_Brand` pana la `06_Templates`
- `98_Imported/klaryoflow-context-archive` ramane doar pentru trasabilitate
- daca apare o diferenta intre arhiva si notele curate, lucram in structura principala si actualizam sursele doar ca referinta

## Harta de migrare

| Sursa legacy | Nota activa | Status | Observatie |
|--------------|-------------|--------|------------|
| `klaryoflow-context/00_AGENCY/despre-klaryoflow.md` | `01_Brand/Identitate-KlaryoFlow.md` | absorbit | continut extins si restructurat |
| `klaryoflow-context/00_AGENCY/pitch-uri.md` | `01_Brand/Pitch-uri-si-Mesaje.md` | absorbit | limbaj curatat si legaturi adaugate |
| `klaryoflow-context/01_CLIENTI/client-template/fisa-client.md` | `05_Clienti/Client-Template/Fisa-Client.md` | absorbit | template simplificat pentru folosire recurenta |
| `klaryoflow-context/02_PROIECTE/demo-prieten.md` | `05_Clienti/Studii-de-Caz/Demo-Prieten.md` | absorbit | transformat in studiu de caz de validare |
| `klaryoflow-context/03_SOPs/cum-facem-audit.md` | `04_Operare/SOP-Audit-Gratuit.md` | absorbit | restructurat pe etape si output standard |
| `klaryoflow-context/04_TEMPLATES/oferta-client.md` | `06_Templates/Oferta-Client.md` | absorbit | simplificat pentru reutilizare rapida |
| `klaryoflow-context/CLAUDE.md` | `AGENTS.md` si `CLAUDE.md` | inlocuit | impartit pentru tool-urile AI curente |
| `klaryoflow-context/README.md` | `README.md` si `Welcome.md` | inlocuit | navigatie actuala separata de arhiva |

## Cand mai intram in arhiva

- cand vrem sa verificam formularea initiala a unei idei
- cand lipseste o nuanta dintr-o nota activa
- cand vrem sa urmarim sursa exacta a unui document migrat
