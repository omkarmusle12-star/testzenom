# Zenom

### When harassment becomes a pattern, Zenom turns the fragments into a record.

**Zenom is a privacy-first incident documentation and safety platform designed to help people organize harassment and stalking evidence, reconstruct what happened, understand their options, and prepare a structured case record — without taking control away from the person experiencing it.**

> The problem isn't that harassment leaves no evidence.  
> **The problem is that the evidence is everywhere.**

---

## The Problem

Harassment rarely happens in one place.

A single situation can involve:

- WhatsApp messages
- Instagram conversations
- Phone calls
- SMS
- Emails
- Screenshots
- Photos
- Screen recordings
- Audio recordings
- Social media accounts
- Phone numbers
- URLs
- Location information
- Notes and memories of incidents

The evidence exists.

But it is fragmented.

A person may have hundreds of screenshots, several blocked accounts, multiple phone numbers, call logs, recordings, and conversations spread across different platforms.

The result is a difficult and exhausting process:

```text
Fragmented Evidence
        ↓
Manual Searching
        ↓
Missing Context
        ↓
Unclear Timeline
        ↓
Invisible Patterns
        ↓
Difficult Reporting
```

Zenom exists to solve the layer **between scattered evidence and informed action.**

---

# What is Zenom?

Zenom is an **incident documentation and case intelligence platform**.

It helps transform scattered records into a structured case:

```text
Evidence
   ↓
Incidents
   ↓
Timeline
   ↓
Entities & Relationships
   ↓
Patterns
   ↓
Case Record
   ↓
User-Reviewed Actions
```

Zenom does not replace:

- Police
- Cybercrime authorities
- Lawyers
- Advocates
- Emergency services
- Social platforms

Instead, it helps a person arrive at those systems with a **clearer, better-organized record of what happened.**

---

# Core Product

## 01 — Evidence Vault

Securely collect records from different sources in one case.

Supported evidence can include:

- Images
- Screenshots
- Videos
- Audio recordings
- Screen recordings
- Documents
- Emails
- Chat exports
- Call logs
- URLs
- Notes
- Other relevant files

Every original artifact remains preserved.

AI-generated information such as OCR, transcription, summaries, or extracted entities is treated as **derived information — never as a replacement for the original evidence.**

---

## 02 — Incident Timeline

Turn individual records into a chronological story.

Instead of searching through hundreds of files:

```text
12 Aug
Instagram message
        ↓
14 Aug
Unknown number calls
        ↓
15 Aug
New account contacts user
        ↓
17 Aug
Repeated messages
        ↓
19 Aug
Account blocked
        ↓
21 Aug
Another account appears
```

Zenom can help reconstruct this timeline while keeping the underlying evidence attached to every event.

The user remains the final authority over what actually happened.

---

## 03 — Entity & Pattern Detection

Harassment can span multiple accounts and channels.

Zenom can surface potentially related:

- Phone numbers
- Usernames
- Social accounts
- Email addresses
- URLs
- Dates
- Locations
- Names
- Repeated phrases
- Contact patterns

These relationships can be represented as an incident graph:

```text
                 ┌──────────────┐
                 │   Incident   │
                 └──────┬───────┘
                        │
          ┌─────────────┼─────────────┐
          ↓             ↓             ↓
      Phone #1      Instagram      Account #2
          │             │             │
          └─────────────┼─────────────┘
                        ↓
                  Possible Pattern
```

### Important

Zenom does **not** determine that two accounts belong to the same person.

It can identify a potentially relevant relationship and explain **why the relationship was surfaced**.

The distinction matters.

---

# 04 — Evidence Completeness

Having evidence is not the same as having a usable record.

Zenom can identify potential gaps such as:

- Missing timestamps
- Unlinked evidence
- Unresolved incidents
- Duplicate files
- Missing context
- Events without supporting evidence
- Evidence that may need additional documentation

The goal is not to produce a meaningless "legal score."

Instead:

> **Zenom helps the user understand what is documented, what is uncertain, and what may still need attention.**

---

# 05 — Legal Navigator

Legal information is often difficult to navigate.

Zenom can provide a structured interface for understanding relevant laws and official sources in plain language.

For example:

