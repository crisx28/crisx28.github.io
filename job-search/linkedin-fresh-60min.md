# LinkedIn — Jobs Posted in the Last 60 Minutes

LinkedIn's dropdown only shows "Past 24 hours" as its freshest option. The real time filter
is the URL parameter **`f_TPR=r<seconds>`**. Set the seconds yourself to get truly fresh posts.

## The parameter

| Freshness | `f_TPR` value |
|-----------|---------------|
| Last 24 hours (the dropdown default) | `r86400` |
| **Last 60 minutes** | **`r3600`** |
| Last 30 minutes | `r1800` |
| Last 15 minutes | `r900` |
| Last 10 minutes | `r600` |

Always add **`sortBy=DD`** = sort by Date, newest first, so the just-posted role is at the top.

### Other filter codes used in the links below
- `f_JT=P%2CC` → Job type = Part-time **and** Contract (`P`=part-time, `C`=contract, `F`=full-time)
- `f_WT=2` → Workplace = Remote (`1`=on-site, `2`=remote, `3`=hybrid)
- `geoId=92000000` → Worldwide (change to target one country — codes below)
- `keywords=` → your search term (URL-encode spaces as `%20`)

Country geoIds (swap into `geoId=`): Worldwide `92000000` · United States `103644278` ·
United Kingdom `101165590` · Canada `101174742` · Australia `101452733` ·
Singapore `102454443` · United Arab Emirates `104305776`.

---

## Ready-to-click links — last 60 minutes, part-time + contract, remote, worldwide

**IT Support**
https://www.linkedin.com/jobs/search/?keywords=IT%20Support&f_TPR=r3600&f_JT=P%2CC&f_WT=2&geoId=92000000&sortBy=DD

**Microsoft 365 Administrator**
https://www.linkedin.com/jobs/search/?keywords=Microsoft%20365%20Administrator&f_TPR=r3600&f_JT=P%2CC&f_WT=2&geoId=92000000&sortBy=DD

**Help Desk**
https://www.linkedin.com/jobs/search/?keywords=Help%20Desk&f_TPR=r3600&f_JT=P%2CC&f_WT=2&geoId=92000000&sortBy=DD

**Google Workspace**
https://www.linkedin.com/jobs/search/?keywords=Google%20Workspace&f_TPR=r3600&f_JT=P%2CC&f_WT=2&geoId=92000000&sortBy=DD

**Technical Support**
https://www.linkedin.com/jobs/search/?keywords=Technical%20Support&f_TPR=r3600&f_JT=P%2CC&f_WT=2&geoId=92000000&sortBy=DD

**One combined search (boolean keywords)**
https://www.linkedin.com/jobs/search/?keywords=%28%22IT%20Support%22%20OR%20%22Help%20Desk%22%20OR%20%22Microsoft%20365%22%20OR%20%22Google%20Workspace%22%29&f_TPR=r3600&f_JT=P%2CC&f_WT=2&geoId=92000000&sortBy=DD

---

## To make it even tighter
- **Even fresher:** change `r3600` → `r1800` (30 min) or `r900` (15 min) in any link above.
- **One country only:** replace `geoId=92000000` with a code from the table (e.g. US = `103644278`).
- **Include full-time too:** change `f_JT=P%2CC` → `f_JT=F%2CP%2CC`.
- **Bookmark each link.** Refreshing it = a live "posted in the last hour" feed you re-run any time.

## Honest limits
- **You must open these in your own logged-in browser.** I can't fetch LinkedIn results here —
  it's auth-walled and returns a login wall to any automated request, so I can't pull the
  actual postings for you or verify counts.
- `f_TPR` is an unofficial (but long-working) LinkedIn URL parameter. It can change without
  notice; if a link ever ignores the time filter, LinkedIn tweaked it — the dropdown's
  "Past 24 hours" is the always-supported fallback.
- A 60-minute window is often **empty** for a niche remote part-time search — that's normal,
  not a broken link. Widen to `r86400` (24h) or set an alert (below) so nothing slips past.

## Better than refreshing: a real-time alert
On any of the searches above, click **Set alert** and choose the most frequent option. LinkedIn
then emails/notifies you as matching roles are posted — effectively a push feed of fresh jobs,
without you re-running URLs. Pair it with **#OpenToWork** so recruiters find you too.
