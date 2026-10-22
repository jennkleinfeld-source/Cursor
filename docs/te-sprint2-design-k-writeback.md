# T&E Sprint 2 — Jira create + Design!K writeback

Live sheet: `1p4v4LrUYiwohmmXDQcJmv7KHqYeUJkFYqPXC6T8AlZY`  
Parent epic: [SALES-9714](https://trr-prod.atlassian.net/browse/SALES-9714)

## Batch 1 (2026-10-20) — complete

| Story | Design | Key | Assignee |
| --- | --- | --- | --- |
| ST-024 | DS-005 / K15 | [SALES-10175](https://trr-prod.atlassian.net/browse/SALES-10175) | Michael Criswell |
| ST-025 | DS-061 / K62 | [SALES-10176](https://trr-prod.atlassian.net/browse/SALES-10176) | Michael Criswell |
| ST-041 | DS-051 / K19 | [SALES-10178](https://trr-prod.atlassian.net/browse/SALES-10178) | Chris Burns |
| ST-042 | DS-029 / K20 | [SALES-10180](https://trr-prod.atlassian.net/browse/SALES-10180) | Michael Criswell |
| ST-043 | DS-056 / K21 | [SALES-10181](https://trr-prod.atlassian.net/browse/SALES-10181) | Alex Burton |
| ST-044 | DS-055 / K22 | [SALES-10177](https://trr-prod.atlassian.net/browse/SALES-10177) | Alex Burton |
| ST-046 | DS-031 / K24 | [SALES-10179](https://trr-prod.atlassian.net/browse/SALES-10179) | Chris Burns |

## Batch 2 (2026-10-21) — complete

| Story | Summary | Eng | Sprint | Key | Design K |
| --- | --- | --- | --- | --- | --- |
| ST-045 | Assign cleared T&E Opps back to referring Ambassadors | Alex Burton | 2 | [SALES-10188](https://trr-prod.atlassian.net/browse/SALES-10188) | K23 LOCKED |
| ST-070 | Enforce legal approval locks before convert/booking/shipping | Michael | 2 | [SALES-10189](https://trr-prod.atlassian.net/browse/SALES-10189) | K45 LOCKED |
| ST-007 | Dedicated trust/estate payout account | Nag Malluru | 2 | [SALES-10193](https://trr-prod.atlassian.net/browse/SALES-10193) | K5–K7 LOCKED |
| ST-008 | T&E Event master (Labs Events / DS-048) | Michael | 2 | [SALES-10194](https://trr-prod.atlassian.net/browse/SALES-10194) | K9 LOCKED |

Change Log: `A27:F28` documents ST-045/070 and ST-007/008 Design K writes.  
ST-007 timeout duplicates SALES-10190–10192 → Won't Do (canonical SALES-10193).

## Batch 3 scan (2026-10-22) — create blocked (Atlassian MCP)

Filter re-read: DoR YES · U blank · X starts READY FOR JIRA · MoSCoW Must · Sprint ∈ {0,1,2}.

### Ready to create (1)

| Story | Summary | Eng | Sprint | Design | Design K target |
| --- | --- | --- | --- | --- | --- |
| ST-089 | Capture BDM qualification fields on Lead (relationship, sensitivity, authority, timing) | Michael | 2 | DS-047 Signed off · M READY FOR JIRA · Y empty · ARB N | **K52** |

Payload drafted: `/tmp/create_ST-089.json` (assignee Michael `632d5cf588ed2ebef97a88ab`, parent SALES-9714, AC-270–273).  
**Blocked:** Atlassian MCP on this Cloud Agent surface is local-only / discovery error — `createJiraIssue` cannot reach Jira from the agent VM. Re-auth or run create from Cursor Desktop, then write the key to Design!K52 and log Change Log.

### Near-misses (not in default filter)

| Story | Why excluded |
| --- | --- |
| ST-096 | DoR YES · READY FOR JIRA · Sprint 2 · Design DS-073 Signed off — but **MoSCoW blank** (not Must) |
| ST-028 | READY FOR JIRA · Sprint 2 — MoSCoW **Should** |
| ST-047 | READY FOR JIRA · Sprint 2 · DS-032 Signed off — MoSCoW **Should** |
| ST-022 / ST-027 / ST-057–060 / ST-063 / ST-065 / ST-076 | READY FOR JIRA · DoR YES · U blank — but **Sprint 3** (outside 0/1/2) |
