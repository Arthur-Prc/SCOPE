# SOC 2 Assessment Framework 🧠

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/b32370ec-ebe0-491a-ae14-b797e694219f" />


A practical framework for analyzing SOC 2 readiness findings, controls, evidence, risks, and remediation.

---

## 🧠 Pre-Answer Framework: SCOPE+

Before answering any SOC 2 assessment question, run this framework quickly.

### S — Scope

**What exactly are we assessing?**

Define:

- Systems
- Assets
- Teams
- Processes
- Data
- Time period
- Applicable criteria

Don't assume the entire company, system, or environment is in scope.

---

### C — Cause & Risk

**What could go wrong, and why does it matter?**

Identify:

- Threat or failure scenario
- Potential impact
- Exposure
- Likelihood
- Business/compliance consequences

Don't confuse a technical issue with the actual business risk.

> Technical problem ≠ Risk

---

### O — Observe the Control

**What control actually exists?**

Separate:

- Policy
- Process
- Control
- Tool
- Implementation
- Exception

Ask:

> What is the organization actually doing to mitigate this risk?

Don't invent a control and don't prescribe a technical solution before understanding the existing environment.

---

### P — Proof

**What evidence demonstrates that the control exists and/or operated?**

Evaluate:

- Relevance
- Completeness
- Reliability
- Timeliness
- Source
- Period covered
- Whether the evidence is independently verifiable

Examples:

- System-generated logs
- Access reports
- Configuration exports
- Tickets
- Screenshots
- Spreadsheets
- Management representations

Remember:

> Missing evidence ≠ proof that the activity never happened.

And:

> Management representation ≠ sufficient evidence by itself.

---

### E — Effectiveness

Evaluate the control from two perspectives:

#### Design Effectiveness

> If this control operates as designed, would it adequately address the identified risk?

#### Operating Effectiveness

> Did the control actually operate consistently and produce the intended result during the relevant period?

Don't automatically classify missing evidence as a failed control.

Possible conclusions:

- Effective
- Ineffective
- Appears Adequate
- Needs Investigation
- Potential Gap

---

### + — Traceability

**Can I prove where my conclusion came from?**

Every important conclusion should be traceable:

```text
Risk
  ↓
Control
  ↓
Evidence
  ↓
Observation
  ↓
Conclusion
