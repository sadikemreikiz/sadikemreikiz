# Sadik Emre Ikiz

Software developer in Berlin, focused on applied AI. I build machine-learning and LLM systems in Python and TypeScript, and full-stack products with C#/.NET and React. M.Sc. in Software Engineering; open to Applied AI and ML Engineer roles.

## Selected work

**[Finding forged receipts: my Master's thesis, rebuilt](https://github.com/sadikemreikiz/financial-document-fraud-detection)** · [live demo](https://sadikemreikiz.github.io/financial-document-fraud-detection/) — Pixel forensics in PyTorch, copy-move detection and accounting checks, fused into one calibrated score, with an LLM agent that drafts the case for a human reviewer. Tested once on 218 held-out receipts: at a 10 % review budget it sent 24 to review, all of them forged, and missed 11 of the 35 forgeries (F1 0.81). I rebuilt the thesis from scratch after my own audit found that test data had leaked into its training; the new evaluation protocol was fixed before any model was trained. Weak spot, measured and reported: receipts saved again as JPEG.

**Auvesta Edelmetalle AG** — Developed an internal Outlook email archiving add-in using React, TypeScript, Office.js, and ASP.NET Core. Integrated Microsoft Graph and SQL Server, wrote automated tests, and prepared deployment configurations that were tested locally.

**[Trysa direct booking](https://github.com/sadikemreikiz/trysa-direct-booking)** · [live site](https://trysacamping.com) — The booking website and staff panel my family's guesthouse runs on, built and operated by me: Next.js, TypeScript and PostgreSQL, two-way Airbnb calendar sync, and an AI concierge on Claude Haiku 5.5 that answers guests in three languages from the site's content and checks availability through a tool. I built an eval for it (31 scripted conversations, code checks plus an LLM judge); the two fixes it pointed to took the pass rate from 71% to 94% with a quarter fewer model calls (one run each; limits stated in the repo). 186 tests against a real Postgres, live since September 2026.

[LinkedIn](https://www.linkedin.com/in/sadikemreikiz/)
