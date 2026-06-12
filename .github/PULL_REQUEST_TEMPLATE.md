## Description

<!-- A clear summary of the changes. Include the semver impact: patch / minor / major. -->

**Semver impact**: <!-- patch / minor / major -->

## Linked Issue

Closes # <!-- Issue number this PR resolves -->

## Type of Change

- [ ] 🐛 Bug fix (patch)
- [ ] ✨ New feature / method (minor)
- [ ] 💥 Breaking change (major)
- [ ] 📝 Documentation / TypeDoc update
- [ ] 🔧 Chore / refactor
- [ ] 🧪 Tests only

## Changes Made

<!-- List the files/modules changed and why. -->

-
-

## Public API Changes

<!-- List any new exported symbols, changed signatures, or removed APIs. -->

```typescript
// New / changed exports:
```

## Test Evidence

```
pnpm test:run output:
```

## Build Evidence

```
pnpm build output:
```

## Checklist

- [ ] I have read [CONTRIBUTING.md](../CONTRIBUTING.md)
- [ ] This PR is linked to an open issue
- [ ] `pnpm typecheck` passes
- [ ] `pnpm lint` passes
- [ ] `pnpm test:run` passes — all tests green
- [ ] `pnpm build` succeeds — `dist/` generated cleanly
- [ ] All new public methods/types have TypeDoc comments
- [ ] New behaviour is covered by at least one Vitest unit test
- [ ] No new runtime dependencies added without prior maintainer approval
- [ ] `docs/` updated if public API changed
- [ ] `examples/` updated if new usage patterns were added
- [ ] Backwards compatibility maintained (or breaking change clearly noted above)

## Additional Notes

<!-- Anything else reviewers should know. -->
