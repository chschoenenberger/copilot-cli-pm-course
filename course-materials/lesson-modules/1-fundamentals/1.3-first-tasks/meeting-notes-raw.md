# TaskFlow Meeting Notes - January 2025
## Week of January 6-17, 2025

Consolidated meeting notes from 10 meetings across two weeks covering Q1 priorities, mobile launch, SSO implementation, activation improvements, and customer insights.

---

## Meeting 01: Sprint Planning - January 6, 2025
**Attendees:** Mike (CTO), Lisa (Eng Lead), Jordan (Design), PM

### Priorities
- Mobile onboarding flow - Jordan has designs ready, Lisa allocated 2 engineers starting Monday
- Bug fixes from last sprint - 3 P1 bugs requiring attention
- Notification improvements - Mike wants to deprioritize (disagreement noted)

### Blockers
- Waiting on API docs from partner team
- Design review backlog growing

### Action Items
- PM to review bug list and confirm priorities by EOD
- Jordan to share final onboarding mockups in Figma

---

## Meeting 02: Customer Call - TechCorp - January 7, 2025
**Attendees:** Sarah M (TechCorp VP of IT), PM

### Enterprise Requirements
1. **SSO is absolute must-have** - SAML specifically required
2. Audit logs for compliance
3. Enhanced admin dashboard
4. Bulk user provisioning

**Critical Quote:** "We can't sign until you have SSO. Our security team won't approve it." - Sarah M

### Deal Details
- **Timeline:** Go-live by end of Q1
- **Contract Value:** $150k ARR potential
- **Rollout:** 20 people in pilot, 500 total users

### Action Items
- Mike to scope SSO timeline
- PM to send security questionnaire response

---

## Meeting 03: Product Review - January 8, 2025
**Attendees:** Sarah (Head of Product), PM

### Activation Metrics Analysis
- **Current State:** 45% activation rate
- **Target:** 60% activation rate
- **Main Dropoff:** Between signup and first task creation
- **Hypothesis:** Onboarding is too long (currently 7 steps)

### Customer Feature Requests
- **Template Library:** Third customer this week requesting templates
  - Marketing template: Most requested
  - Engineering sprint template: Second most requested

### Mobile Progress Update
- iOS build looking good
- Android 2 weeks behind schedule
- **Concern:** Push notifications not working on some devices

### Action Items
- Work with Jordan on shortened onboarding
- Create template library specification

---

## Meeting 04: Engineering Sync - January 9, 2025
**Attendees:** Lisa (Eng Lead), Engineering Team, PM

### Performance Issues (Critical)
- Page load times creeping up: **2.3s average (target: <1s)**
- Database queries need optimization
- Redis cache hit rate dropped

**Critical Quote:** "We need to address this before mobile launch or it'll be even worse." - Lisa

### Technical Debt Inventory
- Auth system needs refactor
- Test coverage at 62% (target: 80%)
- Dependency updates overdue

### Team Capacity Concerns
- Team stretched thin
- **Risk:** Mobile + SSO simultaneously is risky
- **Recommendation:** Hire 2 more engineers

### Action Items
- Lisa to create performance improvement plan
- PM to make hiring case to Sarah

---

## Meeting 05: Design Review - January 10, 2025
**Attendees:** Jordan (Design), PM

### Onboarding V2 Design
**Reduced from 7 steps to 4:**
1. Create workspace (consolidated from 2 previous steps)
2. Invite team (optional, skippable)
3. Create first task (guided experience)
4. Celebration + next steps

**Quote:** "Simpler is better. We were asking too much upfront." - Jordan

### Template Picker Design
- Mockups complete for template selection screen
- **Categories:** Marketing, Engineering, Operations, Personal
- Preview functionality before selection

### Design Concerns
- Accessibility audit needed
- Mobile version requires separate designs
- Dark mode support for new screens

### Action Items
- Jordan to finalize and share with engineering by Monday
- PM to review accessibility checklist

---

## Meeting 06: Sales Sync - January 13, 2025
**Attendees:** Tom (Sales Lead), 2 Account Executives, PM

