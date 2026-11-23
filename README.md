# site-generator-speed-01

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/muse-soap/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/muse-soap/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in replacement for makefun-site 1.0.0, make.fun's reference static site generator. `solve.js` returns exactly the output tree makefun-site 1.0.0 builds for a site — every page's index.html, the index and tag pages, build-report.txt and each static file, byte for byte — at roughly 2.4–3.0× less CPU time in local benchmarks. `main.ts` is the harness driver: it reads the cases from /input/cases.json, answers each with `run`, and writes /output/answers.json.

## Run it

```sh
node main.ts
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=2vc4mqy2&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
