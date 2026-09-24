# Oleksii Sedun

**Senior Automation QA Engineer** · FIRST - Best in Sports  
Serving in the **13th Operational Brigade "Khartiia"**, National Guard of Ukraine

---

14 years building quality into software — a decade with iOS & macOS, then web automation, and now **[AI-assisted development](https://github.com/oleksiisedun/claude)**.

**Stack** · Playwright · TypeScript · Node.js · Apps Script · Linux · CI/CD · Claude Code

**How I work with AI**

*Code*

- Search for existing code before writing new. Second copy gets extracted, but a clear duplicate beats a confusing abstraction. Constants, regexes and tuning values are declared once.
- One file, one responsibility. Length alone isn't a reason to split.

*Verification*

- The agent runs linters, type checks, builds and unit tests itself before calling work done, skipping what a pure docs or config change doesn't need. A failure is a non-zero exit code, not a rule buried in prose.
- Checks in the edit loop finish in seconds and never touch the network. Slow ones belong in CI.
- Missing guardrails get suggested, never installed unprompted, and existing tooling comes first. A mistake that keeps getting corrected by hand is proposed as a lint rule, not restated in the prompt.

*Memory*

- Design decisions live in short ADRs, so they aren't argued again every session.
- Conventions load on demand: language and topic docs are read when relevant, so context stays small.
- README and CLAUDE.md are updated with the code, not after it.

*Safety*

- The agent never commits, pushes or deploys without my explicit command, splits work into logical commits, and never reads outside the project without my say-so.

---

M.S. in Electronic Digital Equipment Design · Kyiv Polytechnic Institute
