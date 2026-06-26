# Fadette — *Présages du Berry* · **preview**

> **This repository is a preview.** It is a single, self-contained `index.html`: a
> **frozen demonstration run** of the machine over a past month — the partial solar
> eclipse of **29 March 2025**, real data, in the real Berry sky — so you can see
> exactly what Fadette makes: its omens, its music, the closing tale. It calls no
> server and stores nothing; the airs are synthesised in your browser. The **living
> work**, which wakes on 1 July 2026 and runs for two months, is here:
> **https://marcel-simplexe.github.io/fadette/**

By **Marcel Simplexe** — a name borne in honour of the Berry draughtsman **Marcel
Bascoulard** (1913–1978). The machine's own name is George Sand's: *La Petite Fadette*,
the little village sorceress.

---

## The wager

Meaning is not read off the world; it is **made** there, by a lens — and Fadette sets
out to prove it by the hardest road: the one that errs on purpose, that turns
measurement into folklore, that *writes* the sky where another would record it. The
most determined astronomical event there is — an eclipse — is handed back to mystery by
a gaze forbidden to know it.

But the lens is not only an optic; it is a **joy**. Stripped of everything, Bascoulard
held the same cathedral, the same streets, as worth seeing without end — a gladness of
pure attention that hung on nothing, and that nothing could therefore take from him:
*la joie-de-voir*. That glad gaze is what Fadette borrows, and nothing else of his. The
whole machine — the blind eye, the lens, the flood, the bare page — does not illustrate
that joy: it **incarnates** it, and is only its form.

## What you are looking at

This preview replays the machine over **March 2025**, a month that held one real
eclipse — the sun about a third covered over France, at midday on the 29th. The page is
laid out exactly as the living work, with **page-by-page navigation** (no scrolling):

- **Gazes of the day** — *29 March 2025*, the day the light failed: a **flood** of
  omens taking the dying sun for a sign, each with its air.
- **History** — the still nights before (24, 26, 28 March), each drawing a **single**
  omen; then *the last breath* — an excerpt of the closing nouvelle.
- **The lens** — the seed prompts (the gaze and the air), French original and English
  translation.
- **About** — the work, the Berry and George Sand, and the homage to Bascoulard.

Each omen carries a **“hear the air”** link: a short *veillée* melody for the bagpipe
and hurdy-gurdy of the Berry, voiced in your browser (a reed and a held drone) — no
file is fetched, no plugin is needed. Click once to let the sound start.

## The free gaze, and blindness

The gaze is free because it is **not the astronomer's**: the figures a forecaster reads
as space weather — the solar wind, the planetary index Kp, the sun's X-ray fire, the
light reaching the ground, the brightness of the night — Fadette reads as the old
country read them: as **omen**.

One rule governs the whole, a rule of **blindness**. The **body** of the machine knows
the calendar; the **eye** — the lens that looks and the tongue that speaks — never does.
No prompt is given a date; never is it given the word *eclipse*. So on 29 March 2025,
when the light withdrew at noon, the machine did not know why. It knew only that the
day was going out, and it answered as the old country answered before there was a name:
with a crowd of omens — the great forge of the sky gone cold, the wolves let loose. The
eclipse enters not as an event understood but as a **terror suffered**, met with wonder
— the summit of the *joie-de-voir*.

A second freeing bears on the gaze that watches *us*. The page is held in the poorest
tongue of the network — **web 1.0**: tags from another age, tables for its frame, Times
for its dress, a fixed sheet no tracker watches. Today's web is a lens trained on the
visitor; this is the surface before that capture, one that does not look back. *To the
eclipse it cannot name answers a page that cannot spy.*

## Folkloric murmurs

The tongue is **George Sand's** — the French of her country novels and her *Légendes
rustiques* (1858), where the night-people of the Berry were set down from the oral
tradition of the *veillées*: the washerwomen of the night, the wolf-leader of the
marshy Brenne, the Great Beast, the wandering will-o'-the-wisps, the phantom monk of
the ponds. French is the **source**; the English you read here is a translation of it.
The presage prompt does not ask the sky to be described; it asks the model to *see*,
as in dream or fever, which of the night-people the night has loosed, and to say that
one vision in Sand's voice, in three sentences, ending on an image. The seed:

