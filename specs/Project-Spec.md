# [PROJECT NAME] Specification

> Template status: replace every bracketed placeholder, rename this file,
> and update `AGENTS.md` and `specs/README.md` before product work begins.

## 1. Purpose and mission

- **Project goal or mission:** [PROJECT GOAL OR MISSION]
- **Intended users:** [INTENDED USERS]
- **Problem addressed:** [PROBLEM]
- **Value provided:** [VALUE]

## 2. Environments and compatibility

- **Supported platforms and versions:** [SUPPORTED ENVIRONMENTS]
- **Required dependencies or capabilities:** [REQUIREMENTS]
- **Unsupported environments and behavior:** [UNSUPPORTED ENVIRONMENTS]

## 3. Scope and boundaries

- **In scope:** [IN-SCOPE BEHAVIOR]
- **Explicitly out of scope:** [OUT-OF-SCOPE BEHAVIOR]
- **External systems and trust boundaries:** [INTEGRATIONS AND BOUNDARIES]

## 4. Data model and collection

Define the data the project receives, creates, transforms, stores, transmits,
or displays. State source authority, normalization rules, retention, and
accuracy expectations where applicable.

- **Data model:** [DATA MODEL]
- **Collection or input behavior:** [COLLECTION OR INPUT RULES]
- **Accuracy, freshness, and uncertainty:** [ACCURACY RULES]

## 5. Observable behavior and presentation

Define successful behavior, defaults, ordering, user interactions, reports or
UI, accessibility, and output formats that users or integrations can observe.

- **Behavior:** [OBSERVABLE BEHAVIOR]
- **Presentation or UI:** [PRESENTATION RULES]

## 6. Errors and degraded operation

Specify invalid inputs, unavailable dependencies, partial results, error
messages, recovery, and any user-visible distinction between complete and
degraded operation.

- **Error semantics:** [ERROR AND DEGRADED-OPERATION RULES]

## 7. Privacy and security

Define the applicable threat model, sensitive data, permission model, logging,
storage, transmission, retention, and security guarantees. Do not imply a
guarantee that the project cannot meet.

- **Privacy rules:** [PRIVACY RULES]
- **Security rules:** [SECURITY RULES]

## 8. Acceptance scenarios

Use stable identifiers. Each scenario states setup, action, and observable
expected result. Tests must cite the identifier(s) they cover.

### [AS-001: SCENARIO NAME]

- **Given:** [SETUP]
- **When:** [ACTION]
- **Then:** [OBSERVABLE RESULT]

## 9. Engineering and test invariants

Record only implementation-independent constraints needed to preserve the
behavioral contract, such as determinism, performance, compatibility, security,
or accessibility requirements. Map tests to acceptance-scenario identifiers.

- **Invariant:** [ENGINEERING OR TEST INVARIANT]
