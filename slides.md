---
theme: default
title: UTM Web & Digital Services Unit
info: Proposed organizational structure for end-to-end university web and digital services
author: UTM Web & Digital Communication
colorSchema: light
class: text-left
mdc: true
---

<style>
:root {
  --slidev-theme-primary: #5c001f;
}

.slidev-layout h1 {
  color: #0f172a;
  letter-spacing: -0.02em;
}

.slidev-layout h2 {
  color: #5c001f;
}

.muted {
  color: #64748b;
}

.tag {
  display: inline-block;
  padding: 0.25rem 0.65rem;
  border-radius: 999px;
  background: #ffffab;
  color: #5c001f;
  font-size: 0.78em;
  font-weight: 600;
}

.org-head {
  width: fit-content;
  margin: 0.8rem auto 0.45rem;
  padding: 0.55rem 1.4rem;
  border-radius: 0.7rem;
  background: #5c001f;
  color: white;
  font-weight: 700;
  font-size: 1.05em;
}

.org-grid, .staffing-grid {
  display: grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: 0.65rem;
  margin-top: 1rem;
}

.org-card, .staffing-card {
  border: 1px solid #cbd5e1;
  border-top: 5px solid #5c001f;
  border-radius: 0.65rem;
  padding: 0.75rem;
  background: #f8fafc;
  min-height: 7.4rem;
}

.org-card strong {
  display: block;
  color: #0f172a;
  font-size: 0.8em;
  line-height: 1.15;
  margin-bottom: 0.45rem;
}

.org-card span {
  display: block;
  color: #475569;
  font-size: 0.62em;
  line-height: 1.35;
}

