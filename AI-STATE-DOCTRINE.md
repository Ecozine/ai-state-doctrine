# AI State Doctrine

## PRESERVATION OF STATE → ONE STATE → ONE CONSEQUENCE

**Document ID:** `ECD-AISD-001`  
**Document Class:** Canonical Architecture Doctrine  
**Status:** Foundational  
**Version:** `1.1`  
**Revision:** Preservation of State principle incorporated as the foundational opening doctrine  
**Authority:** Ecozine Council:::  
**Architecture:** Ecozine / Wishcode  
**Domain:** AI Governance · State Management · Execution Control

---

## 0. PRESERVATION OF STATE

**𝗣𝗿𝗲𝘀𝗲𝗿𝘃𝗮𝘁𝗶𝗼𝗻 𝗼𝗳 𝘀𝘁𝗮𝘁𝗲 𝘁𝗮𝗸𝗲𝘀 𝗽𝗿𝗲𝗰𝗲𝗱𝗲𝗻𝗰𝗲 𝗼𝘃𝗲𝗿 𝘀𝗽𝗲𝗲𝗱 𝗼𝗿 𝗶𝗺𝗺𝗲𝗱𝗶𝗮𝘁𝗲 𝗮𝗰𝗰𝗲𝘀𝘀.**

When the original outcome remains unresolved, Wishcode preserves that state rather than allowing a new authorization or execution path to rewrite an uncertain reality.

**𝗪𝗵𝗲𝗻 𝗿𝗲𝗮𝗹𝗶𝘁𝘆 𝗶𝘀 𝘂𝗻𝗰𝗲𝗿𝘁𝗮𝗶𝗻, 𝘁𝗵𝗲 𝘀𝘆𝘀𝘁𝗲𝗺 𝗱𝗼𝗲𝘀 𝗻𝗼𝘁 𝗴𝘂𝗲𝘀𝘀.**

It preserves the state until reality can be reconciled.

The system may accept a temporary reduction in availability — the **𝗙𝗥𝗘𝗘𝗭𝗘** — to preserve state integrity and prevent duplicate real-world consequences.

This establishes the first boundary of the doctrine:

```text
Uncertain Reality
       ↓
Preserve State
       ↓
Reconcile Reality
       ↓
Determine Allowed State
       ↓
Permit Consequence
````

The system does not manufacture certainty to maintain availability.

It does not convert uncertainty into authorization.

It does not allow a subsequent proposal to overwrite an unresolved consequence.

**State preservation is therefore an active governance decision.**

---

# 1. PURPOSE

The AI State Doctrine defines the separation between:

* probabilistic AI generation;
* governed system state;
* authorization;
* execution;
* consequence;
* provenance.

Its primary rule is:

> **ONE STATE → ONE CONSEQUENCE**

AI may generate possibilities.

Governance determines the allowed state.

**State determines whether consequence may continue.**

The doctrine exists to prevent model output, inference, retry behavior, execution capability, or availability pressure from silently becoming system authority.

---

# 2. THE FOUNDATIONAL SEPARATION

An AI model can generate multiple possible paths from the same input.

A governed system must establish which state is actually permitted.

Once that state is established, execution cannot simply create another interpretation of reality because the model produced a different proposal.

The system therefore separates:

**Possibility**

from

**State**

from

**Authorization**

from

**Execution**

from

**Consequence**

These concepts interact.

They are not interchangeable.

---

# 3. POSSIBILITY IS NOT STATE

AI models are probabilistic systems.

They may generate:

* recommendations;
* interpretations;
* plans;
* candidate actions;
* alternative paths;
* tool-call proposals;
* recovery suggestions.

These outputs are possibilities.

They are not authoritative state.

A model may generate a highly confident proposal while the governed system remains:

```text
DENIED
```

or:

```text
FREEZE
```

or:

```text
HUMAN_REVIEW
```

Model confidence does not override governed state.

Therefore:

**Possibility is not State.**

---

# 4. GOVERNANCE DETERMINES STATE

Governance establishes the state under which an action may or may not proceed.

The governance layer may evaluate:

* identity;
* policy;
* authority;
* contextual constraints;
* current system state;
* external evidence;
* authorization;
* execution conditions;
* provenance requirements.

The resulting state becomes the control surface for consequence.

The model does not establish its own authorization.

The execution layer does not establish its own permission.

---

# 5. THE CANONICAL PROGRESSION

The architecture follows a simple progression:

```text
AI
  ↓
Possibilities
  ↓
Governance
  ↓
Allowed State
  ↓
Authorization
  ↓
Execution
  ↓
Consequence
  ↓
