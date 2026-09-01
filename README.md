# Marketing Ignorante

Repo della testata **MarkeThings — firma "Marketing Ignorante"**.

## Cos'è

Una pubblicazione con voce, audience e obiettivi propri. Non è il brand personale di
Stefano: chi parla è una redazione al plurale.

| | Marketing Ignorante | da 0 al PMF |
|---|---|---|
| Chi parla | Plurale redazionale ("noi", "lascia che ti raccontiamo") | Stefano, prima persona singolare |
| Chi legge | Founder e marketer che devono lanciare **senza budget** | Founder B2B tech in growth |
| Di cosa parla | Campagne e brand, spesso consumer | Positioning, product marketing, GTM B2B |
| Registro | Frasi cortissime, ritmo parlato, zero gergo da consulente | Diretto, tecnico quando serve |
| Obiettivo | Iscritti alla newsletter | Lead per la consulenza |

"da 0 al PMF" vive in un repo separato, `System-content-flywheel`. Le due pubblicazioni
hanno condiviso un repo fino a settembre 2026: la convivenza funzionava a colpi di divieti
("non caricare la foundation dell'altro"), che era il sintomo di due cose che volevano
stare separate. Adesso lo sono, e quei divieti non servono più.

## Cosa c'è dentro

```
CLAUDE.md     regole, voce, workflow — si legge per primo
knowledge/    voce, ipotesi in test, log delle performance
newsletter/   numeri settimanali archiviati (input)
notes/        Substack Notes prodotte da ogni numero (output)
articoli/     pezzi pubblicati della rubrica How Small Brands Grow
.claude/      la skill di progetto marketing-ignorante-notes
```

## Le due linee editoriali

1. **Numero settimanale** — ogni sabato: 3 campagne di brand spiegate, 1 tool utile,
   1 tema come provocazione. È la fonte delle Notes.
2. **How Small Brands Grow** — rubrica mensile, storie di prime mosse di brand.
   Gestita dalla skill globale `how-small-brands-growth`.

## Il flusso Notes

Ogni numero diventa 3-4 Substack Notes, una al giorno, per crescere dentro l'ecosistema
Substack.

- **Si costruisce** in Claude Code (skill, knowledge, commit)
- **Si usa** in Cowork ogni sabato: si incolla il numero, si ottengono le Notes

La skill `marketing-ignorante-notes` è di progetto: vive in `.claude/skills/` e viaggia
con questo repo, quindi è disponibile ovunque lo cloni senza dipendere dalla
sincronizzazione del brain globale.

## Dopo la pubblicazione

Ogni Note pubblicata va registrata in [knowledge/log.md](knowledge/log.md).
Quando un'ipotesi in [knowledge/ipotesi.md](knowledge/ipotesi.md) viene confermata 3 volte,
diventa una regola in `.claude/skills/marketing-ignorante-notes/references/formati-note.md`.

## Git

Repo locale, nessun remote. I contenuti sono stati per un periodo dentro
`System-content-flywheel`, che è pubblico, e restano nella sua history.