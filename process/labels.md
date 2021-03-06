# GitHub Labels

- Owner: @janpio
- Stakeholders: @pantharshit00 @divyenduz
- State: 
  - Spec: Stable ✅
  - Implementation: Fully implemented ✅

Our [Prisma Framework repositories](repositories.md) use several labels in the [Issue Triage](issue-triage.md) process.

---

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Categorization](#categorization)
- [Qualification](#qualification)
- [Special cases](#special-cases)
  - [`prisma/specs`](#prismaspecs)
  - [`prisma/studio`](#prismastudio)
- [Tooling](#tooling)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Categorization

To categorize incoming issues:

- `kind/bug`: A reported bug.
- `kind/regression`: A reported bug in functionality that used to work before.
- `kind/feature`: A request for a new feature.
- `kind/improvement`: An improvement to existing feature and code.
- `kind/docs`: A documentation change is required.
- `kind/discussion`: Discussion is required. 
- `kind/question`: Developer asked a question. No code changes required.

## Qualification

To further qualify `kind/bug` issues:

- `bug/0-needs-info`:  More information is needed for reproduction.
- `bug/1-repro-available`: A reproduction exists and needs to be confirmed. 
- `bug/2-confirmed`: We have confirmed that this is a bug.

## Special cases

### `prisma/specs`

The `specs` repository has a different set of labels. As this is currently still changing often, it doesn't make too much sense to document here.

### `prisma/studio`

The `studio` repository has an additional set of labels. As this is currently still changing often, it doesn't make too much sense to document here.

## Tooling

We use an Open Source tool called `label-sync` in our [`prisma-label-sync` repository](https://github.com/prisma/prisma-label-sync) to define these labels via code and apply the configuration to the GitHub repositories.