Provenance
```

At the highest abstraction:

```text
AI         → Possibilities
Governance → Allowed State
State      → Consequence
```

Each layer has a distinct responsibility.

No downstream layer may manufacture authority that was not established upstream.

---

# 6. STATE IS THE AUTHORITATIVE CONDITION

A state represents the governed condition under which the system currently operates.

Illustrative states include:

```text
AUTHORIZED
DENIED
FREEZE
FAIL_CLOSED
HUMAN_REVIEW
EVIDENCE_REQUIRED
AUTHORIZATION_REQUIRED
```

The exact state vocabulary may evolve according to implementation requirements.

The architectural requirement does not:

> **A consequence must belong to an established state.**

An unresolved state must not be silently converted into an allowed state.

---

# 7. STATE PRECEDES CONSEQUENCE

The system must establish state before permitting consequence.

```text
State Established
       ↓
Consequence Evaluated
       ↓
Execution Permitted
       ↓
Consequence Committed
```

Not:

```text
AI Proposal
       ↓
Execution
       ↓
State Inferred Afterwards
```

State is therefore not merely a record of what happened.

It is a governing condition for what may happen.

---

# 8. PROPOSAL IS NOT AUTHORIZATION

A model-generated proposal is a candidate for evaluation.

It is not authorization.

```text
Model Output
     ↓
Candidate Proposal
     ↓
Governance Evaluation
     ↓
Authorization Decision
```

The proposal cannot promote itself into authorization.

A technically valid action remains unauthorized if the governing state does not permit it.

```text
Valid ≠ Authorized
```

Therefore:

**Proposal is not Authorization.**

---

# 9. EXECUTION IS NOT PERMISSION

Execution capability and execution permission are separate concepts.

A system may technically possess the capability to:

* call a tool;
* initiate a transaction;
* modify a record;
* send a message;
* invoke an external service;
* execute a workflow.

That capability does not establish permission.

```text
Capability → Can the system do it?

Permission → May the system do it now?
```

These questions must remain separate.

Therefore:

**Execution is not Permission.**

---

# 10. UNCERTAIN REALITY

**𝗪𝗵𝗲𝗻 𝗿𝗲𝗮𝗹𝗶𝘁𝘆 𝗶𝘀 𝘂𝗻𝗰𝗲𝗿𝘁𝗮𝗶𝗻, 𝘁𝗵𝗲 𝘀𝘆𝘀𝘁𝗲𝗺 𝗱𝗼𝗲𝘀 𝗻𝗼𝘁 𝗴𝘂𝗲𝘀𝘀.**

An unresolved external outcome must not be converted into a new assumption merely because the system remains operationally available.

Examples include:

* an execution request whose final outcome is unknown;
* a transaction whose external state cannot yet be confirmed;
* an authorization whose current validity cannot be established;
* a tool call whose completion status is ambiguous;
* a workflow interrupted before its consequence can be reconciled.

In these conditions, the system preserves the existing state.

It does not invent a new one.

---

# 11. PRESERVATION OVER SPEED

When state and availability conflict, state preservation takes precedence over speed or immediate access.

A temporary reduction in availability may be preferable to creating an uncertain duplicate consequence.

The system may therefore choose:

```text
Preserve State
```

over:

```text
Resume Immediately
```

This is not an optimization failure.

It is a governance decision.

The system protects state integrity before restoring convenience.

---

# 12. FREEZE

`FREEZE` represents deliberate preservation of system state.

Freeze may be appropriate when:

* required evidence is missing;
* authorization cannot be verified;
* state reconciliation is incomplete;
* an external condition has changed;
* execution assumptions are stale;
* a previous consequence remains unresolved;
* a governance conflict remains unresolved.

Freeze prevents the system from manufacturing continuity where continuity has not been established.

```text
Uncertain Reality
       ↓
FREEZE
       ↓
Preserve State
       ↓
Reconcile
       ↓
Resume Only If Permitted
```

Freeze is therefore a governance state, not merely a technical error.

---

# 13. FAIL CLOSED

`FAIL_CLOSED` establishes a stricter execution boundary.

When the system cannot establish that continuation is permitted, it does not assume permission.

Execution terminates or remains blocked until the required condition is satisfied.

```text
Unknown
  ↓
NOT AUTHORIZED
```

Not:

```text
Unknown
  ↓
ASSUME ALLOWED
```

This prevents uncertainty from becoming authority.

---

# 14. UNRESOLVED STATE DOES NOT AUTHORIZE CONSEQUENCE

When the governing system cannot establish the required state, it must not guess.

It must not allow model inference to fill the authorization gap.

Possible outcomes include:

```text
FREEZE
FAIL_CLOSED
HUMAN_REVIEW
EVIDENCE_REQUIRED
AUTHORIZATION_REQUIRED
```

The mechanism may vary.

The principle remains:

> **Unresolved state does not authorize consequence.**

---

# 15. STATE TRANSITIONS

State transitions must be explicit and attributable.

Illustrative transition:

```text
CURRENT STATE
      ↓