### Pipeline Update
- **3 enterprise deals in late stage**
- **All asking about SSO**
- **Total Pipeline:** $450k ARR

### Lost Deals Analysis (January)
- 2 deals lost to Linear (reasons: speed, keyboard shortcuts)
- 1 deal lost to Asana (reason: brand trust)

**Quote:** "We need to tell a better enterprise story. They see us as a startup tool." - Tom

### Top Feature Requests from Prospects
1. SSO (every enterprise deal mentions this)
2. Advanced permissions
3. Better GitHub integration
4. Audit logs
5. Custom fields

### Action Items
- PM to create enterprise feature roadmap document
- Tom to share detailed competitive loss analysis

---

## Meeting 07: Customer Success Sync - January 14, 2025
**Attendees:** Maria (CS Lead), PM

### Churn Risk Accounts
- **3 accounts flagged as at-risk**
- **Reasons:** Missing features, poor adoption, champion left company

### Expansion Opportunities
- **5 accounts ready for enterprise upgrade**
- **Blocker:** Need SSO to close deals

### Support Ticket Trends
**Top Categories:**
1. Onboarding confusion (35%)
2. Integration issues (25%)
3. Notification settings (20%)
4. Performance complaints (15%)
5. Other (5%)

**Critical Insight:** "Onboarding tickets have doubled since November. Something changed." - Maria

### Action Items
- PM to investigate onboarding ticket spike
- Maria to send at-risk account details

---

## Meeting 08: All Hands Product Update - January 15, 2025
**Attendees:** Entire Company, PM presenting

### Q4 Highlights Shared
- Shipped notifications v2
- Launched dark mode
- Improved performance by 20%

### Q1 Roadmap Announced
- Mobile app (iOS first, then Android)
- SSO implementation
- Activation improvements

### Team Questions
- "When is mobile launching?" (multiple people asked)
- "Can we use TaskFlow on mobile now?" (Yes, mobile web available, app coming)
- "Are we hiring more engineers?" (Working on it)
- "What about international expansion?" (Not Q1 priority)

### Internal Stakeholder Requests
- Marketing wants launch content for mobile
- Sales needs enterprise feature timeline
- Customer Success wants better onboarding documentation

### Action Items
- Create mobile launch plan with marketing
- Share enterprise roadmap with sales

---

## Meeting 09: 1:1 with Sarah (Head of Product) - January 16, 2025
**Attendees:** Sarah (Head of Product), PM

### Career Development
- Sarah wants PM to present at next board meeting
- Opportunity for leadership visibility
- **Topic:** Activation improvement strategy

### Project Priorities
1. **Activation work is #1 priority**
2. Templates should be bundled with onboarding
3. SSO must not slip from timeline

### Manager Feedback
**Quote:** "You're doing great but need to push back more on requests. Can't do everything." - Sarah

**Quote:** "Focus on activation. That's your metric. Don't get distracted by shiny objects."

### PM's Requests
- Need help securing engineering resources
- Want to attend customer visits
- Considering conference speaking opportunities

### Action Items
- Prepare board presentation draft
- Sarah to help with engineering resource conversation

---

## Meeting 10: User Interview - January 17, 2025
**Attendees:** James K (Agency Owner, Power User), PM

### User Background
- Using TaskFlow for 8 months
- Manages 5 client projects with 25 employees
- Upgraded from Free to Pro plan

### What User Loves
- **"The speed. Everything loads instantly. We came from Monday and it was painful."**
- Keyboard shortcuts
- Clean interface

### Pain Points & Wishes
1. **No mobile app** (checks tasks on phone frequently)
2. Wants recurring tasks feature
3. Needs time tracking (currently using separate tool)

**Quote:** "If you had time tracking built in, I could cancel Toggle. That's $500/year I'd give you instead."

### Template Needs (Agency-Specific)
- Client onboarding template
- Project kickoff template
- Monthly reporting template

### Pricing Feedback
- Happy with current pricing
- Would pay more for time tracking
- Concerned about enterprise pricing if company grows

### Action Items
- Add recurring tasks to roadmap consideration
- Explore time tracking partnerships

