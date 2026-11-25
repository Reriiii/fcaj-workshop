---
title: "Week 8 Worklog"
date: 2026-11-02
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
### Week 8 Objectives:

* Move to the team's new self-hosted TINA codebase (meeting bot, transcription, agent).
* Build the voice assistant: wake word detection, question capture and spoken replies.
* Cover the speech flow with tests and merge it into main.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study the new codebase: meeting bot, Redis transcript stream and agent. <br> - Write the tina-speech implementation plan in three phases. | 02/11/2026 | 02/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Phase 1 pilot: detect wake words on local audio. <br> - Pin the KWS runtime and model assets; record phase one and two results. | 03/11/2026 | 03/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 4 | - Add an optional CPU TTS sidecar with a female voice that pronounces "Tina" correctly. <br> - Report speech playback outcomes from the bot and track correlated playback in meetings. | 04/11/2026 | 04/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 5 | - Coordinate authorized room turns, pause hosts during shared turns and fence capture grants. <br> - Test wake gating, replay, multi-client arbitration and recovery. <br> - Fix pre-push gates on Windows. | 05/11/2026 | 05/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 6 | - Bound TTS requests and keep cancellation working; capture questions reported late by KWS. <br> - Load the shared encrypted env with dotenvx. <br> - Merge PR #7 feat/tina-speech into main. | 06/11/2026 | 06/11/2026 | [TINA PR #7](https://github.com/poor-frog/TINA/pull/7) |

### Week 8 Achievements:

* Delivered the voice assistant: say "Tina", ask a question and hear the answer inside the meeting.
* Handled concurrency: only one authorized speaker turn at a time, with recovery when a client drops.
* Wrote tests for wake gating, TTS protocol, playback and multi-client arbitration.
* Merged the feature into main through PR #7.
