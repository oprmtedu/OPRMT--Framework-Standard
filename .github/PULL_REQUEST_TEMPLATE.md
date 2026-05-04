# Pull Request Template

**Repository:** OPRMT™ Framework Repository  
**Owner:** Michael W. Fleming  
**Template Version:** v1.0.0  
**Recommended Path:** `.github/PULL_REQUEST_TEMPLATE.md`

---

## 1. Pull Request Summary

Provide a concise summary of the changes included in this pull request.

```text
Summary:
```

---

## 2. Change Type

Select all that apply.

- [ ] Documentation update
- [ ] Framework standard update
- [ ] OPRMT™ component documentation update
- [ ] Prompt template update
- [ ] Prompt cluster update
- [ ] PCE documentation update
- [ ] DOAS™ scoring documentation update
- [ ] Certification material update
- [ ] Governance policy update
- [ ] Legal or licensing documentation update
- [ ] Repository structure update
- [ ] GitHub Actions workflow update
- [ ] Automation script update
- [ ] Bug fix
- [ ] Broken link fix
- [ ] Formatting or linting correction
- [ ] Release preparation
- [ ] Other

If other, describe:

```text
Other change type:
```

---

## 3. Related Issue or Request

Link the related issue, bug report, document request, prompt submission, or standard change request.

```text
Related issue/request:
```

Examples:

```text
Closes #000
Related to #000
Follows STANDARD_CHANGE_REQUEST #000
```

---

## 4. Files Changed

List the primary files or folders changed by this pull request.

```text
Changed files:
/README.md
/docs/index.md
/standard/OPRMT-Framework-Standard-v1.0.md
```

---

## 5. Repository Area Affected

Select all affected areas.

- [ ] Root repository files
- [ ] `.github` templates or workflows
- [ ] `/docs`
- [ ] `/standard`
- [ ] `/framework`
- [ ] `/prompts`
- [ ] `/pce`
- [ ] `/doas`
- [ ] `/certification`
- [ ] `/governance`
- [ ] `/legal`
- [ ] `/assets`
- [ ] `/automation`
- [ ] `/releases`
- [ ] Other

---

## 6. OPRMT™ Framework Compliance

Does this pull request affect official OPRMT™ framework terminology, structure, definitions, or component logic?

- [ ] Yes
- [ ] No
- [ ] Unsure

If yes or unsure, confirm the affected component:

- [ ] Objective
- [ ] Parameters
- [ ] Results
- [ ] Method
- [ ] Tools
- [ ] Full OPRMT™ sequence
- [ ] Not applicable

Confirm that the official OPRMT™ sequence remains preserved:

```text
O — Objective
P — Parameters
R — Results
M — Method
T — Tools
```

- [ ] Confirmed
- [ ] Not applicable
- [ ] Needs maintainer review

Compliance notes:

```text
Compliance notes:
```

---

## 7. Standard Change Control

Does this pull request modify a controlled standard, specification, governance rule, definition, or validation model?

- [ ] Yes
- [ ] No
- [ ] Unsure

If yes, confirm that a Standard Change Request exists:

- [ ] Standard Change Request linked above
- [ ] Standard Change Request not required
- [ ] Needs maintainer review

Version impact:

- [ ] Patch update
- [ ] Minor update
- [ ] Major update
- [ ] No version impact
- [ ] Unsure

Versioning notes:

```text
Versioning notes:
```

---

## 8. Documentation Quality Checklist

Confirm the following before submitting.

- [ ] File names are clear, readable, and repository-appropriate.
- [ ] New major documents include metadata when applicable.
- [ ] Headings are structured and readable.
- [ ] Markdown renders correctly.
- [ ] Internal links have been checked.
- [ ] No placeholder text remains unless intentional.
- [ ] No duplicate or obsolete files were introduced.
- [ ] Folder README or index files were updated if needed.
- [ ] CHANGELOG.md was updated if required.
- [ ] Release notes were updated if required.

---

