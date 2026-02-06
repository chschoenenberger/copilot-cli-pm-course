# Weekly Meeting Summary

**Week of January 6-17, 2025**

---

## Meeting 01: Sprint Planning
### Key Decisions
- Mobile onboarding flow to start Monday with 2 engineers
- Bug fixes from last sprint (3 P1 bugs) need to be addressed
- Notification improvements being considered for deprioritization

### Action Items
| Action | Owner |
|--------|-------|
| Review bug list and confirm priorities by end of day | PM |
| Share final onboarding mockups in Figma | Jordan |

### Blockers
- Waiting on API docs from partner team
- Design review backlog is growing

### Next Steps
- Engineers to start on Jordan's mobile onboarding designs Monday
- Bug priorities to be confirmed by end of day

---

## Meeting 02: TechCorp Customer Call (Jan 7)
### Key Decisions
- SSO (SAML) is a must-have requirement for TechCorp to sign
- Target go-live date set for end of Q1
- Pilot group of 20 users with 500 total for full rollout

### Action Items
| Action | Owner |
|--------|-------|
| Scope SSO timeline | Mike |
| Send security questionnaire response | PM |

### Blockers
- **SSO blocker**: TechCorp cannot sign until SSO is implemented

### Next Steps
- Complete SSO scoping to determine feasibility for Q1 timeline
- Address enterprise requirements: audit logs, admin dashboard, bulk user provisioning

---

## Meeting 03: Metrics Review
### Key Decisions
- Hypothesis: onboarding is too long (7 steps) — likely cause of activation dropoff
- Templates identified as priority feature based on customer feedback

### Action Items
| Action | Owner |
|--------|-------|
| Work with Jordan on shortened onboarding | TBD |
| Create template library spec | TBD |

### Blockers
- Activation metrics stuck at 45% (target: 60%)
- Android build is 2 weeks behind iOS
- Push notifications not working on some devices

### Next Steps
- Shorten onboarding flow from 7 steps
- Develop template library (marketing template highest priority)
- Resolve mobile push notification issues

---

## Meeting 04: Engineering Sync (Jan 9)
### Key Decisions
- Performance issues must be addressed before mobile launch
- Team capacity is insufficient for running mobile + SSO simultaneously
- Recommendation to hire 2 more engineers

### Action Items
| Action | Owner |
|--------|-------|
| Create performance improvement plan | Lisa |
| Make case for hiring to Sarah | PM |

### Blockers
- Page load times at 2.3s (target is <1s)
- Database queries need optimization
- Redis cache hit rate dropped
- Auth system needs refactor
- Test coverage at 62% (target 80%)
- Team is stretched thin

### Next Steps
- Lisa to develop performance improvement plan
- Build hiring justification for presenting to Sarah

---

## Meeting 05: Design Review (Jan 10)
### Key Decisions
- Reduced onboarding from 7 steps to 4 steps
- New onboarding structure:
  - Step 1: Create workspace (consolidated)
  - Step 2: Invite team (optional, skippable)
  - Step 3: Create first task (guided)
  - Step 4: Celebration + next steps
- Template picker will have 4 categories: marketing, engineering, operations, personal

### Action Items
| Action | Owner |
|--------|-------|
| Finalize designs and share with eng by Monday | Jordan |
| Review accessibility checklist | PM |

### Blockers
- Accessibility audit needed before proceeding
- Mobile version requires separate designs
- Dark mode support needed for new screens

### Next Steps
- Jordan to finalize designs and share with engineering by Monday
- Address mobile and dark mode design gaps

---

## Meeting 06: Sales Feedback
### Key Decisions
- None explicitly stated

### Action Items
| Action | Owner |
|--------|-------|
| Create enterprise feature roadmap doc | PM |
| Share competitive loss details | Tom |

### Blockers
- SSO is blocking every enterprise deal
- Perceived as "startup tool" — hurting enterprise credibility
- Lost 2 deals to Linear (speed/keyboard shortcuts gap)
- Lost 1 deal to Asana (brand trust gap)

### Next Steps
- Develop enterprise feature roadmap: SSO, advanced permissions, GitHub integration, audit logs, custom fields
- Build stronger enterprise positioning

---

## Meeting 07: Customer Success Sync (Jan 14)
### Key Decisions
- None explicitly stated

### Action Items
| Action | Owner |
|--------|-------|
| Investigate onboarding ticket spike | PM |
| Send at-risk account details | Maria |

### Blockers
- **Churn risk**: 3 accounts at-risk (missing features, poor adoption, champion departures)
- **SSO dependency**: 5 enterprise expansion opportunities blocked
- **Onboarding issues**: Tickets have doubled since November