```text
Your documented situation
          ↓
Potentially relevant legal concepts
          ↓
Official source
          ↓
Plain-language explanation
          ↓
What the provision generally covers
          ↓
Possible next steps
```

Legal information should always be:

- Source-backed
- Jurisdiction-aware
- Clearly separated from legal advice
- Linked to the original authoritative source

Zenom does not decide whether a crime occurred.

---

# 06 — Complaint Builder

Once a case has been documented, creating a complaint can become repetitive and overwhelming.

Zenom can transform the case record into a structured draft containing:

### Incident Summary

What the user reports happened.

### Chronology

A chronological list of documented incidents.

### Evidence Index

A structured list of supporting evidence.

### Identifiers

Relevant phone numbers, usernames, URLs, accounts, and other entities.

### Supporting Files

Evidence selected by the user.

### User Statement

A clear, editable description of the situation.

The generated complaint is always **review-first**.

```text
Zenom generates draft
        ↓
User reviews
        ↓
User edits
        ↓
User chooses evidence
        ↓
User explicitly authorizes sharing
        ↓
Submission / export
```

Zenom never silently submits a complaint.

---

# 07 — Trusted Circle

People often need support before they are ready to report something formally.

Zenom can allow users to create a trusted circle with granular permissions.

For example:

```text
Trusted Person A
├── Safety status       ✓
├── Current location    ✓
├── Case summary        ✗
└── Evidence            ✗

Trusted Person B
├── Safety status       ✓
├── Case summary        ✓
├── Selected incidents  ✓
└── Evidence            ✓
```

Sharing is explicit.

Permissions can be revoked.

Access should be auditable.

---

# The Zenom Intelligence Layer

AI is not the product.

**The case record is the product.**

AI exists to reduce the work required to create and understand that record.

### AI can help with:

- OCR
- Transcription
- Evidence classification
- Metadata extraction
- Entity extraction
- Timeline suggestions
- Duplicate detection
- Pattern discovery
- Evidence linking
- Case summarization
- Evidence-gap identification
- Legal-source retrieval
- Complaint drafting

### AI cannot independently:

- Determine that someone is guilty
- Identify an alleged offender with certainty
- Decide that a crime occurred
- Contact police
- Submit a complaint
- Share private evidence
- Escalate an incident
- Make emergency decisions on behalf of the user

**Human control is a core product requirement, not an optional feature.**

---

# Evidence Integrity

Zenom should never modify the original evidence artifact.

For every imported file, the system can maintain integrity metadata such as:

```text
Original File
      │
      ├── Object Reference
      ├── SHA-256 Hash
      ├── File Size
      ├── MIME Type
      ├── Import Timestamp
      └── Available Metadata
```

AI processing creates separate derived artifacts:

```text
Original Evidence
       │
       ├── OCR
       ├── Transcription
       ├── Extracted Entities
       ├── Suggested Timeline Event
       └── AI Summary
```

Derived information never silently overwrites the source.

> Zenom does not claim to make evidence "court-admissible."  
> It aims to preserve, organize, and make the record more auditable and usable.

---

# Privacy & Security

Zenom deals with some of the most sensitive information a person can possess.

That makes privacy a foundational requirement.

### Security principles

- Encryption in transit
- Encryption at rest
- Strong authentication
- Least-privilege access
- Explicit sharing permissions
- Access audit logs
- Controlled exports
- Evidence retention controls
- Evidence deletion controls
- No public evidence URLs
- Secure object storage
- Separation of original and derived data
- No use of private evidence for model training by default
- Protection against unauthorized device/account access

### Threat model

Zenom must consider not only external attackers.

It must also consider scenarios such as:

- An abusive person accessing the victim's device
- A compromised account
- Shared devices
- Stolen sessions
- Unauthorized evidence sharing
- Malicious links or uploaded files
- Insider access
- Metadata leakage
- Accidental exports

Security is therefore part of the architecture from day one.

---

# Product Architecture

