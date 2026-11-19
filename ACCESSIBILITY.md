# Accessibility

**Project:** EGO_INC  
**Document status:** Proposed — pending FAGHIURI approval  
**Last policy review:** 19 November 2026  
**Accessibility evaluation status:** Not yet verified

EGO_INC aims to make its software, documentation, and project resources accessible to people with different abilities, needs, and ways of interacting with technology.

Accessibility matters because everyone should have a reasonable opportunity to understand information, use available features, and participate in the project.

This document describes our accessibility priorities, contributor responsibilities, reporting process, supported environments, known limitations, and approach to improvements.

## Priorities

Our priorities include:

- **Keyboard access:** Essential functions should be usable without requiring a mouse.
- **Screen reader support:** Interfaces should provide meaningful labels, structure, and descriptions.
- **Readable content:** Text and visual information should be clear and distinguishable.
- **Accessible interaction:** Controls should provide visible focus, understandable instructions, and helpful error messages.
- **Alternative formats:** Relevant images, audio, and video should have appropriate accessible alternatives.
- **Language accessibility:** Information should use clear language and support appropriate language identification.
- **Continuous improvement:** Accessibility barriers should be documented, reviewed, and addressed.

For applicable web content, EGO_INC proposes **WCAG 2.2 Level AA** as its accessibility development target.

Reference: [W3C Web Content Accessibility Guidelines 2.2](https://www.w3.org/TR/WCAG22/).

This is an aspirational target, not a statement of verified conformance. Any future conformance claim must be supported by an appropriate evaluation identifying its scope, date, method, evaluator, and results.

## Contributor expectations

Contributors, including AI-assisted contributors, are expected to consider accessibility when proposing or implementing changes.

For user-facing changes, contributors should:

1. Use appropriate interface structure and descriptive labels.
2. Check keyboard navigation and focus behavior.
3. Consider screen reader and assistive technology compatibility.
4. Provide alternatives to meaningful non-text content.
5. Review the clarity of instructions and error messages.
6. Test affected functionality where practical.
7. Document accessibility limitations identified during development.
8. Report the tests actually completed and their results.

Contributors should include relevant testing evidence in pull requests.

Automated accessibility testing may be added to the development workflow. Automated results should be combined with appropriate manual evaluation.

No accessibility testing tools, automated checks, or continuous integration results are claimed to exist unless they have been configured and verified.

Contributions remain subject to EGO_INC project governance. Changes to protected systems, including MASTERARCHIVE, require the applicable explicit approval from FAGHIURI.

## Reporting accessibility issues

EGO_INC welcomes reports of accessibility problems and requests for help.

**GitHub accessibility reporting:** [Insert verified issue-reporting link]

**Alternative accessible contact:** [Insert verified contact method]

When reporting an issue, contributors may provide:

- The affected page, feature, or task.
- What they were trying to accomplish.
- What happened and what they expected.
- The browser, operating system, or device involved.
- The assistive technology used, if they choose to share it.
- Optional screenshots or recordings.

Reporters do not need to disclose a disability or medical information.

Please avoid including passwords, private credentials, or sensitive personal information in public GitHub issues. Security vulnerabilities should use the project's designated private security-reporting process once configured.

### Severity

The following categories are proposed for accessibility issue triage.

**Critical:** An essential task is completely blocked, with no reasonable workaround.

**High:** An important task cannot be completed independently by affected users.

**Medium:** A barrier substantially increases difficulty, but a reasonable alternative is available.

**Low:** A limited accessibility problem that does not prevent task completion.

Maintainers will assess the impact of the barrier and confirm severity. Reporters do not need to determine severity themselves.

These categories should be aligned with the repository's issue templates and labels before implementation.

### How we respond

EGO_INC intends to follow this process:

1. Review and acknowledge accessibility reports.
2. Request clarification when needed.
3. Assess the impact and assign an appropriate severity.
4. Identify possible workarounds.
5. Document proposed corrections.
6. Review and approve required changes.
7. Test corrections and record the results.
8. Invite reporters to verify fixes when practical.

Status updates should be communicated through the available reporting channel.

Specific acknowledgement and resolution deadlines will be established only after the project confirms the resources and responsibilities required to meet them.

## Ownership and maintenance

**Project authority:** FAGHIURI

FAGHIURI retains final project approval authority.

Accessibility maintenance responsibilities include reviewing reports, coordinating evaluations, documenting limitations, and tracking approved improvements.

A designated accessibility maintainer or responsible team should be recorded before the reporting process becomes operational.

ASMIEN and other authorized AI contributors may assist with analysis, documentation, testing recommendations, and proposed corrections. AI-generated proposals do not independently authorize changes to protected systems.

The policy should be reviewed when substantial user-facing changes are made, during relevant maintenance reviews, and when reporting or accessibility responsibilities change.

Transfers of responsibility must be explicitly documented and approved.

## Supported environments

EGO_INC has not yet established a verified accessibility compatibility matrix for this statement.

Supported environments will be documented based on actual evaluation, including applicable:

- Operating systems and versions.
- Desktop and mobile browsers.
- Devices and screen sizes.
- Keyboard and other input methods.
- Screen readers and assistive technologies.
- Relevant software configurations.

The project should distinguish verified support, partial support, and untested environments.

No specific combination is claimed to be accessible solely because it appears in this document.

## Known limitations

A verified inventory of accessibility limitations has not yet been established for this statement.

This does not mean EGO_INC is free of accessibility barriers.

When a limitation is identified, its record should describe:

- The affected user experience or task.
- How the barrier affects accessibility.
- Any available workaround or alternative.
- The related tracking issue, when available.
- The correction status and verification results.

Known barriers should be explained in everyday language.

## Feedback and improvements

Users and contributors are encouraged to recommend accessibility improvements.

Feedback may concern interface behavior, documentation, testing practices, supported environments, or this accessibility statement itself.

Active accessibility barriers should be reported through the designated accessibility-reporting process.

Proposed changes are reviewed under EGO_INC governance, with appropriate authorship attribution and approval.

Accessibility remains an ongoing responsibility throughout development, maintenance, and future product evolution.

---

**Policy status:** Proposed, not yet adopted.

**Conformance status:** No verified WCAG conformance claim.

**Final approval authority:** FAGHIURI.
