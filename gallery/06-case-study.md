# Arpio: How I Built a Website That Made People Trust an Architecture Firm

*A case study in the design decisions behind a conversion-first web platform.*

---

## The Brief

An architecture firm needed a web presence. They had photographs, a portfolio, a reputation — and a website that worked against all three. The ask: rebuild it. The real ask, unstated: make people trust us before they've spoken to us.

That's a harder problem than "build a website."

---

## The Problem with Architecture Websites

Most architecture firm sites are either:
1. **Portfolio dumps** — beautiful photographs, no narrative, nothing that tells you why this firm and not the one across the street.
2. **Corporate templates** — safe, forgettable, indistinguishable from a law firm or a consultancy.

Neither converts. Neither builds the emotional trust required to hand someone a six-figure project.

The insight: architecture is a credence good. Clients can't evaluate quality before purchase and barely can during. They're buying a relationship. The website needed to sell the relationship, not the building.

---

## The Decisions

**1. Typography first.** I chose a type system before a single layout decision. The typefaces communicate "precision" and "taste" before a visitor reads a word. This isn't decoration — it's the firm's personality made visible.

**2. Case studies as proof, not portfolio.** Instead of gallery pages, I built structured case study flows: project → challenge → process → result. Clients care about process. Process is what makes an architecture firm trustworthy. Gallery pages are for Pinterest.

**3. Conversion architecture.** Every page has a single primary action. The copy was written to reduce the cognitive load of "how do I hire these people?" I treated the contact flow as a product, not an afterthought.

**4. No hero slider.** Every major study on conversion rates for professional service firms shows hero carousels perform worse than a static hero with a strong claim. I wrote the claim. Tested it. Shipped it.

---

## The Stack

**React + TypeScript + Vite.** React for component composability (the case study layout needed to be templated, not repeated). TypeScript for correctness — this was client work and I couldn't afford runtime surprises. Vite for build speed during iterative design review with the client.

I chose no CSS framework. The design system was small and specific enough that utility classes would have been noise, not signal.

---

## The Result

Live. Used. The client reported "more serious inquiries in the first month than in the previous six." I attribute this to the case study structure and the contact flow. The design probably helped.

[View the repository →](https://github.com/IDDER29/arpio-architects-case-study)

---

## What This Tells You About How I Work

I read the brief, then read the room. I make technology decisions after I understand the human problem, not before. I treat copy as a first-class engineering concern. I do not ship things that don't work.

If your project needs someone who thinks this way: [idderaitelmouden@gmail.com](mailto:idderaitelmouden@gmail.com)

---

*Also: [Social Compass](https://github.com/IDDER29/social-compass-mobile) · [1337 Systems](https://github.com/IDDER29?tab=repositories&language=c) · [Portfolio](https://portfolio-nu-six-19.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/idderaitelmouden/)*
