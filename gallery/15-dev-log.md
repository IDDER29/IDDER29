# Idder's Dev Log

_Agadir, Morocco · Full-Stack Engineer · 1337 School / 42 Network_

---

## Recent Entries

---

**2025-11-14 — Arpio Architects · v1.0 deployed**

Shipped the Arpio architecture firm platform today. Spent the last two weeks on the contact flow — it went through four iterations before I was satisfied. The problem was cognitive load: visitors were arriving at the contact page already slightly intimidated (architecture is expensive, the clients they want are busy), and the form was making it worse. Final solution: single-field progressive disclosure, human copy, no mandatory fields above the fold.

Conversion rate improvement: measurable. I'll report back in a month.

Stack: React · TypeScript · Vite · Vercel

→ [Repository](https://github.com/IDDER29/arpio-architects-case-study)

---

**2025-08-02 — Social Compass · First production users**

Social Compass hit its first active user day today. The ticket purchase flow worked without a single support ticket, which means the UX is at least coherent. The reward point system is attracting repeat opens — people are checking their balance when they don't need to, which is the exact behavior a gamification system wants.

Debugging a React Native navigation issue that only appears on Android 12 with dark mode. Filed, not fixed yet.

Stack: React Native · TypeScript · Node.js backend

→ [Repository](https://github.com/IDDER29/social-compass-mobile)

---

**2025-04-17 — minishell · Passed peer review**

`minishell` passed its final peer review after 6 weeks. The hardest part was signal handling — specifically, ensuring Ctrl+C in a child process doesn't kill the parent, which sounds obvious until you actually implement it.

The peer who reviewed me caught a pipe leak in a specific edge case (heredoc into a command with a non-zero exit code). He was right. Fixed it.

→ [Repository](https://github.com/IDDER29?tab=repositories&language=c)

---

**2025-01-09 — ft_printf · First submission**

Submitted `ft_printf` today. The variadic argument parsing took three days to fully understand — the C standard is... thorough. The tricky part was `%*d` (width specified as argument, not format string). I got it wrong twice before I got it right.

The evaluator noticed I'd over-allocated in one buffer case. Fixed in v1.1. Better to be told by a peer than by a customer.

→ [Repository](https://github.com/IDDER29?tab=repositories&language=c)

---

## Who Am I

Full-stack engineer based in Agadir, Morocco. I went through the 42 Network curriculum at 1337 School, which means I built things from first principles when most people would have used a library, and I'm better at my job because of it.

I work across the entire stack — C systems code, React/Next.js frontends, Shopify storefronts, React Native mobile, Node.js/NestJS backends. I'm available for freelance and full-time work.

---

[Portfolio](https://portfolio-nu-six-19.vercel.app/) · [idderaitelmouden@gmail.com](mailto:idderaitelmouden@gmail.com) · [LinkedIn](https://www.linkedin.com/in/idderaitelmouden/) · [All 68 repos](https://github.com/IDDER29?tab=repositories)
