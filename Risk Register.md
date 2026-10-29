# Risk Register
Project Name: Mountain Mama Media DAM 
Project Manager: Matthew Saville
Date Created: 10/29/2026
Last Updated: 10/29/2026

## Risk Scoring Guide
| Probability | Impact | How to Score |
|------------|--------|-------------|
| **High (3)** | **High (3)** | Probability × Impact = Risk Score |
| **Medium (2)** | **Medium (2)** | Example: Medium (2) × High (3) = 6 |
| **Low (1)** | **Low (1)** | Higher score = Higher priority |

**Priority Levels**:
- **Critical (7-9)**: Immediate attention required
- **High (5-6)**: Actively manage
- **Medium (3-4)**: Monitor regularly
- **Low (1-2)**: Keep on watchlist

## Risk Register Table
| ID | Risk Description | Category | Probability (1-3) | Impact (1-3) | Risk Score | Response Strategy | Mitigation Plan | Owner | Status | Last Update |
|----|-----------------|----------|-------------------|--------------|------------|-------------------|-----------------|-------|--------|------------|
| R-01 | Assets are lost or corrupted during migration from legacy cloud drives | Technical | 2 (Medium) | 3 (High) | 6 | Mitigate | Back up all source drives before migration; migrate in batches | MatthewSaville | Active | 2026-10-29 |
| R-02 | SSO integration fails or misconfigured role-based access exposes restricted or licensed content | Technical | 2 (Medium) | 3 (High) | 6 | Mitigate | Test SSO in secure environment first; keep a backup admin account; test every role against an access matrix | noahshort5 | Active | 2026-10-29 |
| R-03 | Freelancer portals give outside users access to content beyond their contracts | Technical | 2 (Medium) | 3 (High) | 6 | Mitigate | Limit freelancers to project-specific folders; set accounts to expire with the contract; review freelancer access monthly | sabrinabendel | Active | 2026-10-29 |
| R-04 | AI metadata tagging is inaccurate, making assets hard to find and rights data unreliable | Technical | 3 (High) | 2 (Medium) | 6 | Mitigate | Measure tagging accuracy; require human review of rights fields; let editors correct tags | kgn00003 | Active | 2026-10-29 |
| R-05 | Rights expiration tracking misses dates, leading to use of content with expired license | Technical | 2 (Medium) | 3 (High) | 6 | Mitigate | Test date tracking; send alerts ahead of expiration; flag assets with missing rights dates | MatthewSaville | Active | 2026-10-29 |
| R-06 | Stakeholders continue to push new scope into active sprints, such as resubmitting the rejected transcoding pipeline | Scope | 3 (High) | 2 (Medium) | 6 | Control | Route all new requests through the CCB; protect sprint commitments | MatthewSaville | Active | 2026-10-29 |
| R-07 | Search response time increases as the asset library grows after migration | Quality | 2 (Medium) | 2 (Medium) | 4 | Mitigate | Test search engine with the fully migrated library; set a response-time target; tune before go-live | noahshort5 | Active | 2026-10-29 |
| R-08 | Staff resist the new DAM and keep saving files to the old cloud drives | Stakeholder | 2 (Medium) | 2 (Medium) | 4 | Mitigate | Provide hands-on training; retire legacy drives on a set date | kgn00003 | Watchlist | 2026-10-29 |
