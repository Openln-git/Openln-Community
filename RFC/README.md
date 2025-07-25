# RFC Process

RFC stands for "Request for Comments". This process is used for proposing substantial changes, new features, or architectural decisions for Openln projects.

## When to Use RFCs

Use the RFC process when you want to propose:

- **New features** with significant complexity or impact
- **Breaking changes** to existing APIs or functionality
- **Architectural decisions** that affect multiple components
- **Process changes** for development or community governance
- **Significant refactoring** that changes internal structure
- **New project directions** or major initiatives

## When NOT to Use RFCs

For these cases, use regular GitHub issues instead:

- Bug fixes
- Minor feature additions
- Documentation improvements
- Small refactoring
- Clarifications to existing functionality

## RFC Lifecycle

### 1. Pre-RFC Discussion (Optional)

- Discuss your idea informally in GitHub Discussions
- Get initial feedback from the community
- Refine your proposal based on input

### 2. Draft RFC

- Copy the [RFC template](templates/rfc-template.md)
- Fill in all sections thoroughly
- Save as `RFC/YYYY-MM-DD-brief-title.md`

### 3. Submit RFC

- Open a pull request with your RFC
- RFC number will be assigned by maintainers
- Community discussion happens in the PR

### 4. Community Review

- Community members review and provide feedback
- RFC author addresses concerns and updates the document
- Discussion continues until consensus or decision is reached

### 5. Decision

RFCs can have one of these outcomes:

- **Accepted**: RFC is approved for implementation
- **Rejected**: RFC is not approved (with clear reasoning)
- **Withdrawn**: Author withdraws the proposal
- **Postponed**: Good idea, but not the right time

### 6. Implementation

- Accepted RFCs move to implementation phase
- Implementation can be done by RFC author or others
- Progress is tracked through issues and pull requests

## RFC Format

All RFCs must follow the [standard template](templates/rfc-template.md) and include:

- **Summary**: Brief description of the proposal
- **Motivation**: Why this change is needed
- **Detailed Design**: Technical specification
- **Drawbacks**: Potential negative impacts
- **Alternatives**: Other approaches considered
- **Unresolved Questions**: Areas needing further discussion

## Review Criteria

RFCs are evaluated based on:

- **Technical Merit**: Is the solution technically sound?
- **Community Benefit**: Does it benefit the broader community?
- **Implementation Feasibility**: Can it be reasonably implemented?
- **Backward Compatibility**: Impact on existing users
- **Maintenance Burden**: Long-term maintenance considerations
- **Alignment**: Does it align with project goals and vision?

## RFC Shepherding

For complex RFCs, a shepherd may be assigned to:

- Guide the RFC through the process
- Facilitate discussion and consensus building
- Help address concerns and feedback
- Coordinate with relevant domain experts

## Implementation Tracking

Once an RFC is accepted:

1. Create implementation issues/milestones
2. Track progress against the RFC specification
3. Update the RFC if implementation reveals necessary changes
4. Mark RFC as "Implemented" when complete

## RFC Directory Structure

```
RFC/
├── README.md                    # This file
├── templates/
│   └── rfc-template.md         # RFC template
├── 0001-example-rfc.md         # Accepted RFCs
├── 0002-another-rfc.md
└── withdrawn/                  # Withdrawn RFCs
    └── withdrawn-rfc.md
```

## Current Priority Areas

Given our focus on the **openln-engine MVP**, we're particularly interested in RFCs related to:

- Core engine architecture and design
- API design and interfaces
- Performance and scalability considerations
- Integration patterns and extensibility
- Development tooling and workflows
- Testing strategies and quality assurance

## Examples of Good RFCs

- Clear problem statement and motivation
- Detailed technical specification
- Consideration of alternatives and tradeoffs
- Implementation plan and timeline
- Impact assessment on existing functionality

## Getting Help

- **Questions about the RFC process**: Open a discussion or issue
- **Technical guidance**: Reach out to relevant domain experts
- **Process concerns**: Contact community maintainers
- **Template questions**: See the [RFC template](templates/rfc-template.md)

## Best Practices

### For RFC Authors

- **Start small**: Consider if a smaller change could achieve your goals
- **Research thoroughly**: Understand existing solutions and approaches
- **Engage early**: Get feedback before writing the full RFC
- **Be responsive**: Address feedback and questions promptly
- **Stay focused**: Keep the RFC scope manageable

### For RFC Reviewers

- **Be constructive**: Provide specific, actionable feedback
- **Ask questions**: Help clarify unclear aspects
- **Consider implications**: Think about broader impacts
- **Suggest alternatives**: Propose different approaches when helpful
- **Be timely**: Provide feedback in a reasonable timeframe

## Historical Context

This RFC process is inspired by successful processes used by:

- [Rust RFCs](https://github.com/rust-lang/rfcs)
- [React RFCs](https://github.com/reactjs/rfcs)
- [Ember RFCs](https://github.com/emberjs/rfcs)
- [TC39 Proposals](https://github.com/tc39/proposals)

We've adapted these processes for the specific needs of the Openln community.

---

The RFC process helps ensure that substantial changes to Openln are well-designed, thoroughly discussed, and have broad community support. Thank you for participating in this process! 🚀