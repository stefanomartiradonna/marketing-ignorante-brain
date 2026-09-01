# Marketing Ignorante — Cervello della Pubblicazione

Questo file è il punto di ingresso di ogni sessione su Marketing Ignorante.
Leggilo integralmente prima di qualsiasi task.

---

## Cos'è

**MarkeThings**, firma **"Marketing Ignorante"**. Una pubblicazione con voce, audience e
obiettivi propri, gestita da Stefano Martiradonna ma **separata dal suo brand personale**.

Chi parla non è Stefano in prima persona: è una redazione al plurale. "Noi", "lascia che
ti raccontiamo". Questa non è una sfumatura di stile, è l'identità della testata.

| | Marketing Ignorante | da 0 al PMF (altro repo) |
|---|---|---|
| Chi parla | Plurale redazionale, "noi" | Stefano, prima persona singolare |
| Chi legge | Founder e marketer che devono lanciare **senza budget** | Founder B2B tech in growth |
| Di cosa parla | Campagne e brand, spesso consumer | Positioning, product marketing, GTM B2B |
| Registro | Frasi cortissime, ritmo parlato, zero gergo da consulente | Diretto, tecnico quando serve |
| Obiettivo | Iscritti alla newsletter | Lead per la consulenza |

**La voce sta in `knowledge/voce.md`. Leggila sempre prima di scrivere qualsiasi cosa.**

Questa pubblicazione viveva dentro il repo di "da 0 al PMF" e ci convive per anni a colpi
di divieti ("non caricare la foundation dell'altro"). Adesso ha casa sua: quei divieti non
servono più, perché non c'è più niente da cui difendersi. Se ti serve contesto sull'altra
pubblicazione, è in `System-content-flywheel`, ed è un repo diverso di proposito.

---

## Le due linee editoriali

**1. Il numero settimanale.** Ogni sabato: 3 campagne di brand spiegate, 1 tool utile,
1 tema come provocazione. È il prodotto principale e la fonte di tutto il resto.
I numeri archiviati stanno in `newsletter/`, indicizzati in `newsletter/INDEX.md`.

**2. How Small Brands Grow.** Rubrica mensile: storie delle prime mosse di brand piccoli
e challenger. Framework dei 5 vettori di disruption (Kinner) e evidenza sulla
differenziazione (Pauwels). I pezzi pubblicati stanno in `articoli/`.

---

## Cosa produce questo repo

| Tipo di output | Dove va | Skill |
|---|---|---|
| Substack Notes da un numero | `notes/` | `marketing-ignorante-notes` (skill di progetto, in `.claude/skills/`) |
| Pezzo della rubrica HSBG | `articoli/` | `how-small-brands-growth` (skill globale) |
| Numero settimanale archiviato | `newsletter/` + riga in `newsletter/INDEX.md` | nessuna, è archiviazione |

Convenzione nome file: `[Topic]-[Angle-o-Data].md`.
Per gli articoli HSBG: `HSBG-[Brand]-[Angolo]-[AAAA-MM].md`.

---

## Il flusso Notes

Ogni numero settimanale diventa 3-4 Substack Notes, una al giorno. L'obiettivo è farsi
conoscere dentro l'ecosistema Substack e far crescere gli iscritti.

- **Si costruisce qui** in Claude Code: skill, knowledge, commit
- **Si usa in Cowork** ogni sabato: si incolla il numero, si ottengono le Notes

La skill `marketing-ignorante-notes` è **di progetto**, non globale: vive in
`.claude/skills/` e viaggia con questo repo. Ovunque lo cloni, la skill c'è, senza
dipendere dalla sincronizzazione del brain globale.

---

## Knowledge

- `knowledge/voce.md` — tono, ritmo, parole ammesse e vietate, esempi giusto/sbagliato.
  Il file più importante del repo.
- `knowledge/ipotesi.md` — cosa stiamo testando e su quale evidenza.
- `knowledge/log.md` — Notes pubblicate e come sono andate.

**Dopo ogni pubblicazione**: registra la Note in `knowledge/log.md`.
Quando un'ipotesi si conferma 3 volte, diventa una regola in
`.claude/skills/marketing-ignorante-notes/references/formati-note.md` ed esce da `ipotesi.md`.

Non chiedere autorizzazione per aggiornare i file in `knowledge/`. Chiedi solo per
modificare questo CLAUDE.md.

---

## Voce: i non negoziabili

Il dettaglio sta in `knowledge/voce.md`, ma questi valgono sempre:

- Plurale redazionale, mai "io"
- Frasi corte. Ritmo parlato. Si legge ad alta voce e deve suonare come una persona che parla
- Zero gergo da consulente
- Nessuna parola inglese dove esiste quella italiana
- Mai il trattino medio (—): virgole, punti, due punti, frasi separate

---

## Git

Repo locale, nessun remote. Commit liberi sui file di contenuto e di knowledge.

**Nota**: i contenuti di questo repo sono stati per un periodo dentro
`System-content-flywheel`, che è pubblico su GitHub, e restano nella history di quel repo.
Se un domani questo repo va su GitHub, la scelta pubblico/privato va fatta sapendo che
contiene bozze e ipotesi non ancora pubblicate.