### Next Steps
- Investigate the onboarding ticket spike (urgent)
- Review at-risk account details
- Address SSO requirement to unlock enterprise expansion

---

## Meeting 08: All Hands Product Update (Jan 15)
### Key Decisions
- Mobile app priority: iOS first, then Android
- International expansion is not a Q1 priority
- SSO implementation scheduled for Q1
- Activation improvements included in Q1 roadmap

### Action Items
| Action | Owner |
|--------|-------|
| Create mobile launch plan with marketing | TBD |
| Share enterprise roadmap with sales | TBD |

### Blockers
- Need to hire more engineers

### Next Steps
- Launch mobile app (iOS then Android)
- Implement SSO
- Deliver activation improvements
- Coordinate with marketing on mobile launch

---

## Meeting 09: 1:1 with Sarah (Jan 16)
### Key Decisions
- Templates should be bundled with onboarding
- Activation work is the priority focus
- SSO cannot slip from timeline

### Action Items
| Action | Owner |
|--------|-------|
| Prepare board presentation draft | PM |
| Help with eng resource conversation | Sarah |

### Blockers
- Need engineering resources
- Risk of distraction from "shiny objects"

### Next Steps
- Present activation improvement strategy at next board meeting
- Attend customer visits (pending approval)
- Consider conference speaking opportunities

---

## Meeting 10: User Interview (Jan 17)
### Key Decisions
- None (interview format)

### Action Items
| Action | Owner |
|--------|-------|
| Add recurring tasks to roadmap consideration | TBD |
| Explore time tracking partnerships | TBD |

### Blockers
- No mobile app (user checks tasks on phone frequently)
- No built-in time tracking (user paying $500/year for Toggl)
- Missing recurring tasks feature

### Next Steps
- Evaluate recurring tasks for roadmap inclusion
- Research time tracking partnership opportunities
- Consider agency-specific templates

---

# Executive Summary

## 🔑 Top Decisions This Week
1. **Onboarding reduced from 7 steps to 4 steps** to improve activation
2. **Mobile app priority**: iOS first, then Android
3. **SSO scheduled for Q1** — critical for enterprise deals
4. **Templates to be bundled with onboarding**
5. **Need to hire 2 more engineers** — team at capacity

## ⚡ All Action Items

| Action | Owner | Meeting |
|--------|-------|---------|
| Review bug list and confirm priorities | PM | 01 |
| Share final onboarding mockups in Figma | Jordan | 01 |
| Scope SSO timeline | Mike | 02 |
| Send security questionnaire response | PM | 02 |
| Work with Jordan on shortened onboarding | TBD | 03 |
| Create template library spec | TBD | 03 |
| Create performance improvement plan | Lisa | 04 |
| Make case for hiring to Sarah | PM | 04 |
| Finalize designs and share with eng by Monday | Jordan | 05 |
| Review accessibility checklist | PM | 05 |
| Create enterprise feature roadmap doc | PM | 06 |
| Share competitive loss details | Tom | 06 |
| Investigate onboarding ticket spike | PM | 07 |
| Send at-risk account details | Maria | 07 |
| Create mobile launch plan with marketing | TBD | 08 |
| Share enterprise roadmap with sales | TBD | 08 |
| Prepare board presentation draft | PM | 09 |
| Help with eng resource conversation | Sarah | 09 |
| Add recurring tasks to roadmap consideration | TBD | 10 |
| Explore time tracking partnerships | TBD | 10 |

## 🚧 Critical Blockers

| Blocker | Impact | Source |
|---------|--------|--------|
| **SSO not implemented** | Blocking all enterprise deals, 5 expansion opportunities | Meetings 02, 06, 07 |
| **Performance issues** (2.3s load time) | Must fix before mobile launch | Meeting 04 |
| **Engineering capacity** | Cannot run mobile + SSO simultaneously | Meetings 04, 08, 09 |
| **Activation at 45%** (target 60%) | Main business metric at risk | Meeting 03 |
| **Onboarding tickets doubled** | Customer success struggling | Meeting 07 |
| **3 accounts at churn risk** | Revenue impact | Meeting 07 |

## 📋 Priority Next Steps
1. **Implement SSO** — blocking enterprise revenue
2. **Ship shortened onboarding (4 steps)** — improve activation
3. **Fix performance issues** — prerequisite for mobile launch
4. **Hire 2 engineers** — team at capacity
5. **Launch iOS app** — user demand confirmed
6. **Create enterprise roadmap** — win back competitive losses
