# JH-PROD-20260918-17-MIX

Job Hunter PRODUCT research lane (not the personal Job Pack application loop).

- Run ID: `JH-PROD-20260918-17-MIX`
- Timezone: Asia/Bangkok
- Retrieval window: 2026-09-18 17:16–18:20 +07 (10:16–11:20 UTC)
- Persistence: **unverified**. Native prior-run storage empty per supervisor. Pilot `https://grok.com/c/4df77e3e-58e0-4719-add3-38041ce0737d` login-walled / no extractable artifacts.
- Review state: **unreviewed**. Do not call these records independently verified.
- No applications submitted. No salary/sponsorship/fit inferred.
- Previous research remains unreviewed.

## Download

GitHub ZIP (branch main):
https://github.com/chkae88-pixel/jh-prod-20260918-17-mix/archive/refs/heads/main.zip

## Files

| File | Purpose |
|---|---|
| `checkpoint.json` | Completed / pending IDs, real counts from tables |
| `employers.json` | 20 NEW employer career-source records |
| `pending_rechecks.json` | Supervisor pending items (≤25% of run) |
| `roles.csv` | Roles captured with apply-page status |
| `employers.csv` | Flat employer registry |
| `briefs.json` | 3 reusable employer briefs |
| `eval_cases.json` | 5 synthetic evaluation cases |
| `sources.csv` | Source URL + timestamps + scope |
| `review_queue.json` | Next-run recheck queue |
| `refresh_dedup_spec.json` | Refresh / deduplication specification |
| `watchlist.csv` | Employers / boards without apply-verified live roles |

## Count rule

All counts in `checkpoint.json` are derived from the tables in this export after merge. Do not trust chat run_meta.

## Conservative apply flag

`apply_form_verified=false` run-wide. Presence of an `/apply` path or Apply Now button is stored as `apply_path_observed` only.
