# Approval models, compared

Every platform that calls itself an AI employee has some answer to "what happens before a risky
call". They differ in three ways: where the rule lives, how narrow it can be, and whether a change to
it is reviewable.

| Model | Where the rule lives | How narrow | Reviewable |
| --- | --- | --- | --- |
| Per-tool policy in the repo | `kortix.yaml` in your repository | Per tool, per argument (`match` + `conditions`) | A pull request and a `git revert` |
| Approval cards in a hosted product | The vendor's console | Per permission the vendor exposes | The vendor's UI history |
| Prompt instructions | The prompt | Not enforceable | No |
| No gate | — | — | — |

## What to ask a vendor

- Which tools can the employee call without asking?
- Can two calls to the same tool get different answers based on their arguments?
- If I change the answer, who reviews the change and how do I undo it?
- Where is the audit trail, and can I export it?

## What the policy looks like in a repo

Kortix reads `policy` and `policies` from `kortix.yaml`. The reference is
<https://kortix.com/docs/project/manifest>. A working example, with a validator that fails the build
when a writing call has no rule, is the campaign's starter:
<https://github.com/ArtemShatokhin/ai-employee-starter>.
