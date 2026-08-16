<!-- ══════════════════════ HEADER ══════════════════════ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:02569B,100:13B9FD&height=200&section=header&text=Soumoparno%20Roy&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Flutter%20Developer%20%7C%20Offline-first%20mobile%20products&descAlignY=55&descSize=16" alt="header"/>

<a href="https://github.com/SoumoparnoRoy">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=13B9FD&center=true&vCenter=true&width=600&lines=Flutter+%C2%B7+Dart+%C2%B7+Riverpod+%C2%B7+SQLite;Apps+that+work+with+no+signal;Domain+logic+that+never+imports+Flutter;80+tests+and+no+device+required" alt="Flutter · Dart · Riverpod · SQLite" />
</a>

<br/>

<a href="https://www.linkedin.com/in/soumoparno-roy">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://kurskart.vercel.app">
  <img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live demo"/>
</a>
<img src="https://komarev.com/ghpvc/?username=SoumoparnoRoy&style=for-the-badge&color=13B9FD&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

<br/>

<!-- ══════════════════════ ABOUT ══════════════════════ -->

## 🧭 &nbsp;About

I build Flutter apps that hold up outside the demo — offline, on a bad network, on a mid-range Android phone.

> **Start from the user's problem**, not the widget tree.
>
> **Keep Flutter out of the domain layer**, so the interesting parts stay testable without a device.
>
> **Design for no signal, low memory, interrupted taps** — real conditions, not the happy path.
>
> **Maintainable over clever.** I'll be the one reading it in six months.

<br/>

<!-- ══════════════════════ STACK ══════════════════════ -->

## 🛠 &nbsp;Tech Stack

<div align="center">

**Mobile**

<img src="https://skillicons.dev/icons?i=flutter,dart&theme=dark" alt="Flutter, Dart"/>

**Backend & Data**

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,sqlite&theme=dark" alt="Node.js, Express, MongoDB, SQLite"/>

**Tooling**

<img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio,postman,vercel&theme=dark" alt="Git, GitHub, VS Code, Android Studio, Postman, Vercel"/>

</div>

<br/>

<!-- ══════════════════════ PROJECTS ══════════════════════ -->

## 🚀 &nbsp;Featured Projects

<details open>
<summary><b>📚 Attend-It</b> — <i>Know exactly how many classes you can afford to miss</i></summary>

<br/>

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-4B32C3)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Offline First](https://img.shields.io/badge/Offline--first-3DDC84)
![Tests](https://img.shields.io/badge/tests-80-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

An offline-first attendance tracker that answers one question before you skip a lecture.

| | |
|---|---|
| **Rules, not rows** | A weekly class is stored as a rule and expanded into occurrences on demand. Editing a rule reshapes every future week instantly, and the database stays tiny. |
| **Time that doesn't drift** | Dates as `yyyymmdd` integers, times as minutes since midnight — immune to timezones and DST. |
| **Marks that survive edits** | Attendance is keyed by `(subject, date, start time)`, not slot id, so a mark outlives the rule that produced it. |
| **Testable by design** | The domain layer never imports Flutter. 80 tests cover the schedule engine, stats formulas, notification gating, and palette contrast ratios — no device needed. |

```
Can skip     ⌊p / t⌋ − h
Must attend  ⌈(t·h − p) / (1 − t)⌉
```

No accounts. No server. No network calls. Works on a train with no signal.

**[→ View repository](https://github.com/SoumoparnoRoy/Attend-It)**

</details>

<details>
<summary><b>🛒 KursKart</b> — <i>Multi-store e-commerce, full stack</i></summary>

<br/>

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white)
![Vercel](https://img.shields.io/badge/Deployed-Vercel-000000?logo=vercel)

A Flutter client and a Node/Express/MongoDB API in one monorepo.

| | |
|---|---|
| **Can't oversell** | Checkout reserves stock with a conditional update per product. If any line fails, reserved stock is released and the cart is left untouched. |
| **Immutable orders** | Order lines copy name, price and image at purchase time, so editing a product later never rewrites history. |
| **Runs two ways** | The same Express app runs as a normal server and as a serverless function, with a cached Mongo connection shared across warm invocations. |
| **Security defaults** | bcrypt hashing, JWT in `flutter_secure_storage`, API URL as a `--dart-define`, cleartext HTTP in debug builds only. |

**[→ View repository](https://github.com/SoumoparnoRoy/KursKart)** &nbsp;·&nbsp; **[→ Live API](https://kurskart.vercel.app)**

</details>

<br/>

<!-- ══════════════════════ SNAKE ══════════════════════ -->

## 🐍 &nbsp;Contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SoumoparnoRoy/SoumoparnoRoy/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SoumoparnoRoy/SoumoparnoRoy/output/snake.svg" />
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/SoumoparnoRoy/SoumoparnoRoy/output/snake.svg" />
</picture>

</div>

<br/>

<!-- ══════════════════════ STATS ══════════════════════ -->

## 📊 &nbsp;GitHub Stats

<!--
  Cards are served from a self-hosted github-stats-extended instance
  (release branch, own PAT). The public instances are rate-limited and
  return broken images.
-->

<div align="center">

<img width="49%" src="https://github-readme-stats-kurse.vercel.app/api?username=SoumoparnoRoy&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&count_private=true&hide=stars,prs,issues,contribs&hide_rank=true" alt="GitHub stats"/>
<img width="40%" src="https://github-readme-stats-kurse.vercel.app/api/top-langs/?username=SoumoparnoRoy&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=6&size_weight=0.5&count_weight=0.5" alt="Top languages"/>

<br/>

<img width="60%" src="https://streak-stats.demolab.com?user=SoumoparnoRoy&theme=tokyonight&hide_border=true&background=0D1117" alt="Contribution streak"/>

</div>

<br/>

<!-- ══════════════════════ NOW ══════════════════════ -->

## 🌱 &nbsp;Currently

| | |
|---|---|
| **Building** | Polished Flutter products that survive real device constraints |
| **Learning** | Architecture patterns for apps that keep growing |
| **Improving** | Repositories documented well enough to read as case studies |
| **Open to** | Flutter roles, collaborations, and interesting mobile problems |

<br/>

<!-- ══════════════════════ FOOTER ══════════════════════ -->

<div align="center">

### Let's build something

<a href="https://www.linkedin.com/in/soumoparno-roy">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<br/><br/>

<i>"Design for real device constraints and imperfect conditions."</i>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:13B9FD,100:02569B&height=120&section=footer" alt="footer"/>

</div>
