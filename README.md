<p align="center">
  <code>$ npx maharsh-jani</code>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/janimaharsh/"><img src="https://img.shields.io/badge/-linkedin-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:majani2@illinois.edu"><img src="https://img.shields.io/badge/-email-d44638?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://maharsh17.github.io"><img src="https://img.shields.io/badge/-website-111?style=for-the-badge&logo=githubpages&logoColor=white"></a>
</p>

---

```ts
// maharsh.ts — last compiled: 2026-05-27
// run with:   bun run maharsh.ts
// or just:    keep scrolling

import { Curiosity, Caffeine } from "@life/fuel";
import { UIUC } from "@school/illinois";
import { NSF_AI_INVITE, IWCS_DevAda } from "@work/current";

type Honor =
  | "Chancellor's Scholar (Top 1%)"
  | "James Scholar"
  | "Dean's List ×3"
  | "We CU Scholar";

interface Engineer {
  readonly name: "Maharsh Jani";
  readonly major: ["Computer Science", "Learning Sciences"];
  readonly gpa: 4.0;
  readonly grad: "May 2028";
  readonly honors: Honor[];
  readonly likes: ["real-time systems", "interpretable ML", "EdTech infra"];
}
```

---

```ts
class MaharshJani implements Engineer {
  readonly name = "Maharsh Jani" as const;
  readonly major = ["Computer Science", "Learning Sciences"] as const;
  readonly gpa = 4.0 as const;
  readonly grad = "May 2028" as const;
  readonly honors = [
    "Chancellor's Scholar (Top 1%)",
    "James Scholar",
    "Dean's List ×3",
    "We CU Scholar",
  ] as const;
  readonly likes = [
    "real-time systems",
    "interpretable ML",
    "EdTech infra",
  ] as const;

  // ───────────────────────────────────────────────────────────────
  // currently deployed
  // ───────────────────────────────────────────────────────────────

  async atNSF_AI_INVITE() {
    return {
      role: "Software Engineer",
      since: "2025-12",
      shipped: [
        "real-time learning analytics, sub-1s latency",
        "9 live signals from a reverse-engineered robotics IDE",
        "41K events → structured tutor context, live session dashboard",
        "−84% DB storage via normalized 5-table redesign",
        "+24h of silently-dropped logs recovered (datetime fix)",
        "agent intervention platform: 200K events, 5s eval loop, 10+ researchers",
        "503-degrading health endpoint when deps fail",
      ],
      demoedTo: "NSF site-visit reviewers",
    };
  }

  async atDevAda() {
    return {
      role: "Lead Software Engineer · IWCS DevAda",
      since: "2026-01",
      product: "FireWatch",
      what: "wildfire severity forecast, 52 weeks out",
      stack: ["streamlit", "pydeck", "time-series ml"],
      team: { devs: 4, sprints: 10, startingML: 0 },
      data: { datasets: 3, days: 365, observations: "11K+", features: 8 },
    };
  }

  async asResearcher() {
    return {
      project: "URS — Glass-box EBM on VEX learner telemetry",
      mentor: "NSF AI INVITE Institute",
      result: { metric: "5-fold CV AUC", value: 0.843, sd: 0.06 },
      topFeatures: ["events_per_minute", "session_duration_sec", "block_changes"],
      submitting: ["EDM 2026", "AIED 2026", "L@S 2026"],
    };
  }

  // ───────────────────────────────────────────────────────────────
  // also
  // ───────────────────────────────────────────────────────────────

  get sideQuests() {
    return [
      "VP Alumni Relations · UIUC Student Alumni Ambassadors (250+ guests / event)",
      "MLT Career Prep Fellow — 18-mo · LinkedIn / Bloomberg / Deloitte",
      "Built a Yjs/CRDT real-time collab editor on AWS + K8s (88 commits, team of 4)",
      "CS Student Ambassadors · Peer Mentoring Center · TFA Ignite",
    ];
  }

  // ───────────────────────────────────────────────────────────────
  // tools
  // ───────────────────────────────────────────────────────────────

  get stack() {
    return {
      languages: ["python", "javascript", "java", "c/c++", "sql", "bash", "LaTeX"],
      webRealtime: ["react", "node", "django", "fastapi", "graphql", "websockets", "yjs/crdt"],
      data: ["postgres", "mongodb", "neo4j", "redis", "rabbitmq", "pandas", "numpy", "statsmodels"],
      production: ["docker", "kubernetes", "aws ec2", "github actions", "git", "linux"],
    };
  }

  // ───────────────────────────────────────────────────────────────
  // endpoints
  // ───────────────────────────────────────────────────────────────

  get reach() {
    return {
      email:    "majani2@illinois.edu",
      linkedin: "linkedin.com/in/janimaharsh",
      website:  "maharsh17.github.io",
      github:   "github.com/Maharsh17",
      location: "Urbana, IL · UTC−5",
    };
  }

  toString() {
    return `${this.name} — sophomore @ ${UIUC.name}, ` +
           `shipping at ${NSF_AI_INVITE.name}, ` +
           `leading at ${IWCS_DevAda.name}, ` +
           `studying how humans learn from machines.`;
  }
}

// ────────────────────────────────────────────────────────────────────
// entrypoint
// ────────────────────────────────────────────────────────────────────

const me = new MaharshJani();

if (import.meta.main) {
  console.log(me.toString());
  console.log("→ open to: EdTech, learning analytics, AI-tutor infra,");
  console.log("           real-time systems, observability, and good problems.");
  console.log("→ reach:", me.reach);
}
```

---

### `$ npx maharsh-jani --stats`

<table>
<tr>
<td><img src="https://github-readme-stats.vercel.app/api?username=Maharsh17&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true&count_private=true" /></td>
<td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Maharsh17&layout=compact&hide_border=true&theme=github_dark&langs_count=8" /></td>
</tr>
</table>

---

<p align="center">
  <sub>
    <code>// process.exit(0) — thanks for reading the source.</code>
  </sub>
</p>