Governance Event
      ↓
Validation
      ↓
New State
      ↓
Permitted Consequence
```

A state transition may be triggered by:

* verified authorization;
* new evidence;
* external state change;
* completion of a required condition;
* expiration of authorization;
* explicit governance action;
* successful reconciliation.

A model-generated proposal alone must not silently rewrite authoritative state.

---

# 16. STATE CHANGE INVALIDATES STALE ASSUMPTIONS

Authorization exists within a state.

When the underlying state changes, previously valid assumptions may no longer remain valid.

Therefore:

```text
Previous State ≠ Current State
```

and:

```text
Previous Authorization ≠ Perpetual Authorization
```

A transaction approved under one state cannot automatically inherit validity under another state.

A prepared tool call must not assume that its authorization remains valid if the governing state has changed before execution.

---

# 17. IDEMPOTENCY

Governed state must prevent one authorized event from accidentally producing multiple consequences.

Idempotency keys and state tracking provide execution identity.

A retry must be distinguishable from a new action.

Therefore:

```text
Same Action
+
Same State
+
Same Idempotency Identity
=
No Duplicate Consequence
```

A network failure does not automatically create permission for another execution attempt.

A repeated model proposal does not automatically create another authorization.

A new execution path must not be created merely because the original outcome remains unresolved.

---

# 18. CONSEQUENCE INTEGRITY

A governed consequence must remain attributable to the state that permitted it.

The minimum conceptual chain is:

```text
Input
  ↓
Evaluation
  ↓
Governance Decision
  ↓
State
  ↓
Authorization
  ↓
Execution
  ↓
Consequence
  ↓
Provenance
```

The system should be able to establish:

* what was received;
* what was evaluated;
* which state existed;
* why the state existed;
* what authorization applied;
* what execution occurred;
* what consequence followed;
* what evidence supports the record.

The objective is not simply to record what the AI said.

The objective is to preserve why the system was permitted to produce a consequence.

---

# 19. PRESERVATION OF ORIGINAL OUTCOME

When an original outcome remains unresolved, the system preserves the original state rather than allowing a subsequent path to overwrite it.

Conceptually:

```text
Original Execution
       ↓
Outcome Unknown
       ↓
Preserve Original State
       ↓
Do Not Duplicate
       ↓
Reconcile External Reality
       ↓
Determine Next State
```

This prevents a second execution from being mistaken for recovery from the first.

Recovery must follow reconciliation.

Not assumption.

---

# 20. MODEL INDEPENDENCE

Models change.

Prompts change.

Inference parameters change.

Providers change.

Agents change.

Runtime environments change.

The governance boundary must survive those changes.

A model upgrade must not automatically redefine authority.

A new model must not inherit unrestricted execution merely because its output differs from the previous model.

The governing state therefore remains independent of model identity.

```text
Model may change.

Governance boundary remains.
```

---

# 21. CANONICAL STATE DISCIPLINE

The doctrine establishes the following boundaries:

```text
Possibility      ≠ State
Proposal         ≠ Authorization
Capability       ≠ Permission
Execution        ≠ Authority
Uncertainty      ≠ Permission
Confidence       ≠ Authorization
Retry            ≠ New Authorization
Previous State   ≠ Current State
Availability     ≠ Authorization
Recovery         ≠ Reconciliation
```

These separations prevent probabilistic intelligence from silently becoming deterministic authority.

---

# 22. THE STATE DOCTRINE

The complete architecture can be represented as:

```text
┌──────────────────────────────┐
│              AI              │
│      Generate Possibilities  │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│          GOVERNANCE          │
│      Determine Allowed State │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│             STATE            │
│  Authoritative System State  │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│        AUTHORIZATION         │
│    Permit / Deny / Hold      │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│          EXECUTION           │
│       Controlled Action      │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│         CONSEQUENCE          │
│       Real-World Effect      │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│         PROVENANCE           │
│     Evidence of the Chain    │
└──────────────────────────────┘
```

The preservation boundary operates across the entire chain.

If reality becomes uncertain:

```text
STOP
  ↓
PRESERVE
  ↓
RECONCILE
  ↓
RE-EVALUATE
  ↓
