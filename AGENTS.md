# Repository agent guide

## Repository workflow and completion

This Go library contains Bubble Tea component directories and tests, not a standalone application. Use Go 1.24+, `go mod download`, `go build ./...`, and `go test ./...`, matching CI. Taskfile also exposes test/golangci-lint tasks; run affected package tests during iteration and required broader checks before completion.

Test state/update/view contracts and inspect changed terminal rendering. Prefer deterministic input and terminal/clipboard substitutes, preserving user state. Compilation does not prove keyboard navigation or visual layout; report automated/manual evidence separately.

Continue the authorized change through relevant validation and repair of failures it causes; preserve unrelated work. Report checks actually run, commands only inspected, and exact missing prerequisites. Ask only when a material decision, missing authorization, or required input blocks progress; continue independent reversible work. Existing mandatory contribution and validation gates still apply.
