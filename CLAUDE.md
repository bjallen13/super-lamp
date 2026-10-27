# CLAUDE.md

This repo is a thin bridge. The real project context lives in Google Drive —
read it from there, don't duplicate it here.

## Source of truth: Google Drive

Folder: **My Drive › Claude-Work › Projects**
- Folder ID: `1fyaVGogs9A_Y_Z6GOcv-BppdUiAdKwaZ`
- https://drive.google.com/drive/folders/1fyaVGogs9A_Y_Z6GOcv-BppdUiAdKwaZ

Key files (look up by ID via the Google Drive connector):

| File | ID | Use |
|---|---|---|
| `next-steps-tracker_2.md` | `1v8iN2DmuEa83O-Azv5u7Q6FQc08ewoQ0` | Live backlog across all businesses — the current copy despite the `_2` suffix |
| `three-business-playbook.md` | `1YHvsmeoa-jZdO8erQuvPgf5j7Ywq-eGA` | Priority order and standing rules |

Subfolders: Retail RE, Glide RE, Wholesale RE, Trading, Seller Portal - Utah Digs,
Trending Content Radar, Claude - Business Ideas - AI - Tools, Claude outputs.

## Session protocol

1. **Start:** read the tracker and playbook above before doing anything else.
   Open the relevant business subfolder for the task at hand.
2. **During:** follow the priority order in the playbook
   (Retail → Glide/Wholesale → Trading).
3. **End:** report what changed and propose the tracker update. Write to Drive
   only when Blair approves it.

If the Google Drive connector is unavailable, say so plainly and stop. Don't
work from memory or guess at the files' contents.

## Parallel workers

Only one session (the coordinator) edits a given Drive doc. Worker sessions
report results back to it, or each writes its own new file in `Claude outputs`,
so they never overwrite each other.

## Standing rules

- Everything client-facing is draft-only and human-reviewed. Nothing gets
  auto-sent, and the same goes for trades: no auto-execution, ever.
- Rehab, ARV and expense numbers come from Blair's own inputs, never from
  model estimates.
- Honesty: flag uncertainty, never invent sources or statistics, call out
  anything that may have changed since the knowledge cutoff, and never
  attribute a quote unless certain.