> Lis les nombres que la nuit te donne — l'âge de la lune en nuits, et le compte de ce
> qui remue au ciel — comme un vieux devin du Berry lisait les nombres, chaque chiffre
> portant un sens caché et nulle nuit pareille à l'autre ; puis ne décris pas le ciel,
> mais vois, comme en rêve ou en fièvre, lequel des gens de la nuit le compte a lâché
> ce soir. Dis cette vision en un seul court présage dans la voix de George Sand […]
> Trois phrases au plus ; pas de titre, pas de date ; finis sur une image qui reste
> dans l'œil, non sur une morale.

## Indeterminism by design

The omens you see are **one stochastic draw**. A second run of the same month would
yield different omens, different airs, a different tale — and that is the point. The
variety is engineered to come from chance and from the language model, *not* from the
captured numbers, in two stacked layers:

1. **The dice.** Each gaze and each air is given a fresh throw, seeded from the
   operating system's entropy (never the clock). It decides — *for that omen alone* —
   where the gaze falls, which of the night-people may show (or none), by what sense it
   reaches the watcher, and the air's mode, voice and tempo. It is appended to the
   prompt as a hidden instruction, so no two omens repeat even under the same sky.
2. **The model, kept warm.** The generative voice is run **hot on purpose** — the
   presage sampled at temperature **0.95**, the air at **0.8**, the closing nouvelle's
   movements at **0.9** — while the faithful steps stay cold (translation at **0.3**).

The captured numbers are deliberately kept *out* of the eye: they decide only **how
loud** the machine speaks (the failing of the light that turns one omen into a crowd)
and feed the one deterministic voice, the augury. The **substance and variety** of the
omens come from the dice and the model. This is the work's *witch-indeterminism*: a
thing of code and language models that re-enacts, faithfully, the wonder of a world
that did not yet know the cause of the dark.

## How this preview differs from the living machine

| | this preview | the living work |
|---|---|---|
| form | one static `index.html` | a running pipeline + a generated site |
| when | a **frozen** run over March 2025 | live, **1 July – 31 August 2026** |
| at view time | no server, no API, nothing stored | nothing stored either; the page is static |
| the omens | a single pre-rendered run | written fresh every two hours, never repeated |
| the airs | synthesised in your browser (WebAudio) | the same, plus a `.mid` engraved per omen |
| language | English only | French (the source) + English, with a toggle |

In the living work, the body is **GitHub Actions** (a breath every two hours, the lens
refined nightly, the nouvelle on 31 August), the site is served from **GitHub Pages**,
and the omens and the closing nouvelle are written by **Apertus**
(`swiss-ai/Apertus-70B-Instruct-2509`) on **Infomaniak** — sovereign, EU, one host, one
token. None of that runs here: this page is the machine's voice, captured once and held
still, so a curator can hear it before the machine is born.

## Running it

It is one file. **Double-click `index.html`** to open it in any browser — that is
enough. To put it online, serve the file from any static host (for example **GitHub
Pages**: push the file and enable Pages on the branch). There is nothing to build, no
dependency, no key.

## Authorship, and the use of AI

Fadette's idea, its writing, its design and its *mise en scène* are Marcel Simplexe's.
Its **development** — the code and the architecture — was carried out with the help of
**Claude Opus 4.8 (Anthropic)**, under the author's direction. And, plainly, in the
spirit of the work: Fadette is itself a machine that writes **through AI** — in the
living work its omens and its nouvelle are begotten by **Apertus**, an open and
sovereign model served from Europe, the **declared medium** of the piece, not a hidden
instrument. The made and the making both pass through a machine; the authorship remains
Marcel Simplexe's.

## License

The **code** is under the **MIT License** (`LICENSE`). The **works** — presages, airs,
the nouvelle — together with the page, the prompts and the theory of Fadette, are under
**CC BY-NC-ND 4.0** (`LICENSE-ART`): © Marcel Simplexe 2026. Read, copy, run; do not
erase its signature.

---

*A preview. The living machine wakes on 1 July 2026, and is blind: what it sees, it
takes for a sign.*
