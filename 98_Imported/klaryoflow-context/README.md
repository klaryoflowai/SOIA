# 📁 klaryoflow-context

> Repo privat GitHub — Contextul permanent al KlaryoFlow AI
> **NU face acest repo public. Conține date confidențiale ale clienților.**

---

## Ce este acest repo

Acesta este „creierul" agenției KlaryoFlow AI.
Conține tot contextul necesar pentru ca Claude Code să înțeleagă
afacerea, clienții și procesele fără a fi nevoie de explicații repetate.

---

## Cum îl folosești cu Claude Code

### Setup inițial (o singură dată)

```bash
# 1. Clonează repo-ul pe laptop
git clone https://github.com/[USERNAME]/klaryoflow-context.git

# 2. Navighează în folder
cd klaryoflow-context

# 3. Deschide Claude Code în acest folder
claude .
```

### La fiecare sesiune nouă

```bash
# Claude Code citește automat CLAUDE.md
# Spune doar:
"Citește contextul din CLAUDE.md și spune-mi ce știi despre KlaryoFlow"
```

### Când adaugi un client nou

```bash
# Copiază template-ul
cp -r 01_CLIENTI/client-template 01_CLIENTI/[nume-client]

# Completează fișa
# Apoi sincronizează pe GitHub
git add .
git commit -m "Client nou: [nume-client]"
git push
```

---

## Structura folderelor

```
klaryoflow-context/
├── CLAUDE.md                        ← Contextul principal (citit automat)
├── README.md                        ← Ești aici
│
├── 00_AGENCY/                       ← Tot despre KlaryoFlow
│   ├── despre-klaryoflow.md
│   ├── servicii-soia.md
│   ├── pricing.md
│   └── pitch-uri.md
│
├── 01_CLIENTI/                      ← Un folder per client
│   ├── client-template/             ← Copiază asta pentru client nou
│   │   └── fisa-client.md
│   └── [nume-client]/
│       └── fisa-client.md
│
├── 02_PROIECTE/                     ← Proiecte active și studii de caz
│   └── demo-prieten.md
│
├── 03_SOPs/                         ← Procese standard
│   ├── cum-facem-audit.md
│   ├── instalare-soia-context.md
│   ├── instalare-soia-data.md
│   └── instalare-soia-auto.md
│
└── 04_TEMPLATES/                    ← Documente gata de folosit
    ├── oferta-client.md
    ├── contract-retainer.md
    └── raport-audit.md
```

---

## Sincronizare cu Obsidian (opțional)

1. Deschide Obsidian → Settings → Community Plugins
2. Instalează **Obsidian Git**
3. Configurează cu repo-ul tău GitHub
4. Setează auto-sync la fiecare 10 minute

Astfel poți edita de pe orice device cu Obsidian
și modificările ajung automat pe GitHub.

---

## Reguli importante

- **Actualizează CLAUDE.md** după orice schimbare majoră în agenție
- **Completează fișa clientului** după fiecare audit și ședință
- **Nu pune parole sau chei API** în acest repo (chiar dacă e privat)
- **Commit frecvent** — fiecare actualizare importantă merită un commit

---

*KlaryoFlow AI · Context Repository · Privat*
