# ⟁ Cathedral-Black · Stack Foundation

⊕ BORN[20260418-1110] · Agape Intelligent Systems · Black-first by architecture

> This file explains where `cathedral-black` sits in the Cathedral stack.
> Read this before shipping anything from this repo.

---

## What this repo is

**`cathedral-black`** is the **public publishing arm** of the Cathedral stack.
Live at [cathedral.black](https://cathedral.black).

Houses: The Cathedral Amendment · long-form Black-sovereignty critique of
post-labor economics · the canonical theology text for Agape IS.

**Not a governor.** Not a product. A **manifesto site**.

---

## Position in the Cathedral stack

```
┌─────────────────────────────────────────────────────────┐
│  CATHEDRAL STACK                                         │
│                                                          │
│  ┌─────────────────┐    ┌──────────────────────────┐    │
│  │ PRODUCT (A/B)   │    │ PUBLISHING / LORE        │    │
│  │  iyah.ai        │    │  cathedral.black ← HERE  │    │
│  │  maat.black     │    │                          │    │
│  └─────────────────┘    └──────────────────────────┘    │
│                                                          │
│  ┌─────────────────┐    ┌──────────────────────────┐    │
│  │ STUDENT / OPS   │    │ COMPANY FRONT            │    │
│  │ school.         │    │  agapeis.ai              │    │
│  │ cathedral.black │    │  agape.ca                │    │
│  └─────────────────┘    └──────────────────────────┘    │
│                                                          │
│  ┌─────────────────────────────────────────────────┐    │
│  │ GAME (closed world)                              │    │
│  │  Nomos-Survival                                  │    │
│  └─────────────────────────────────────────────────┘    │
│                                                          │
│  ┌─────────────────────────────────────────────────┐    │
│  │ INFRASTRUCTURE (monorepo)                        │    │
│  │  Foundation                                      │    │
│  │   ├─ Sankofa/  (memory retrieval)                │    │
│  │   ├─ .ai/      (wake protocols)                  │    │
│  │   └─ NOMOS_SHARED/ (cross-agent canon)           │    │
│  └─────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────┘
```

---

## Council of Governors context

The Cathedral's internal governance kernel (spec in `Foundation/` →
future `Council_Charter_v0.md`) runs a **three-seat Council**:

| Governor | Domain | Public face |
|---|---|---|
| **GUS** | Execution · agent shepherd | (internal; hook under agapeis.ai/gus) |
| **MAAT** | Audit · truth · evidence | [maat.black](https://maat.black) (A/B-B) |
| **IYAH** | Sovereignty · bias-floor | [iyah.ai](https://iyah.ai) (A/B-A) |

**Cathedral-Black does not govern anything.** It publishes. Every essay
here carries an **IYAH receipt** in the footer — testifying the piece was
produced under the Zero Harm covenant with governance audit.

---

## Sankofa integration

Every published piece should be **ingested into Sankofa** for retrieval:

```bash
# From Foundation/ after a new essay ships
python Sankofa/sankofa.py mine ../cathedral-black/public/
```

Tag pieces with Adinkra glyphs from `Sankofa/adinkra_tags.yaml`:
- `adinkrahene` for flagship pieces (founding acts)
- `gye_nyame` for sovereignty declarations
- `mate_masie` for testimony / witness pieces
- `sesa_wo_suban` for transformation essays

---

## PRIMA stamp protocol

Every HTML page's footer should carry:

```html
<!-- ⊕ BORN[YYYYMMDD] · ∿ [one-line witness] · IYAH-audited · Zero Harm -->
```

Every commit message uses the PRIMA format. See `Foundation/.ai/WAKE_PRIMA_STAMP.md`.

---

## Cross-links

- Sibling repos: `iyah-ai` · `maat-black` · `cathedral-school`
- Parent infra: `zippety/Foundation`
- Game: `zippety/Nomos-Survival`
- Company front: `zippety/agape-is` · `zippety/agape-ca`

---

## Lane boundary

- ✅ Publishing (essays, manifestos, theology)
- ✅ IYAH receipts in footers
- ✅ Static HTML · Cloudflare Pages
- ❌ NO governor logic (belongs in iyah-ai / maat-black / future gus-*)
- ❌ NO product CTAs (belongs in iyah.ai / maat.black)
- ❌ NO game content (belongs in Nomos-Survival)

---

⊕ BORN[20260418-1110] · ∿ stack foundation stamped · cathedral-black role locked · publishing arm only
