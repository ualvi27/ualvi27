# 👋 Hi, I'm **Umer Alvi** (@ualvi27)

**Founder & Solo Architect**  
Building enterprise AI infrastructure for construction, healthcare, and telecom.  
22+ years of Primavera P6, FIDIC Red Book, PMBOK expertise.  
**22+ years construction planning experience** → **AI/ML engineer** → **SaaS architect**  

---

## 🎯 What I'm Building

### **[PMC — Planning Management & Controls](https://pkailabs.io)**
A **schedule intelligence platform** solving the enterprise scheduling problems P6 doesn't:
- **Immutable version history** — every upload is a new version, one-click rollback to any prior state
- **Stateless CPM engine** — deterministic critical path, zero state drift
- **Full audit trail** — who changed what, and when; nothing hidden
- **Quality flag engine** — surfaces every assumption (calendar issues, dangling relationships, progress transparency)
- **Multi-tenant architecture** — no exclusive locks; teams collaborate, don't compete for access

**Status:** Beta (Phase 14 S4 complete: feedback system stabilized)  
**Next:** Phase 17 — Schedule Integrity & Confidence (3 health modules, version history UI)  
**Tech:** FastAPI + PostgreSQL + React + Qwen2.5 LLM agents (13 specialists on RTX 5060 Ti)

---

### **[VoipAI — AI Telephony System](https://pkailabs.io)**
Asterisk PBX + FastAPI + OpenAI TTS/STT + advanced call routing  
- **Status:** Production (recently resolved 24kHz/8kHz resampling with ffmpeg, AGI path mismatches, caller access control)
- **Current work:** Caller whitelisting + PIN fallback authentication
- **Tech:** Asterisk, Python FastAPI, OpenAI APIs, PostgreSQL, Redis

---

### **[AstroMed — Multi-Tenant Medical Practice Platform](https://pkailabs.io)**
Homoeopathic practice management + medical astrology integration  
- **Status:** MVP architecture complete (Keycloak realm, PostgreSQL multi-tenant, Docker Compose)
- **Tech:** FastAPI, React/Next.js, Keycloak, PostgreSQL, Homoeopathic database normalization

---

### **[PMC Frontend Overhaul — Tier-Based Theming](https://pkailabs.io)**
153 TSX components refactored with 4 tier-based themes:
- **Free/Obsidian+Sapphire** — dark, professional
- **Basic/Pearl+Onyx** — clean, minimal
- **Premium/Graphite+Teal** — premium, data-rich
- **Enterprise/Royal Onyx+Champagne** — executive dashboard

**Status:** 4 self-contained implementation prompts produced; awaiting frontend integration  
**Tech:** React, Tailwind CSS, design tokens, variable scoping

---

## 🚀 Recent Achievements (2026)

### **Market Research — Primavera P6 Pain Points**
Identified **8 enterprise scheduling pain areas** from 50+ sources:
1. ✅ Baseline Management → **PMC solves with immutable versions**
2. ✅ Import/Export Fidelity → **PMC solves with full validation**
3. ✅ Delay & Variance Tracking → **PMC solves with variance engine (Phase 14)**
4. ✅ Scheduling Options & Retained Logic → **PMC solves with transparent CPM**
5. ✅ Progress/Update Mechanics → **PMC solving with type transparency (Phase 17)**
6. ✅ **Calendars & Working Time** (HEAVIEST SIGNAL) → **PMC solves with auto-parsing + health checks**
7. ✅ Global Change Errors (No Undo) → **PMC solves with version rollback**
8. ✅ What-If Scenarios → **PMC Phase 17 (comparison), Phase 18 (simulator)**

**Result:** 88% of market pain addressed by PMC architecture (vs. 67% baseline)

---

## 📊 Architecture Principles

**Architecture > Features.** Every design decision driven by three hard constraints:

1. **Nothing is overwritten** — immutability, audit trail, accountability
2. **Stateless computation** — determinism, reproducibility, no drift
3. **No silent failures** — transparency, flagged assumptions, trust

This is why PMC beats "feature-rich" competitors — we solve the trust problem first.

---

## 💻 Technical Stack

| **Backend** | **Frontend** | **AI/ML** | **Infrastructure** |
|----------|-----------|----------|------------------|
| FastAPI | React/Next.js | Qwen2.5:14b-instruct (Ollama) | Oracle Linux 9 |
| PostgreSQL | Tailwind CSS | Claude API (planning) | i7-12700 CPU |
| Asyncpg (async DB) | ShadcN/UI | OpenAI TTS/STT | RTX 5060 Ti GPU 16GB |
| Alembic (migrations) | TypeScript | LangChain | Docker + Compose |
| FastAPI agents | Recharts | Continue IDE (local Qwen) | GitHub Copilot (single-file) |
| Keycloak SSO | MUI | Ollama (dual instance) | Deployment: self-hosted |

---

## 🔧 Developer Workflow (Locked In)

**Planning:** Claude (this conversation)  
**Code:** GitHub Copilot (single-file edits, localized changes)  
**Verification:** `docker exec grep` against built container files (mandatory before "live" claim)  
**Deployment:** Direct container build + verify pattern (no CI/CD, intentional)

