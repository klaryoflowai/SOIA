# SOIA Vault

Acest vault este contextul permanent al proiectului **SOIA** si al agentiei **KlaryoFlow AI**. El centralizeaza pozitionarea, produsul, operarea si materialele comerciale intr-un format util in Obsidian, AI tools si GitHub.

## Start Rapid

- [Welcome](Welcome.md) - hub-ul principal de navigare in vault
- [AGENTS.md](AGENTS.md) - contextul principal pentru Codex
- [CLAUDE.md](CLAUDE.md) - contextul principal pentru Claude
- [01_Brand/Identitate-KlaryoFlow.md](01_Brand/Identitate-KlaryoFlow.md) - identitate, misiune, promisiune
- [02_Produs/Arhitectura-SOIA.md](02_Produs/Arhitectura-SOIA.md) - arhitectura produsului
- [03_Go_To_Market/Plan-90-Zile.md](03_Go_To_Market/Plan-90-Zile.md) - planul de lansare
- [04_Operare/SOP-Audit-Gratuit.md](04_Operare/SOP-Audit-Gratuit.md) - procesul comercial de audit
- [05_Clienti/Client-Template/Fisa-Client.md](05_Clienti/Client-Template/Fisa-Client.md) - template standard de client
- [06_Templates/Oferta-Client.md](06_Templates/Oferta-Client.md) - oferta reutilizabila
- [98_Imported/README.md](98_Imported/README.md) - context legacy pastrat pentru trasabilitate
- [99_Surse/Surse-si-Asumptii.md](99_Surse/Surse-si-Asumptii.md) - surse, asumptii si completari

## Ce Contine

Vault-ul tine intr-un singur loc:

- ce vindem
- cui vindem
- cum livram
- cum documentam clientii
- cum operam proiectul

Este gandit pentru 3 moduri de folosire:

1. in Obsidian, ca spatiu de lucru zilnic
2. in Codex si Claude, ca memorie structurata pentru AI
3. in GitHub, ca repository privat de context si operare

## Reguli De Lucru

- Nu pune secrete in vault.
- Nu pune parole, token-uri sau date bancare.
- Un client = un folder dedicat.
- Orice discutie importanta trebuie rezumata in aceeasi zi.
- Orice schimbare de oferta sau pozitionare trebuie reflectata in `AGENTS.md` si `CLAUDE.md`.
- Cand o informatie nu este inca sigura, marcheaz-o explicit cu `[DE COMPLETAT]`.

## Structura

- `01_Brand` - identitate, mesaje, pitch-uri
- `02_Produs` - produsul SOIA, interfata, pricing
- `03_Go_To_Market` - lansare, vanzare, riscuri
- `04_Operare` - SOP-uri si mod de lucru
- `05_Clienti` - template-uri si studii de caz
- `06_Templates` - documente gata de reutilizat
- `98_Imported` - context legacy si materiale brute
- `99_Surse` - surse, asumptii si trasabilitate

## GitHub

Repo-ul tinta pentru publicare este:

- `https://github.com/klaryoflowai/SOIA`

Acest vault este pregatit pentru un repo separat, cu urmatoarele reguli:

- notele curate, SOP-urile si template-urile se versioneaza
- `.obsidian` ramane partial versionat pentru preferintele comune
- fisierele locale volatile, exporturile temporare si `.env*` se ignora prin `.gitignore`
- `98_Imported` ramane in repo doar ca arhiva de context, nu ca sursa activa de lucru

## Originea Materialelor

Vault-ul curent a fost construit din:

- contextul existent din `klaryoflow-context`
- planul strategic de 90 zile
- mockup-ul de interfata SOIA
- materialele deja scrise pentru audit, pitch si template-uri
