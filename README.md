## Soumoparno Roy

Flutter developer. I build mobile products that hold up outside the demo — offline, on a bad network, on a mid-range Android phone.

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-4B32C3)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)

---

### Projects

**[Attend-It](https://github.com/SoumoparnoRoy/Attend-It)** — Offline-first attendance tracker for university students

Answers one question: *how many classes can I still afford to miss?* A weekly class is stored as a rule, not a row per week, so a schedule engine expands rules into occurrences on demand — editing a rule reshapes every future week instantly and the database stays small. Dates are `yyyymmdd` integers and times are minutes since midnight, so nothing drifts with timezones or DST. Everything is local: no accounts, no server, no network calls.

The domain layer never imports Flutter, so 80 unit tests cover the schedule engine, the stats formulas, notification gating, and the light palette's contrast ratios — no device required.

`Flutter` · `Riverpod` · `SQLite` · `MIT`

---

**[KursKart](https://github.com/SoumoparnoRoy/KursKart)** — Multi-store e-commerce, full stack

Flutter client and a Node/Express/MongoDB API in one monorepo, with JWT auth in `flutter_secure_storage` and bcrypt-hashed passwords. Checkout reserves stock with a conditional update per product, so simultaneous orders can't oversell; if any line fails, the reserved stock is released and the cart is left untouched. Order lines copy name, price, and image at purchase time, so editing a product later never rewrites past orders.

The backend is split so the same Express app runs as a normal server and as a serverless function, with a cached Mongo connection shared across warm invocations. The API base URL is a `--dart-define`, not a hardcoded constant, and cleartext HTTP is permitted in debug builds only.

`Flutter` · `Riverpod` · `Node.js` · `Express` · `MongoDB` · `JWT` · [live](https://kurskart.vercel.app)

---

### How I work

Start from the user's problem, not the widget tree. Keep business logic out of the UI and Flutter out of the domain layer, so the interesting parts stay testable. Design for real constraints — no signal, low memory, interrupted operations, a user who taps the same button twice. Prefer maintainable code over clever code.

---

### Currently

Deepening full-stack mobile work — architecture that survives a growing app, and repositories documented well enough to read as case studies.

---

[LinkedIn](https://www.linkedin.com/in/soumoparno-roy) · [GitHub](https://github.com/SoumoparnoRoy)
