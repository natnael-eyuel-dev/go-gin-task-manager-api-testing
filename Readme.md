# Go Gin Task Manager API (Testing)

A reliability-focused iteration of the Task Manager API with unit testing coverage and CI workflow integration to validate authentication, authorization, and core business operations.

## Phase Position

- **A2SV Go Phase:** Task 8 (Testing + CI)
- **Previous Project:** `go-clean-architecture-task-manager`
- **Program Milestone:** Final testing and CI hardening stage after architecture refactor

## Features

- Unit tests for core layers and flows
- Test suite using `testify`
- CI pipeline via GitHub Actions
- Existing JWT + RBAC + task API behavior retained

## Tech Stack

- Go
- Gin
- Testify
- GitHub Actions

## Project Structure

```text
.
├── .github/workflows/
├── Delivery/
├── Domain/
├── Infrastructure/
├── Repositories/
├── Usecases/
├── docs/
├── .gitignore
├── coverage
├── go.mod
├── go.sum
└── Readme.md
```

## Run

```bash
go mod tidy
go run main.go
```

## Test

```bash
go test ./... -v
```

## Learning Outcomes

- Testable design in layered services
- Confidence-building through automated checks
- CI-first engineering practices