```text
                         ┌─────────────────────┐
                         │       ZENOM         │
                         │     Web Client      │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │      API Layer      │
                         └──────────┬──────────┘
                                    │
             ┌──────────────────────┼──────────────────────┐
             │                      │                      │
             ▼                      ▼                      ▼
      ┌─────────────┐       ┌─────────────┐       ┌─────────────┐
      │   Evidence  │       │  Incident   │       │   Identity  │
      │   Service   │       │   Service   │       │  & Access   │
      └──────┬──────┘       └──────┬──────┘       └─────────────┘
             │                     │
             └──────────┬──────────┘
                        ▼
                ┌───────────────┐
                │ Incident Graph│
                └───────┬───────┘
                        │
              ┌─────────┴─────────┐
              ▼                   ▼
       ┌──────────────┐    ┌──────────────┐
       │ Intelligence │    │ Legal /      │
       │ Layer        │    │ Sources      │
       └──────┬───────┘    └──────┬───────┘
              │                   │
              └─────────┬─────────┘
                        ▼
                ┌───────────────┐
                │ Case Builder  │
                └───────┬───────┘
                        │
           ┌────────────┼────────────┐
           ▼            ▼            ▼
       Export       Reporting    Trusted
        Case        Workflow     Circle
```

---

# Planned Technology Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js / React |
| API | FastAPI |
| Database | PostgreSQL |
| Object Storage | S3-compatible storage |
| Background Jobs | Redis + Worker |
| Search | PostgreSQL initially |
| AI | Interchangeable model layer |
| Authentication | Secure managed authentication |
| Deployment | Cloud infrastructure |

The architecture is intentionally modular.

The goal is to avoid coupling the product to one AI provider.

---

# Data Model

The core domain revolves around a small number of important objects:

```text
Case
 ├── Incidents
 │     ├── Evidence
 │     ├── Entities
 │     └── Relationships
 │
 ├── Evidence
 │
 ├── Timeline
 │
 ├── Actions
 │
 └── Sharing / Audit History
```

### Core entities

**Case**

The container for a user's documented situation.

**Incident**

A specific event or reported occurrence.

**Evidence**

An original supporting artifact.

**Entity**

A person/account/phone number/email/URL/etc. extracted or manually added to the case.

**Relationship**

A potentially meaningful connection between entities or incidents.

**Action**

A user-authorized action such as export, sharing, or reporting.

---

# Development Roadmap

Zenom is being developed in stages.

### Phase 0 — Product & Safety Foundation

- Threat model
- Abuse cases
- Privacy model
- Evidence model
- Legal-source requirements
- Retention strategy
- User flows
- Safety boundaries

### Phase 1 — Evidence Foundation

- Authentication
- Case creation
- Evidence upload
- Secure storage
- Metadata
- Hashing
- Evidence viewer

**No AI initially.**

### Phase 2 — Incident System

- Incidents
- Timeline
- Evidence ↔ incident relationships
- People/accounts/entities
- Notes
- Search
- Filtering

### Phase 3 — Intelligence

- OCR
- Transcription
- Entity extraction
- Classification
- Duplicate detection
- Timeline suggestions
- Pattern detection

### Phase 4 — Case Intelligence

- Evidence completeness
- Pattern summaries
- Incident relationships
- Case overview
- Missing-information suggestions
- Documentation guidance

### Phase 5 — Legal Navigator

- Official legal sources
- Provision database
- Plain-language explanations
- Source citations
- Jurisdiction awareness

### Phase 6 — Complaint Builder

- Complaint drafting
- Evidence index
- Case summary
- PDF export
- Attachment packaging
- Review workflow

### Phase 7 — Trusted Circle

- Trusted contacts
- Granular permissions
- Selective sharing
- Case sharing
- Access logs
- Revocation

### Phase 8 — Reporting Integrations

- Official cybercrime workflows
- Verified authority directory
- Reporting assistance
- Email workflows
- Platform reporting assistance
- Future official APIs where available

---

# MVP

The first meaningful version of Zenom is intentionally narrow.

```text
┌───────────┐
│  Evidence │
└─────┬─────┘
      ↓
┌───────────┐
│ Incident  │
└─────┬─────┘
      ↓
┌───────────┐
│ Timeline  │
└─────┬─────┘
      ↓
┌───────────┐
│  Pattern  │
└─────┬─────┘
      ↓
┌───────────┐
│ Case      │
│ Export    │
└───────────┘
```

Everything else builds on this foundation.