## 9. Prompt or Template Review

Complete this section if the pull request adds or modifies prompt assets, prompt templates, prompt clusters, or AI workflow instructions.

- [ ] Prompt uses structured OPRMT™ format.
- [ ] Prompt includes clear Objective.
- [ ] Prompt includes defined Parameters or input variables.
- [ ] Prompt defines expected Results.
- [ ] Prompt includes a Method or execution process.
- [ ] Prompt identifies relevant Tools or allowed resources.
- [ ] Prompt includes constraints or guardrails.
- [ ] Prompt avoids unsupported legal, financial, medical, accreditation, or outcome guarantees.
- [ ] Prompt is suitable for repository inclusion.
- [ ] Not applicable.

Prompt review notes:

```text
Prompt review notes:
```

---

## 10. Legal, Ownership, and Usage Review

Select all that apply.

- [ ] This pull request does not modify legal, license, ownership, or usage-policy language.
- [ ] This pull request modifies legal, license, ownership, or usage-policy language and requires maintainer review.
- [ ] OPRMT™ ownership references remain intact.
- [ ] No unsupported commercial-use claims were added.
- [ ] No accreditation, certification recognition, employment guarantee, or legal compliance guarantee was added.
- [ ] No third-party copyrighted material was added without permission or appropriate reference.
- [ ] Needs legal or licensing review.

Legal or ownership notes:

```text
Legal or ownership notes:
```

---

## 11. Testing and Validation

Describe how the change was tested or reviewed.

- [ ] Markdown lint reviewed
- [ ] Link check reviewed
- [ ] Workflow syntax reviewed
- [ ] Script executed locally
- [ ] Script reviewed but not executed
- [ ] Documentation manually reviewed
- [ ] Not applicable

Validation notes:

```text
Validation notes:
```

---

## 12. Screenshots or Evidence

Attach screenshots, rendered Markdown previews, terminal output, workflow logs, or other evidence if applicable.

```text
Evidence:
```

---

## 13. Risk Assessment

Select any known risks.

- [ ] Low risk — documentation or formatting only
- [ ] Medium risk — affects repository structure or linked documentation
- [ ] High risk — affects framework interpretation, standard language, validation logic, or release process
- [ ] Unknown risk — maintainer review required

Risk notes:

```text
Risk notes:
```

---

## 14. Maintainer Review Required

Select any required reviews.

- [ ] Repository Specialist review
- [ ] Framework Owner review
- [ ] Documentation review
- [ ] PCE alignment review
- [ ] DOAS™ alignment review
- [ ] Certification review
- [ ] Legal or licensing review
- [ ] Automation or GitHub Actions review
- [ ] No special review required

---

## 15. Final Contributor Confirmation

By submitting this pull request, I confirm that:

- [ ] I have reviewed the changed files.
- [ ] I have followed the repository structure and naming conventions.
- [ ] I have preserved the OPRMT™ framework sequence and terminology unless a controlled change request is linked.
- [ ] I have not introduced unsupported claims, guarantees, or licensing conflicts.
- [ ] I understand that OPRMT™ and related framework materials are owned by Michael W. Fleming unless otherwise stated in the repository license, notice, or usage policy.
- [ ] I understand that approval of this pull request does not grant rights outside the repository license and usage policy.

---

# Maintainer Section

For maintainer use only.

## Review Decision

- [ ] Approved
- [ ] Approved with revisions
- [ ] Changes requested
- [ ] Rejected
- [ ] Deferred
- [ ] Closed without merge

## Maintainer Notes

```text
Notes:
```

## Required Follow-Up

```text
Follow-up:
```

## Release Notes Entry

```text
Release notes entry:
```

---

# Ownership Notice

OPRMT™ and related framework materials are owned by Michael W. Fleming unless otherwise stated in the repository license, notice, or usage policy.

This pull request template supports repository governance, documentation integrity, prompt compliance alignment, standard change control, and long-term protection of the official OPRMT™ Framework.
