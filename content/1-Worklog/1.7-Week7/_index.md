---
title: "Week 7 Worklog"
date: 2026-10-26
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Week 7 Objectives:

* Finish the Chrome extension that captures a Google Meet tab and shows live notes.
* Deploy the speech runtime and staging controls on AWS.
* Test with real meetings and keep spending inside the agreed budget.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Build meeting capture and the live notes panel in the extension. <br> - Redesign the meeting notebook UI and refresh capture readiness. | 26/10/2026 | 26/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Complete the protected runtime and SAM staging controls. <br> - Add scoped CI coverage and local infrastructure checks. <br> - Fix startup readiness, recover interrupted ASR boots and reconcile data erasure. | 27/10/2026 | 27/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 4 | - Deploy the speech runtime to AWS staging. <br> - Recover stopped runtimes automatically. | 28/10/2026 | 28/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 5 | - Live QA with real Google Meet meetings. <br> - Fix capture and microphone setup; harden the live capture and notes runtime. <br> - Merge the connected meeting baseline and write the onboarding guide. | 29/10/2026 | 29/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 6 | - Add a timed AWS testing dashboard. <br> - Record the budget policy: $100 ceiling, split $80 work / $20 cleanup. <br> - Fix continuous speech context and notes snapshots; draw the TINA system diagram. | 30/10/2026 | 30/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |

### Week 7 Achievements:

* Ran the first end-to-end flow: Chrome extension → AWS speech runtime → Bedrock notes → live panel.
* Learned to control cost on a shared account with timed runs, budget holds and cleanup reserves.
* Found and fixed capture and microphone issues that only appeared in real meetings.
* Documented the system in a draw.io architecture diagram and an onboarding guide.
* Attended the AWS First Cloud AI Journey Community Day (31/10).
