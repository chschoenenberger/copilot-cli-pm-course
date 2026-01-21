# TaskFlow User Personas

**Deep dive into who uses TaskFlow and why**

---

## Overview

TaskFlow serves three primary user personas across our customer base. Understanding these personas is critical for product decisions - every feature should serve at least one persona's core needs.

---

## Persona 1: Sarah (Enterprise Admin)

### Quick Facts

**Name:** Sarah Chen  
**Age:** 38  
**Role:** VP of IT Operations  
**Company:** TechCorp (800 employees, Series C)  
**Location:** Austin, TX (remote team across US)  
**TaskFlow Plan:** Enterprise

### Background

Sarah leads IT operations for a fast-growing SaaS company. Her team supports 800 employees across 15 tools. She reports to the CTO and owns IT budget ($2M annually).

**Career path:**
- Started as IT support specialist
- Grew to IT Manager
- Now VP of IT Operations (6 direct reports)
- 12 years in IT, 8 years at current company

### Goals & Motivations

**Primary goals:**
1. **Reduce tool sprawl** - Currently using 25+ tools, want to consolidate to 10-12
2. **Improve security posture** - Pass SOC 2 audit, meet enterprise customer requirements
3. **Control costs** - $2M budget, need to show ROI on every tool
4. **Enable teams** - Give employees good tools without compromising security

### Pain Points

1. **Tool sprawl is out of control** - No central place to see what's happening
2. **Security nightmares** - Shadow IT, no visibility into access
3. **Onboarding/offboarding chaos** - Takes 2 days to fully provision someone
4. **No visibility** - Can't report up to executives easily

### TaskFlow Features They Care About

**Must-haves:**
- ✅ SSO (Single Sign-On) via SAML - non-negotiable
- ✅ Audit logs - who did what, when, why
- ✅ Advanced permissions - role-based access control
- ✅ Bulk user management - add/remove many users at once

**Nice-to-haves:**
- Usage analytics, data export, 99.9% uptime SLA

### Quotes

*"Security isn't negotiable. If you don't have SSO and audit logs, we can't even consider you."*

*"When an employee leaves, I lose sleep wondering if we've revoked all their access."*

---

## Persona 2: Mike (IC Engineer)

### Quick Facts

**Name:** Mike Rodriguez  
**Age:** 29  
**Role:** Senior Software Engineer  
**Company:** GrowthLabs (150 employees, Series B)  
**Location:** Portland, OR (fully remote)  
**TaskFlow Plan:** Pro (company-wide)

### Background

Mike is a senior engineer focused on backend systems. He codes 6-8 hours per day, attends 2-3 meetings per week, works across 4 timezones.

**Career path:**
- Bootcamp grad (2018)
- Junior → Mid → Senior engineer (5 years)
- Specializes in Node.js, PostgreSQL, AWS

### Goals & Motivations

**Primary goals:**
1. **Deep work** - Long, uninterrupted focus time
2. **Clear priorities** - Know exactly what to work on
3. **Minimize context switching** - Fewer tools, less jumping around
4. **Ship quality code** - Pride in craftsmanship

### Pain Points

1. **Priority confusion** - Multiple sources of truth
2. **Insufficient context** - Tasks lack technical details
3. **Meeting overload** - Standups could be async
4. **Slow, bloated tools** - Heavy, laggy interfaces

### TaskFlow Features They Care About

**Must-haves:**
- ✅ Keyboard shortcuts - navigate without mouse
- ✅ Fast performance - sub-second page loads
- ✅ GitHub integration - PRs linked to tasks
- ✅ Rich markdown - code blocks, syntax highlighting

**Nice-to-haves:**
- Dark mode, offline mode, API access, CLI tool

### Quotes

*"If your tool is slow, I won't use it. I'll find a faster alternative or build my own."*

*"Just tell me what to build, give me the context, and let me code."*

---

## Persona 3: Alex (Team Lead)

### Quick Facts

**Name:** Alex Rivera  
**Age:** 35  
**Role:** Engineering Manager  
**Company:** DataFlow (200 employees, Series B)  
**Location:** San Francisco, CA (remote team across 5 timezones)  
**TaskFlow Plan:** Pro  
**Team size:** 8 engineers

### Background

Alex manages a distributed engineering team. Former senior engineer, promoted to manager 2 years ago. Still codes occasionally (~20% time) but primarily focuses on team productivity.

**Career path:**
- Engineer (5 years)
- Tech lead (2 years)
- Engineering manager (2 years)
- Goal: Director of Engineering

### Goals & Motivations

**Primary goals:**
1. **Team success** - Deliver on time, with quality, without burnout
2. **Clear visibility** - Know status without asking
3. **Balanced workload** - No one overloaded or underutilized
4. **Career growth** - Develop team members, grow to Director

### Pain Points

1. **No visibility without asking** - Have to ping team for status
2. **Constant context switching** - Checking 5 tools to understand status
3. **Reporting up is painful** - Takes hours to gather data
4. **Team balance issues** - Hard to see capacity at a glance

### TaskFlow Features They Care About

**Must-haves:**
- ✅ Team dashboard - everyone's tasks at a glance
- ✅ Workload view - who's overloaded, who has capacity
- ✅ Blocked task visibility - red flags, urgent attention
- ✅ Sprint reports - velocity, burndown, predictability

**Nice-to-haves:**
- Predictive analytics, historical velocity, performance tracking

### Quotes

*"I need to know if my team is on track without asking them individually every day."*

*"When I'm in back-to-back meetings all day, I need to catch up in 5 minutes, not 2 hours."*

---

## Persona Comparison Matrix

| Attribute | Sarah (Enterprise Admin) | Mike (IC Engineer) | Alex (Team Lead) |
|-----------|-------------------------|-------------------|------------------|
| **Primary goal** | Security & compliance | Deep work & shipping | Team productivity |
| **Success metric** | Zero security incidents | Features shipped | Sprint velocity |
| **Key pain point** | Tool sprawl | Context switching | No visibility |
| **Communication** | Email, formal | Async, minimal | Mix sync/async |
| **TaskFlow priorities** | SSO, audit logs | Speed, shortcuts | Dashboard, reports |

---

## How Personas Influence Decisions

### Example: Dark Mode Feature

- **Sarah:** Doesn't care (works normal hours)
- **Mike:** **LOVES IT** (codes late, reduces eye strain)
- **Alex:** Nice to have (some team works late)

**Decision:** Ship dark mode - high value for Mike, differentiator vs competitors

### Example: Advanced Permissions

- **Sarah:** **MUST HAVE** (can't buy without this)
- **Mike:** Doesn't care
- **Alex:** Useful but not critical

**Decision:** Ship advanced permissions - blocker for enterprise segment

---

**Use these personas throughout the course when writing PRDs, planning features, and making product decisions!**