**Philosophy:** Solo builder = no hand-offs = total accountability

---

## 🎓 Learning Goals (Active)

- ✅ Master Python coding fundamentals & best practices
- 🔄 **Generative AI:** LLM architecture, fine-tuning, prompt engineering, RAG pipelines
- 🔄 **Frameworks:** LangChain (deep), Transformers library, PyTorch, TensorFlow (on roadmap)
- 🔄 **Production ML:** Model serving, inference optimization, cost efficiency
- 🔄 **Enterprise Architecture:** Multi-tenancy, auth (Keycloak), compliance, audit trails

---

## 📈 Current Focus (June 2026)

### **Phase 17 Sprint** — Schedule Integrity & Confidence
- [x] Pre-work #C1: File hash dedup gate
- [x] Pre-work #C3: Calendar hours fix (lag_days /8.0 → lag_hr_cnt)
- [x] Pre-work #4: Percent-complete type capture
- [ ] **NEW:** Calendar 8.0 fallback quality flag (no silent assumptions)
- [ ] **Flagship:** Schedule Health Report (DCMA 27-check suite + 3 new modules)
  - [ ] Calendar Health Module (default-calendar detection, hours/day checks)
  - [ ] Progress Type Transparency (dur % vs physical % vs units %)
  - [ ] Relationship & Dangling Activity Module (OOS explanation)
- [ ] Version History Sidebar (every upload tracked, one-click rollback)
- [ ] Version Comparison UI (two-version side-by-side diff)

### **Phase 18 Parking Lot**
- Calendar-aware CPM dates (honors holidays, shifts, working-day gaps)
- What-if simulator (drag activity → watch ripple in real-time)

---

## 🌍 About PKAILabs

[**PKAILabs.io**](https://pkailabs.io) — Enterprise AI for Pakistan's Operating Industries

**Mission:** Build production-grade AI infrastructure for construction, healthcare, and telecom in emerging markets.

**Products:**
- **PMC** — AI-powered schedule intelligence (construction)
- **VoipAI** — Intelligent telephony system (telecom)
- **AstroMed** — Multi-tenant medical practice + astrology (healthcare)
- **Chat.pkailabs.io** — CRAG-powered HR chatbot (multi-tenant)

**Approach:** Founder-built, production-first, no VC pressure. Ship → Learn → Compound.

---

## 🎯 What I'm Looking For

**Collaboration:**
- AI model development (fine-tuning, specialized agents, RAG pipelines)
- Enterprise architecture feedback (multi-tenancy, auth, audit trails)
- Construction tech partnerships (schedule intelligence, project controls)
- AI safety & alignment (responsible model development)

**Ideal collaborators:**
- Engineers shipping real products (not prototypes)
- Deep understanding of enterprise constraints
- Commitment to user trust over feature velocity
- 22+ years of domain expertise OR fresh perspective on core problems

**Not interested in:** VC-driven feature races, hype-driven pivots, "move fast and break things" (enterprises need reliability)

---

## 📫 How to Reach Me

- **Email:** [ualvi27@gmail.com](mailto:ualvi27@gmail.com)
- **GitHub:** [@ualvi27](https://github.com/ualvi27)
- **PKAILabs:** [pkailabs.io](https://pkailabs.io)
- **LinkedIn:** [Umer Alvi](https://linkedin.com/in/umeralvi)
- **Twitter/X:** [@ualvi27](https://x.com/ualvi27)

---

## 😄 Pronouns & Philosophy

**Let's Make the Impossible → Possible**

- Solo founder doesn't mean solo thinker
- Architecture compounds; features fade
- Trust earned through transparency
- Shipping beats talking
- When your code doesn't run → review and run again; it works

---

## ⚡ Fun Facts

1. **22 years → AI pivot:** Construction scheduling to AI/ML engineer (not a typical arc, but it compounds)
2. **Solo builder:** PMC architected and shipped by one person; intentional, not a constraint
3. **Dual Ollama instances:** RTX 5060 Ti can run two 14B models simultaneously (not many know this)
4. **When code breaks:** Review the architecture, not the syntax. 90% of failures are design decisions, not typos
5. **Immutability is underrated:** Most companies optimize for speed; I optimize for trust

---

## 🚀 What's Next

- **Phase 17 (July 2026):** Schedule Integrity Report + Version History
- **Phase 18 (Q3 2026):** Calendar-aware CPM + What-if Simulator
- **VoipAI Production (July 2026):** Caller access control + advanced routing
- **AstroMed MVP (August 2026):** Medical astrology integration + homoeopathic database

---

## 📊 Repositories Worth Visiting

- **[pkailabs-pmc](https://github.com/ualvi27/pkailabs-pmc)** — Schedule intelligence backend (FastAPI + CPM engine)
- **[pmc-frontend](https://github.com/ualvi27/pmc-frontend)** — 153 TSX components (React + design system)
- **[voipai-asterisk](https://github.com/ualvi27/voipai-asterisk)** — Asterisk + FastAPI telephony
- **[astromed-backend](https://github.com/ualvi27/astromed-backend)** — Multi-tenant medical platform

---

**Thanks for visiting. If you're building something real, let's talk. 🚀**
