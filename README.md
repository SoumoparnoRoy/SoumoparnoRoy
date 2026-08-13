<!-- ══════════════════════ HEADER ══════════════════════ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:02569B,100:13B9FD&height=200&section=header&text=Soumoparno%20Roy&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Flutter%20Developer%20%7C%20Offline-first%20mobile%20products&descAlignY=55&descSize=16"/>

<a href="https://github.com/SoumoparnoRoy">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=13B9FD&center=true&vCenter=true&width=600&lines=Flutter+%C2%B7+Dart+%C2%B7+Riverpod+%C2%B7+SQLite;Apps+that+work+with+no+signal;Domain+logic+that+never+imports+Flutter;80+tests+and+no+device+required" alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/soumoparno-roy">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/SoumoparnoRoy">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://kurskart.vercel.app">
  <img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<img src="https://komarev.com/ghpvc/?username=SoumoparnoRoy&style=for-the-badge&color=13B9FD&label=PROFILE+VIEWS"/>

</div>

<br/>

<!-- ══════════════════════ ABOUT ══════════════════════ -->

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> &nbsp;About

```dart
class Soumoparno extends Developer {
  @override
  final String focus = 'Offline-first Flutter products';

  @override
  final List<String> principles = [
    'Start from the user problem, not the widget tree',
    'Keep Flutter out of the domain layer',
    'Design for no signal, low memory, interrupted taps',
    'Maintainable over clever',
  ];

  @override
  Future<Product> build(Idea idea) async =>
      idea.ship(whenNetworkFails: true);
}
```

<br/>

<!-- ══════════════════════ STACK ══════════════════════ -->

## <img src="https://media.giphy.com/media/WFZvB7VIXBgiz3oDXE/giphy.gif" width="28"> &nbsp;Tech Stack

<div align="center">

**Mobile**

<img src="https://skillicons.dev/icons?i=flutter,dart&theme=dark" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,sqlite&theme=dark" />

**Tooling**

<img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio,postman,vercel&theme=dark" />

</div>

<br/>

<!-- ══════════════════════ PROJECTS ══════════════════════ -->

## <img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28"> &nbsp;Featured Projects

<div align="center">

<a href="https://github.com/SoumoparnoRoy/Attend-It">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=SoumoparnoRoy&repo=Attend-It&theme=tokyonight&hide_border=true&bg_color=0D1117"/>
</a>
<a href="https://github.com/SoumoparnoRoy/KursKart">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=SoumoparnoRoy&repo=KursKart&theme=tokyonight&hide_border=true&bg_color=0D1117"/>
</a>

</div>

<br/>

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

<!-- ══════════════════════ STATS ══════════════════════ -->

## <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="28"> &nbsp;GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=SoumoparnoRoy&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&count_private=true"/>
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SoumoparnoRoy&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=6"/>

<br/>

<img width="60%" src="https://streak-stats.demolab.com?user=SoumoparnoRoy&theme=tokyonight&hide_border=true&background=0D1117"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=SoumoparnoRoy&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8"/>

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=SoumoparnoRoy&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=13B9FD&line=13B9FD&point=ffffff&area=true"/>

</div>

<br/>

<!-- ══════════════════════ SNAKE ══════════════════════ -->

<div align="center">

<img src="https://raw.githubusercontent.com/SoumoparnoRoy/SoumoparnoRoy/output/snake.svg" alt="Snake eating my contributions"/>

</div>

<br/>

<!-- ══════════════════════ NOW ══════════════════════ -->

## <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="28"> &nbsp;Currently

```yaml
building:   polished Flutter products that survive real device constraints
learning:   architecture patterns for apps that keep growing
improving:  repositories documented well enough to read as case studies
open_to:    Flutter roles, collaborations, and interesting mobile problems
```

<br/>

<!-- ══════════════════════ FOOTER ══════════════════════ -->

<div align="center">

### Let's build something

<a href="https://www.linkedin.com/in/soumoparno-roy">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br/><br/>

<i>"Design for real device constraints and imperfect conditions."</i>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:13B9FD,100:02569B&height=120&section=footer"/>

</div>
