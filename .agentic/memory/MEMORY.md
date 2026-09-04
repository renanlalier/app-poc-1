---
format_version: 1
last_updated_by: bootstrap
---

## Stack preferences

(Populated by agent executions via the memory-write skill.)

## Known constraints

- Cannot add dependencies without human approval (`forbid_dependencies_add: true`)
- Cannot modify `.github/workflows/**`, `.agentic/config.yml`, or `.agentic/skills/**`
- `.agentic/memory/**` is writable — use the memory-write skill at end of every execution
- Must pass `build` and `test` gates before a PR is considered valid

## Lessons learned

(Populated by agent executions via the memory-write skill.)

## Inter-execution context

(Populated by agent executions via the memory-write skill.)
