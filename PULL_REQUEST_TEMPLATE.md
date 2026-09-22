# Pull Request

## Gate

```text
Architecture Gate: REQUIRED | NOT_REQUIRED
Architecture Authority: <official path>@<verified SHA or PENDING>
Implementation Allowed: YES | NO
Slice Risk: LOW | MEDIUM | HIGH
Change Class: FEATURE_ONLY | DEPENDENCY_PATCH | DEPENDENCY_MAJOR | FRAMEWORK_OR_SDK | COMPILER_OR_TOOLCHAIN | LOCKFILE_ARCHITECTURE | SECURITY_REMEDIATION | CI_OR_DEPLOYMENT
Change Safety: NOT_REQUIRED | LIGHT | FULL
```

When the accepted Change Safety Standard (`5atwah/standards/engineering/CHANGE_SAFETY_STANDARD.md` section 2) applies, keep both `Change Class` and `Change Safety`, each with one of its section 3 values listed above; otherwise delete both lines.

`LIGHT` keeps the Architecture Gate `NOT_REQUIRED` but requires the bounded dependency/tooling proof below. `FULL` requires an accepted Architecture Gate.

## Exact scope

- Base SHA:
- Head SHA:
- Task/slice:
- Changed files:
- Expected manifest/lockfile effect, if applicable:
- Explicit non-goals:

## What changed

Describe the smallest meaningful delta and why it is required. Reference official authorities instead of copying project history or permanent rules.

## Verification

- [ ] Exact repo/base/head/branch verified.
- [ ] Complete diff reviewed; no unrelated files or generated output.
- [ ] Relevant lint/typecheck/test/build/docs checks passed, or exact reason stated.
- [ ] Any failure was reproduced unchanged, classified, isolated, repaired at root cause, and the original command rerun.
- [ ] Dependency/toolchain work proves owner, consumer, peers, deliberate pins, expected files, lockfile budget, and external automation/deployment effects.
- [ ] Exact PR-head CI completed successfully where configured, or exact no-CI review evidence recorded.
- [ ] Architecture/contract/schema/security tests derive from accepted authority where required.
- [ ] No unresolved review blocker or moved head.

Evidence:

```text
Commands/checks:
Failure class/root cause, if applicable:
Dependency graph/lockfile proof, if applicable:
CI run or no-CI evidence:
Review ID/verdict:
```

## Safety and boundaries

- [ ] No secrets, credentials, private keys, tokens, recovery codes, private customer data, or production values.
- [ ] No hardcoded geography, merchants, sources, addresses, fees, schedules, or environment-specific values.
- [ ] No undeclared dependency, Prisma/migration, public-contract, provider/native, payment/order/inventory/fulfillment/service, or CI expansion.
- [ ] Backend authority, money minor units + currency, and separate status domains are preserved where relevant.
- [ ] No AI attribution, promotional footer, or signature.

## Reuse and cleanup

- Adopt:
- Adapt:
- Reject/delete:

State whether duplicate, stale, or superseded code/docs were removed or intentionally retained, and why.

## Memory Delta

```text
None | exact accepted memory files to update after merge
```

Do not record an unmerged PR as accepted state.

## Merge state

- [ ] Draft until implementation/review/CI gates pass.
- [ ] Merge authorization matches this exact repo/base/head/diff/scope.
- [ ] No production, credential, billing, destructive, or branch-deletion action is implied.

## Next action

State one exact next action only.
