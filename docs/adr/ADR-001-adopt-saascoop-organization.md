# ADR-001 — Adopt SaaSCoop Organization as the Engineering Platform Home

## Status

Accepted

## Date

2026-06-25

## Context

The SaaSCoop initiative is being structured as a long-term cooperative ecosystem focused on open-source software, artificial intelligence, education, research, and community governance.

One architectural decision required early in the project is defining where the Engineering Platform should be hosted.

The alternatives considered were:

1. Personal GitHub account
2. Dedicated GitHub organization exclusively for the Engineering Platform
3. Official SaaSCoop GitHub Organization

## Decision

The Engineering Platform will be hosted inside the official SaaSCoop GitHub Organization.

The platform becomes a shared engineering foundation supporting current and future SaaSCoop projects.

## Rationale

This decision aligns with SaaSCoop principles:

- technological sovereignty
- community governance
- reusable knowledge
- open collaboration
- long-term sustainability
- institutional ownership instead of personal ownership
- generation of open technological assets

Hosting the platform inside the organization prevents fragmentation and strengthens the SaaSCoop identity.

## Alternatives Considered

### Alternative 1 — Personal Repository

Advantages:

- simple to create
- low initial friction

Disadvantages:

- personal ownership
- difficult succession
- weak institutional identity
- not aligned with long-term community governance

Decision:

Rejected.

### Alternative 2 — Dedicated Organization for the Engineering Platform

Advantages:

- independent identity
- clear project separation

Disadvantages:

- duplicated governance
- fragmented community
- increased administrative overhead
- weaker connection with SaaSCoop's long-term mission

Decision:

Rejected for the current stage.

### Alternative 3 — SaaSCoop Organization

Advantages:

- unified governance
- centralized documentation
- common engineering standards
- reusable infrastructure
- stronger community identity
- better onboarding for contributors
- clear alignment with SaaSCoop strategy

Decision:

Accepted.

## Consequences

### Positive

- centralized engineering standards
- unified documentation
- reusable templates
- shared governance
- stronger brand identity
- easier onboarding
- better continuity if new contributors join the organization

### Negative

- requires governance discipline from the beginning
- requires clear repository organization
- may increase the importance of maintaining organization-level documentation

## Risks

- The organization may become difficult to navigate if repositories are created without a portfolio strategy.
- The Engineering Platform may become too broad if scope is not controlled.
- Contributors may confuse platform assets with product-specific implementation details.

## Mitigations

- Define repository categories.
- Adopt naming conventions.
- Maintain architecture documentation.
- Use ADRs for important decisions.
- Review governance periodically.
- Keep product-specific assets in product repositories and shared standards in the Engineering Platform.

## Future Work

- Create the Engineering Platform roadmap.
- Define repository taxonomy.
- Create engineering standards.
- Establish organization-level governance.
- Configure repository rules, branch protection, discussions, security alerts, and contribution guidelines.