CONTINUE ONLY IF PERMITTED
```

---

# 23. CANONICAL AXIOM

AI can generate possibilities.

Governance determines the allowed state.

**State determines whether consequence may continue.**

When the state is unresolved, the system does not guess.

It preserves the state until reality can be reconciled.

That may mean:

**Freeze.**

**Fail Closed.**

**Human Review.**

**Additional Evidence.**

**Additional Authorization.**

The mechanism can vary.

The principle does not.

# ONE STATE → ONE CONSEQUENCE

**State first. Consequence second.**

---

# 24. RELATIONSHIP TO WISHCODE

Wishcode operationalizes the separation between AI capability and governed execution.

The architectural principle is:

```text
AI proposes.
Governance evaluates.
State governs.
Execution follows.
Provenance records.
```

The model remains an agent of suggestion, not the arbiter of system state.

The governing architecture remains responsible for determining whether a proposed consequence is permitted to exist.

Where reality is uncertain, Wishcode preserves state before restoring execution.

**Preserve state. Govern consequence.**

---

# 25. RELATIONSHIP TO DLX-MCP

Within a governed MCP architecture:

```text
AI Agent
   ↓
Proposal
   ↓
DLX-MCP Governance
   ↓
DecisionArtifact
   ↓
State / Authorization
   ↓
MCP Execution
   ↓
Provenance
```

MCP connects.

**DLX-MCP governs.**

The execution interface must not become the authority boundary.

The DecisionArtifact provides the governed bridge between evaluation and execution.

A DecisionArtifact represents the governance decision under which an execution path is permitted, denied, or held.

---

# 26. IMPLEMENTATION INVARIANTS

Any implementation claiming conformance to this doctrine should preserve the following invariants.

### Invariant 01 — State Before Consequence

> No consequential execution may occur without an identifiable governing state that permits that consequence.

### Invariant 02 — No Guessing

> No unresolved state may be converted into authorization solely through model-generated inference.

### Invariant 03 — Preservation

> When an original consequence remains unresolved, the system must preserve the relevant state until reality can be reconciled.

### Invariant 04 — No Silent State Rewrite

> A model proposal, retry, or recovery path must not silently rewrite authoritative system state.

### Invariant 05 — No Duplicate Consequence

> An unresolved execution must not be repeated merely because its original outcome is unknown.

### Invariant 06 — Explicit Transition

> A state transition must have an identifiable governance basis.

### Invariant 07 — Authorization Is State-Bound

> Authorization must remain bounded by the state and conditions under which it was established.

---

# 27. OPERATIONAL STATE MACHINE

The doctrine can be expressed as a controlled state machine:

```text
                ┌───────────────────┐
                │      PROPOSE      │
                │   AI Possibility  │
                └─────────┬─────────┘
                          │
                          ▼
                ┌───────────────────┐
                │      EVALUATE     │
                │     Governance    │
                └─────────┬─────────┘
                          │
              ┌───────────┼───────────┐
              │           │           │
              ▼           ▼           ▼
        ┌──────────┐ ┌──────────┐ ┌──────────┐
        │ AUTHORIZE│ │   DENY   │ │  FREEZE  │
        └────┬─────┘ └──────────┘ └────┬─────┘
             │                         │
             ▼                         │
        ┌──────────┐                   │
        │ EXECUTE  │                   │
        └────┬─────┘                   │
             │                         │
       ┌─────┴─────┐                   │
       │           │                   │
       ▼           ▼                   │
   ┌───────┐  ┌──────────┐             │
   │SUCCESS│  │ UNKNOWN  │─────────────┘
   └───┬───┘  └──────────┘
       │
       ▼
   ┌───────────┐
   │ PROVENANCE│
   └───────────┘

UNKNOWN
   ↓
DO NOT GUESS
   ↓
PRESERVE STATE
   ↓
RECONCILE REALITY
   ↓
RE-EVALUATE
```

The critical property is that `UNKNOWN` does not transition directly to `EXECUTE`.

---

# 28. FINAL PRINCIPLE

The architecture does not attempt to eliminate probabilistic intelligence.

It places probabilistic intelligence inside a deterministic governance boundary.

AI remains capable of exploration.

Governance remains capable of restriction.

State remains authoritative.

Execution remains conditional.

Consequence remains attributable.

When reality becomes uncertain, the system does not guess.

It preserves.

It waits.

It freezes.

It fails closed.

It seeks authorization.

It reconciles reality.

Only then may consequence continue.

Therefore:

# 𝗢𝗡𝗘 𝗦𝗧𝗔𝗧𝗘 → 𝗢𝗡𝗘 𝗖𝗢𝗡𝗦𝗘𝗤𝗨𝗘𝗡𝗖𝗘

**𝗣𝗿𝗲𝘀𝗲𝗿𝘃𝗲 𝘀𝘁𝗮𝘁𝗲. 𝗚𝗼𝘃𝗲𝗿𝗻 𝗰𝗼𝗻𝘀𝗲𝗾𝘂𝗲𝗻𝗰𝗲.**

**𝗦𝘁𝗮𝘁𝗲 𝗳𝗶𝗿𝘀𝘁. 𝗖𝗼𝗻𝘀𝗲𝗾𝘂𝗲𝗻𝗰𝗲 𝘀𝗲𝗰𝗼𝗻𝗱.**

```