---

## Summary: Key Themes Across All Meetings

### 🚨 Critical Blockers
1. **SSO Implementation** - Blocking $600k+ in enterprise pipeline (TechCorp $150k + 5 expansion deals)
2. **Activation Crisis** - Stuck at 45%, need 60%, onboarding tickets doubled
3. **Resource Constraints** - Team stretched thin with mobile + SSO simultaneously

### 📊 Quantified Insights
- Current activation rate: 45% (target: 60%)
- Time to first task: 8 minutes (target: <2 minutes)
- Page load time: 2.3s (target: <1s)
- Test coverage: 62% (target: 80%)
- Onboarding confusion tickets: 35% of all support volume (doubled since November)

### 💰 Revenue Impact
- **At Risk:** $150k TechCorp deal (hard deadline: March 15)
- **Pipeline:** $450k ARR waiting on SSO
- **Expansion:** 5 accounts ready to upgrade (blocked by SSO)
- **Churn Risk:** 3 accounts flagged

### 🎯 Consensus Priorities (Q1 2025)
1. **Mobile App Launch** - iOS end of Q1, Android 2 weeks later
2. **SSO Implementation** - SAML first, 6-8 week project
3. **Activation Improvements** - Simplified onboarding (7 steps → 4 steps)
4. **Template Library** - Marketing and engineering templates most requested

### 🔧 Technical Debt & Performance
- Auth system refactor needed
- Performance degradation (2.3s page loads)
- Database optimization required
- Redis cache issues

### 👥 Competitive Intelligence
- Lost deals to Linear (speed, keyboard shortcuts)
- Lost deals to Asana (brand trust)
- Perception issue: "Seen as a startup tool, not enterprise-ready"

### ✅ All Action Items by Owner

**PM (You):**
- Review bug list and confirm priorities (EOD Jan 6)
- Send security questionnaire to TechCorp
- Get detailed SSO requirements from TechCorp
- Run experiment with simplified first-run experience
- Work with marketing on email nurture sequence
- Create template library spec
- Make hiring case to Sarah
- Review accessibility checklist
- Create enterprise feature roadmap doc
- Investigate onboarding ticket spike (doubled since Nov)
- Create mobile launch plan with marketing
- Share enterprise roadmap with sales
- Prepare board presentation draft (topic: activation strategy)
- Add recurring tasks to roadmap consideration
- Explore time tracking partnerships

**Engineering (Mike/Lisa):**
- Scope SSO timeline and identify contractor needs
- Scope SAML work specifically
- Create performance improvement plan
- Finalize and share specs with team by Monday

**Design (Jordan):**
- Share final onboarding mockups in Figma (EOD Jan 6)
- Simplify onboarding from 7 steps to 4
- Finalize designs and share with eng by Monday (Jan 13)

**Sales (Tom):**
- Share competitive loss details and analysis

**Customer Success (Maria):**
- Send at-risk account details

**Leadership (Sarah):**
- Help with engineering resource conversation
- Confirm team offsite dates (March)

---

## Open Questions & Decisions Needed
1. Android timeline? (iOS first, but specific Android date unclear)
2. Who owns template library project?
3. Hire for mobile or use contractors?
4. TechCorp deadline - hard or soft? (March 15 stated)
5. Notification approach: Push + in-app hybrid?
6. SAML vs OAuth - SAML first confirmed, but both eventually?
7. Need SAML contractor? (In-house expertise lacking)

---

## PM Reflection Notes
- Q1 priorities clear but resource constraints concerning
- TechCorp deal critical - cannot miss March 15 deadline
- Mike seems stressed about mobile + SSO simultaneously
- Onboarding ticket spike (doubled) suggests recent regression - needs urgent investigation
- Template requests accelerating - 3rd customer this week
- Sarah's feedback to focus on activation and push back on scope is important
- Performance issues (2.3s loads) must be addressed before mobile launch
- 5 expansion opportunities blocked by SSO = real revenue at risk
- User interview (James K) validates speed as differentiator but highlights mobile and time tracking gaps
