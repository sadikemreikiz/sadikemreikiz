# Sadik Emre Ikiz

I’m a software engineer based in Berlin with an M.Sc. in Software Engineering, focused on applied AI. My main project is a rebuilt version of my master’s thesis system for financial document fraud detection, combining computer vision, OCR, accounting checks and LLM-assisted review in Python and PyTorch, with reproducible evaluation.

My backend and full-stack experience includes Python/Django development at Softalya, a React and ASP.NET Core Outlook add-in at Auvesta, and Trysa, a live booking platform I built and operate with an AI concierge. I’m looking for AI engineering opportunities in Germany where I can bring this software development background to practical AI applications.

## Selected work

### Financial Document Fraud Detection
**My master’s thesis project, rebuilt and evaluated**

A research prototype that detects signs of receipt forgery, highlights suspicious regions and prepares evidence for human review.

- Combines pixel-level forensics, copy-move detection and OCR-based accounting checks into a calibrated risk score.
- Uses an LLM to extract receipt fields and an agent to draft case files from the system’s evidence.
- Rebuilt from scratch after my audit uncovered data leakage in the original implementation, with an evaluation protocol fixed before training.
- Achieved **0.90 average precision and 0.81 F1** in a single evaluation on 218 held-out receipts, including 35 forgeries. Documents failure cases, including reduced performance on receipts re-saved as JPEG.

**Stack:** Python · PyTorch · scikit-learn · RapidOCR · Claude API

[Source code](https://github.com/sadikemreikiz/financial-document-fraud-detection) · [Recorded results demo](https://sadikemreikiz.github.io/financial-document-fraud-detection/)

### Trysa Direct Booking
**A live product for my family’s guesthouse**

A multilingual booking website and staff panel that I designed, built and operate.

- Brings direct booking requests and Airbnb availability into one workflow, with two-way calendar synchronisation.
- Includes an AI concierge that answers from the site’s content, checks availability through tools and hands booking confirmation to the family.
- Handles booking conflicts, notification retries and operational alerts, with 186 unit and integration tests plus end-to-end tests.
- Evaluates the concierge through 31 scripted conversations in Turkish, English and German.

**Stack:** Next.js · React · TypeScript · PostgreSQL · Claude API · Vercel

[Source code](https://github.com/sadikemreikiz/trysa-direct-booking) · [Live website](https://trysacamping.com/)

## Professional experience

### Auvesta Edelmetalle AG — Software Developer
*May–September 2026*

Developed an internal Outlook email archiving add-in using React, TypeScript, Office.js and ASP.NET Core. Integrated Microsoft Graph and SQL Server for email retrieval, document filing and audit history. Wrote automated frontend and backend tests and prepared locally tested deployment configurations.

### Softalya Software Inc. — Development Internships
*2023 · 2024*

Developed backend features and REST APIs with Python, Django and Django REST Framework, working with PostgreSQL and SQLite. In an earlier frontend internship, built responsive interfaces with HTML, CSS, Bootstrap and JavaScript.

## Contact

Based in Berlin · Open to AI engineering, backend and full-stack development opportunities

[LinkedIn](https://www.linkedin.com/in/sadikemreikiz/) · [Email](mailto:sadikemreikiz90@gmail.com)
