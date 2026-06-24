# Idder Ait Elmouden — Systems & Full-Stack Engineer

Agadir, Morocco · [idderaitelmouden@gmail.com](mailto:idderaitelmouden@gmail.com)

---

## Engineering Philosophy

Systems decompose into interfaces and invariants. Every non-trivial bug is a violated invariant that wasn't expressed in the code. Every performance problem is an interface that transferred cost invisibly. I design from the boundary inward.

---

## What I've Solved

### Problem: An architecture firm's website looked like every other architecture firm's website.

**Root cause:** Template-driven design cannot create trust because trust is specific and templates are general. The firm's portfolio was real; the wrapper around it wasn't.

**Solution:** Custom design system built to communicate taste before the visitor reads a word. Case study format (problem → process → result) instead of portfolio grid. Single-action per page, conversion-optimised contact flow. Typography chosen to signal precision.

**Outcome:** Qualified inquiry rate up in the first month. [Arpio Architects →](https://github.com/IDDER29/arpio-architects-case-study)

---

### Problem: Campus events were fragmented across WhatsApp, flyers, and rumour.

**Root cause:** No unified discovery layer. No trusted source of truth. No incentive to engage before or after events.

**Solution:** Cross-platform mobile app with unified event feed, ticket purchase flow, and a reward-point system that creates habit. Designed around the discovery-to-attendance-to-community arc.

**Technical decisions:** React Native for cross-platform reach with native feel. TypeScript throughout for type safety across a codebase multiple contributors would touch. State management scoped per feature to avoid the "global state dump" failure mode.

**Outcome:** Production deployment, active user base. [Social Compass →](https://github.com/IDDER29/social-compass-mobile)

---

### Problem: I didn't fully understand what happens below the abstraction.

**Decision:** Rebuild it. Every piece.

| Component | What I built | What it taught me |
|-----------|-------------|-------------------|
| `ft_printf` | Variadic args, format parsing | The C ABI, va_list mechanics, edge cases in integer formatting |
| `push_swap` | Sorting under op-count constraint | Algorithm selection trade-offs, O(n log n) vs practical constants |
| `get_next_line` | Stateful fd reading | Static storage, buffer management, fd multiplexing |
| `minishell` | POSIX-compatible shell | fork/exec, signals, pipes, redirections, the actual meaning of "process" |
| `libft` | Standard library | Memory, strings, lists — nothing is magic |

[1337 Systems Suite →](https://github.com/IDDER29?tab=repositories&language=c)

---

## Stack

```
Frontend:   React / Next.js / TypeScript / Tailwind / Angular / Redux
Backend:    Node.js / NestJS / Python / REST / PostgreSQL
Commerce:   Shopify / Liquid / Storefront API
Mobile:     React Native / TypeScript
Systems:    C / Makefile / POSIX / Linux
```

---

## Trade-offs I Understand

- **React vs Next.js** — when SSR pays for itself and when it's premature
- **REST vs GraphQL** — what fetch patterns actually suit the client
- **Custom component vs library** — when control is worth the maintenance cost
- **C malloc vs arena** — when allocation patterns justify a custom allocator

---

## Open For

Freelance contracts. Full-time engineering roles. Problems worth solving.

[Portfolio →](https://portfolio-nu-six-19.vercel.app/) · [LinkedIn →](https://www.linkedin.com/in/idderaitelmouden/) · [All repos →](https://github.com/IDDER29)