.org-card:nth-child(2) { border-top-color: #f8be17; }
.org-card:nth-child(3) { border-top-color: #c2410c; }
.org-card:nth-child(4) { border-top-color: #64748b; }
.org-card:nth-child(5) { border-top-color: #5c001f; }

.staffing-card {
  min-height: 9rem;
  border-top-color: #94a3b8;
}

.staffing-card.recommended {
  border: 2px solid #5c001f;
  border-top: 7px solid #5c001f;
  background: #fffde8;
  transform: translateY(-0.25rem);
}

.staffing-card h3 {
  margin: 0;
  color: #0f172a;
  font-size: 1em;
}

.staffing-card .headcount {
  color: #5c001f;
  font-size: 1.55em;
  font-weight: 800;
}

.staffing-card p {
  margin: 0.35rem 0 0;
  color: #475569;
  font-size: 0.7em;
  line-height: 1.3;
}

.slidev-layout::after {
  content: '';
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  height: 0.35rem;
  background: linear-gradient(90deg, #5c001f 0 62%, #f8be17 62% 84%, #ffffab 84% 100%);
}
</style>

---
layout: center
class: text-center
---

# UTM Web & Digital Services Unit

## A multidisciplinary operating model for the university web ecosystem

<div class="tag mb-5">UTM WEB &amp; DIGITAL COMMUNICATION</div>

<div class="mt-4 muted">Working proposal for management discussion · November 2026</div>

::: notes
This is a working proposal. The objective is to define the functions required to operate university web services end to end, not to prescribe an immediate headcount.
:::

---

# The management decision

UTM’s web function now supports public-facing services, internal workflows, data collection, campaigns, and digital transformation. It should be structured as a digital service capability, not treated as a single webmaster role.

The proposed model protects distinct capabilities for:

- Platform operations
- Software and AI engineering
- Digital experience
- Data and digital intelligence
- Governance and service delivery

::: notes
The proposal separates functional responsibilities from individual posts. One officer may cover several functions initially, but the functions still need to be visible and governed.
:::

---

layout: two-cols
---

# Why the operating model must evolve

- More websites, applications, integrations, and data sources to operate
- Higher expectations for availability, speed, security, accessibility, and measurable impact
- Growing use of analytics, automation, AI, and digital campaigns
- Operational knowledge concentrated in too few individuals
- Technical consequences considered too late in requirements and procurement

::right::

![](/images/web-unit-placeholder.svg)

<div class="text-sm muted mt-3">The web unit is already operating across multiple professional disciplines.</div>

---

# The actual scope is broader than website development

| Capability | Examples of work |
| --- | --- |
| Platform engineering | Docker, NGINX, PHP-FPM, Redis, backups, monitoring |
| Web and application engineering | WordPress, plugins, APIs, SSO, dashboards, integrations |
| Security and reliability | Hardening, patching, incident response, disaster recovery |
| Digital experience | UX, accessibility, branding implementation, SEO, content journeys |
| Data and intelligence | Web analytics, marketing analytics, search visibility, reporting |
| Automation and AI | Chatbots, agents, workflow automation, content intelligence |
| Governance | PTJ coordination, standards, audits, documentation, training |

::: notes
This inventory can later be converted into a workload and competency assessment. It is evidence that the current scope already crosses conventional job boundaries.
:::

---

# Proposed operating model

```mermaid
flowchart LR
  A[Strategy and priorities] --> B[Design and requirements]
  B --> C[Build and integrate]
  C --> D[Deploy and operate]
  D --> E[Measure and improve]
  E --> A
```

The unit should own the complete service lifecycle:

**Strategy → Design → Development → Deployment → Security → Operations → Analytics → Optimization**

---
class: org-structure
---

# Proposed organization structure

<div class="org-head">Head of Web &amp; Digital Services</div>

<div class="org-grid">
  <div class="org-card">
    <strong>Platform Engineering<br/>and DevOps</strong>
    <span>DevOps / SRE</span>
    <span>Infrastructure</span>
    <span>Security &amp; reliability</span>
  </div>
  <div class="org-card">
    <strong>Web Applications<br/>and AI Engineering</strong>
    <span>Website / CMS</span>
    <span>Web applications</span>
    <span>Integrations · AI</span>
  </div>
  <div class="org-card">
    <strong>Digital Experience<br/>and Marketing</strong>
    <span>UX / UI</span>
    <span>Accessibility</span>
    <span>SEO · campaigns</span>
  </div>
  <div class="org-card">
    <strong>Data &amp; Digital<br/>Intelligence</strong>
    <span>Web analytics</span>
    <span>Marketing analytics</span>
    <span>BI · data engineering</span>
  </div>
  <div class="org-card">
    <strong>Governance &amp;<br/>Service Delivery</strong>
    <span>Business analysis</span>
    <span>PTJ coordination</span>
    <span>Standards · training</span>
  </div>
</div>

<div class="mt-5 text-sm muted">Functional domains define the capabilities that must be covered; they do not require five separate departments or one permanent post for every role.</div>

---

layout: two-cols
---

# Functional roles inside the unit

### Platform Engineering and DevOps
- DevOps / SRE
- Infrastructure and runtime reliability
- Security implementation and incident readiness

### Web Applications and AI Engineering
- Website and CMS engineering
- Web applications and integrations
- AI, chatbot, and workflow automation

### Digital Experience and Marketing
- UX/UI and accessibility
- SEO and digital marketing
- Content and conversion experience

::right::

### Data and Digital Intelligence
- Web and marketing analytics
- BI, data engineering, and dashboards
- Search visibility and impact measurement

### Governance and Service Delivery
- Business analysis and PMO
- PTJ coordination and service standards
- Documentation, training, and acceptance

::: notes
Security is a cross-cutting responsibility. The Web Unit implements web and application controls while the central ICT security function retains university-wide authority.
:::

---

# Web analytics belongs with digital intelligence

| Discipline | Core question |
| --- | --- |
| Web analytics | Is the website performing effectively? |
| Marketing analytics | Are campaigns reaching and influencing the intended audience? |
| Digital intelligence | What should UTM decide or improve based on the evidence? |

The unit should own instrumentation, data quality, technical analysis, dashboards, and reporting infrastructure.

Corporate Communication and PTJs should continue to own communication objectives, editorial decisions, and campaign priorities.

---

layout: image
image: /images/web-unit-placeholder.svg
---

# A service, not a collection of websites

::: notes
Use this as a visual pause before discussing the staffing model. Replace the placeholder visual with an approved UTM diagram or photograph later.
:::

---

# Practical staffing model

<div class="staffing-grid">
  <div class="staffing-card">
    <h3>Lean</h3>
    <div class="headcount">6</div>
    <p>Core staff plus shared specialists. Protect essential operations and reduce single-person dependency.</p>
  </div>
  <div class="staffing-card recommended">
    <h3>Recommended</h3>
    <div class="headcount">10</div>
    <p>Separate platform, engineering, experience, intelligence, and governance capabilities.</p>
  </div>
  <div class="staffing-card">
    <h3>Mature</h3>
    <div class="headcount">16</div>
    <p>Five domains with enough depth for university-wide scale, resilience, and continuous improvement.</p>
  </div>
</div>

The recommended model is a planning target, not an immediate establishment request.

Before requesting posts, measure:

- Number and criticality of services
- Technical complexity and operational load
- Coverage required outside office hours
- Security and compliance exposure
- Dependency on individual officers

---

layout: two-cols
---

# Recommended initial model: 10 core staff

### Core establishment

1. Head / Web and Digital Service Owner
2. DevOps / SRE and Infrastructure Engineer
3. Security and Reliability Engineer
4. Website and CMS Engineer
5. Web Applications and Integration Engineer

::right::

6. AI and Automation Engineer
7. UX/UI and Accessibility Officer
8. SEO and Digital Marketing Officer
9. Web and Marketing Analytics Officer
10. BI and Data Engineer

Governance, PMO, and PTJ coordination are led by the service owner and supported by designated PTJ coordinators until workload evidence justifies a dedicated business-analysis / service-delivery post. Creative production, advanced security, legal, procurement, and university-wide ICT authority remain shared or centrally coordinated where appropriate.

---

# Why this matters for Skim F

Modern technical services require recognized specializations beyond generic support or application development.

| Emerging specialization | Typical responsibility |
| --- | --- |
| Platform engineering | Cloud, containers, deployment, observability, resilience |
| Software engineering | CMS, applications, APIs, testing, architecture |
| Security engineering | Hardening, vulnerability management, incident response |
| Data engineering and BI | Instrumentation, pipelines, dashboards, data quality |
| AI engineering | Models, agents, integrations, evaluation, governance |
| Technical business analysis | Requirements, service design, feasibility, benefits |

The establishment should recognize the work actually required to operate a modern digital university.

---

# Clear boundaries prevent scope expansion

| Area | Primary responsibility |
| --- | --- |
| University websites and web applications | Web and Digital Services Unit |
| Web hosting platform and deployment | Web Unit, coordinated with central ICT |
| University-wide network and data centre | UTMDX / central ICT |
| University-wide security authority | Central ICT security function |
| Web security implementation | Web Unit |
| Official branding and editorial approval | Corporate Communication / PTJ |
| PTJ website content ownership | Respective PTJ |

---

# Proposed implementation path

```mermaid
timeline
    title From current duties to a sustainable service
    2026 Q4 : Inventory services and workloads
           : Confirm ownership and operating boundaries
    2027 Q1 : Establish functional leads
           : Standardize monitoring, backup, deployment, and documentation
    2027 Q2 : Formalize competency and staffing proposal
           : Introduce service reporting and improvement cycles
```

The first deliverable should be an evidence-based role-to-workload map.

---

layout: center
class: text-center
---

# Proposed decision

Recognize UTM web management as an end-to-end digital service function with:

- Five protected capability domains
- Clear boundaries with central ICT and Corporate Communication
- A workload-based staffing assessment
- A structured technical career and competency pathway
- Shared accountability for reliability, security, experience, and impact

<div class="mt-8 tag">Next: validate the model with current service and workload evidence</div>

::: notes
The next working session should refine the organizational chart and map each current responsibility to a proposed function, estimated effort, risk, and required competency.
:::