---

# What Zenom Is Not

Zenom is deliberately **not**:

- Another AI chatbot
- Another generic RAG application
- A WhatsApp replacement
- An emergency-service replacement
- A police replacement
- A lawyer replacement
- An automated accusation engine
- A facial-recognition system for identifying suspects
- A surveillance platform
- An automatic police-reporting bot
- A system that secretly tracks people
- A system that decides when someone is guilty

The goal is not maximum automation.

The goal is **maximum usefulness without taking away human control.**

---

# Design Philosophy

### 01 — Evidence before intelligence

Build the evidence foundation before adding AI.

### 02 — Originals before summaries

Never allow an AI summary to become the source of truth.

### 03 — Facts ≠ inference

Clearly distinguish:

```text
User statement
      ≠
Extracted fact
      ≠
AI inference
      ≠
Unresolved possibility
```

### 04 — User-controlled actions

High-impact actions require explicit authorization.

### 05 — Explainability

When Zenom surfaces a pattern, the user should be able to understand **why** it was surfaced.

### 06 — Privacy by architecture

Sensitive information should not become an afterthought.

### 07 — No false certainty

When the system does not know, it should say so.

---

# Repository Structure

```text
Zenom/
│
├── apps/
│   ├── web/                  # Web application
│   └── api/                  # Backend API
│
├── packages/
│   ├── domain/               # Core domain models
│   ├── evidence/             # Evidence processing
│   ├── timeline/             # Timeline / incident logic
│   ├── graph/                # Entity & relationship graph
│   └── legal/                # Legal source layer
│
├── docs/
│   ├── product/              # Product specifications
│   ├── architecture/         # Architecture decisions
│   ├── security/             # Threat model & security docs
│   └── decisions/            # ADRs
│
├── tests/
│
├── .github/
│   └── ...
│
├── CONTRIBUTING.md
├── SECURITY.md
└── README.md
```

---

# Project Status

🚧 **Early development / architecture phase**

The product architecture, safety boundaries, domain model, and development roadmap are being defined before implementation.

This project is intentionally being built incrementally.

**Current focus:**

> Product definition → Security model → Evidence foundation → Incident system → Intelligence

---

# Responsible Use

Zenom is intended to help users document and organize information about situations they personally experience.

It should not be used to:

- Harass another person
- Track people without consent
- Collect private information unlawfully
- Manufacture evidence
- Fabricate allegations
- Impersonate authorities
- Automatically identify or expose private individuals
- Conduct unauthorized surveillance

Users are responsible for the information they upload and the actions they take.

---

# Disclaimer

Zenom is a technology project for documentation, organization, and information assistance.

It does not provide legal advice, determine criminal liability, guarantee evidence admissibility, or replace law enforcement, lawyers, advocates, emergency services, or professional support.

For situations involving immediate danger, users should contact appropriate emergency or local support services.

---

# Contributing

Zenom is being built with a strong emphasis on:

- Privacy
- Security
- Responsible AI
- Human control
- Evidence integrity
- Explainability
- Accessibility

Contributions, security research, architectural discussion, and thoughtful criticism are welcome.

Before contributing, please read the project documentation and security guidelines.

---

# Security

If you discover a security vulnerability, please **do not open a public issue containing sensitive details**.

See [`SECURITY.md`](SECURITY.md) for responsible disclosure instructions.

---

# Vision

Most systems are designed around the platform where an incident happens.

WhatsApp owns the messages.

Instagram owns the conversations.

The phone owns the call logs.

Email owns the emails.

Cloud storage owns the files.

But **the person experiencing the situation owns the story.**

Zenom is designed to become the layer that brings those fragments together.

Not to decide what happened.

Not to decide who is guilty.

Not to decide what the person should do.

But to help transform:

```text
                    Fragments
                       ↓
                  Documentation
                       ↓
                    Context
                       ↓
                    Pattern
                       ↓
                 Understanding
                       ↓
                  User Choice
```

**Zenom — turn the fragments into a record.**

---

## License

License information will be added as the project reaches its public development stage.Privacy-first incident documentation and safety platform that helps people organize harassment evidence, reconstruct incident timelines, identify patterns, understand relevant legal information, and take informed action.
