# Payam Adloo

**Software Engineer · Python Backend · AI Applications · Internal Tools**

Software engineer with an electrical engineering and aerospace/defense background. I spent eight years across hardware validation, systems integration, qualification, manufacturing systems, and failure investigation, where I consistently gravitated toward automation, telemetry, debugging, software tooling, and hardware/software integration. I now build Python backend systems, APIs, AI applications, and engineering automation with an emphasis on reliability and measurable verification.

**Target roles:** Software Engineer · Python Backend Engineer · AI Application Engineer · Automation / Developer Productivity Engineer

## What I build

| Area | Engineering focus |
|---|---|
| **Backend systems** | FastAPI services, typed contracts, SQL persistence, asynchronous work, health checks, and failure handling |
| **AI applications & infrastructure** | Local vLLM inference, request admission, context budgeting, tool/agent workflows, performance measurement, and rollback controls |
| **Internal tools & automation** | Engineering workflow automation, API integrations, operator tooling, debugging, and repeatable verification |
| **Telemetry and hardware integration** | Binary protocols, CRC validation, serial communication, device detection, and evidence capture |
| **Verification** | pytest, static checks, containerized integration tests, CI, explicit pass/fail criteria, and reproducible artifacts |

## Flagship public systems

### [Secure Payload Command and Telemetry Gateway](https://github.com/piemasterflex111/cislunar-ground-platform)

[![ground-platform-ci](https://github.com/piemasterflex111/cislunar-ground-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/piemasterflex111/cislunar-ground-platform/actions/workflows/ci.yml)

Five-service Python system that receives a fixed binary telemetry frame, preserves the original bytes, validates the interface contract, coordinates durable processing through PostgreSQL and Redis, and returns operator-readable results.

**Verified behavior:** 146 automated tests · isolated end-to-end verification · raw-byte preservation · idempotent duplicate handling · sequence checks · CRC rejection

**Demonstrates:** service boundaries, durable state, API design, binary protocol handling, failure-path testing, and Docker Compose integration.

### [Hardware Validation Bench](https://github.com/piemasterflex111/stm32-hardware-validation-framework)

[![software-verification](https://github.com/piemasterflex111/stm32-hardware-validation-framework/actions/workflows/ci.yml/badge.svg)](https://github.com/piemasterflex111/stm32-hardware-validation-framework/actions/workflows/ci.yml)

Fail-closed Python workflow for serial and CAN hardware validation. It detects Linux devices, records exact command/response evidence, and prevents software-only checks from being presented as physical hardware validation.

**Demonstrates:** PySerial, hardware presence gates, structured evidence artifacts, explicit failure behavior, and the boundary between simulation and observed bench results.

## Operational AI systems

These repositories remain private because they contain workstation-specific operating configuration rather than public portfolio material:

- **AIWork control plane** — executes bounded agent changes in isolated Git worktrees, verifies them independently, requires human ownership attestation, and rolls back failed applications.
- **Local AI runtime** — versions the vLLM container configuration, health checks, measured routing experiments, and rollback profiles for a local NVIDIA GPU inference stack.
- **Qwen request governor** — provides OpenAI-compatible request sanitation, context budgeting, admission control, upstream failure handling, and request audit records.

## Core stack

`Python` · `FastAPI` · `Pydantic` · `SQLAlchemy` · `PostgreSQL` · `Redis` · `pytest` · `Docker Compose` · `Linux` · `systemd` · `vLLM` · `GitHub Actions` · `serial/CAN telemetry`

## Engineering standard

Code existence is not proof of system behavior. Claims are limited to behavior that was directly exercised, checked against explicit acceptance criteria, and preserved as repeatable evidence.
