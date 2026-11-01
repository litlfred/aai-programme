---
# aai-platform-s7wq
$schema: bean/1.0.0
title: Sync the fork to the WHO repository
status: todo
type: task
priority: normal
parent: aai-platform-7aw2
tags:
    - sync
created_at: 2026-10-20T16:00:00Z
updated_at: 2026-11-01T10:05:00Z
issue: https://github.com/litlfred/folio-assistant/issues/2605
---

Work runs off `litlfred/aai-platform` for now (owner, 2026-10-20). When the owner says to sync:

## Done when

- [x] `main` is pushed or merged to `WorldHealthOrganization/aai-platform` (now aai-programme; WHO PR #2, then #57)
- [x] The branch `cat/aai-platform/beans` is pushed there (befe225)
- [ ] The first entry in `beans-sources.json` points at the WHO repo (litlfred/aai-programme#60, open)
- [ ] The section 7.3 labels exist on the WHO repo
- [ ] `bun run scripts/pull-beans.ts` reads the WHO store (checked locally on #60: 25 beans)
