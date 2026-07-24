# Payam Adloo

**Engineering Systems · Python · Telemetry · Test Automation**

Electrical engineer with eight years of experience across aerospace and defense test, hardware validation, systems integration, qualification, and failure investigation. Current technical work focuses on operating and validating Python systems that connect software behavior to measurable evidence.

## Public systems

### [Secure Payload Command and Telemetry Gateway](https://github.com/piemasterflex111/cislunar-ground-platform)

Five-service Python system that receives a fixed binary telemetry frame, preserves the original bytes, validates the interface contract, coordinates durable work through PostgreSQL and Redis, and returns operator-readable results.

**Verified behavior:** nominal processing · raw-byte preservation · idempotent duplicate handling · CRC rejection

### [Hardware Validation Bench](https://github.com/piemasterflex111/stm32-hardware-validation-framework)

Fail-closed serial hardware workflow with explicit Linux device detection, command/response evidence capture, and a strict separation between software checks and physical validation.

**Current boundary:** no supported serial device was connected during the latest audit, so the repository does not claim a completed physical STM32 validation run.

## Operational systems

The following systems are maintained in private repositories because they contain workstation-specific operating configuration rather than public portfolio material:

- **AIWork control plane** — isolates agent changes, runs independent verification, requires human ownership attestation, reapplies checks, and rolls back failed patches.
- **Local AI runtime** — source of truth for the running vLLM container, parser configuration, health checks, measured routing experiments, and rollback profiles.
- **Qwen request governor** — admission control, context budgeting, OpenAI-compatible request sanitation, upstream failure handling, and audit logging for local inference.

## Technical domains

| Area | Scope |
|---|---|
| **Systems integration** | Power, harnesses, instrumentation, serial communication, software, and operator workflow |
| **Test automation** | Deterministic execution, explicit pass/fail criteria, failure-path testing, and structured artifacts |
| **Python software** | FastAPI, Pydantic, SQLAlchemy, automated tests, asynchronous services, CLI tooling, and data processing |
| **Telemetry** | Binary packet contracts, CRC validation, sequence behavior, raw-frame preservation, and retrieval |
| **Linux and containers** | Docker Compose, systemd services, health checks, logs, process isolation, and rollback |

## Engineering principle

A system is not considered validated because code exists or software tests pass. Claims are limited to behavior that was directly observed and preserved as repeatable evidence.
