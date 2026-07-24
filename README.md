# Payam Adloo

**Engineering Systems · Python · Telemetry · Test Automation**

Electrical engineer with eight years of experience across aerospace and defense test, hardware validation, systems integration, qualification, and failure investigation. Current technical work focuses on Python services and automation for hardware-adjacent systems.

## Selected systems

### [Secure Payload Command and Telemetry Gateway](https://github.com/piemasterflex111/cislunar-ground-platform)

Five-service Python system that receives a fixed binary telemetry frame, preserves the original bytes, validates the interface contract, coordinates durable work through PostgreSQL and Redis, and returns operator-readable results.

**Technical areas:** Python · FastAPI · PostgreSQL · Redis · Docker Compose · binary protocols · CRC validation · idempotency

### [STM32 Hardware Validation Framework](https://github.com/piemasterflex111/stm32-hardware-validation-framework)

Python-driven validation for an STM32F446RE development board, including UART command handling, serial evidence capture, I²C checks, BME280 sensor verification, and structured CSV/JSON artifacts.

**Technical areas:** embedded validation · UART · I²C · pyserial · automated test execution

### [TraceOps Evidence Demo](https://github.com/piemasterflex111/traceops-evidence-demo)

FastAPI and SQLAlchemy workflow for converting engineering evidence into reviewable requirements, claims, gaps, and deterministic validation results.

**Technical areas:** typed APIs · persistence · automated tests · audit-oriented workflow design

### [Engineering Workflow Dashboard](https://github.com/piemasterflex111/engineering-workflow-dashboard)

Python automation for normalizing Jira and GitHub data, classifying work, generating reports, and separating dry-run planning from controlled live updates.

**Technical areas:** REST API integration · internal tools · safe automation · reporting pipelines

### [Local AI Inference Validation](https://github.com/piemasterflex111/local-ai-inference-proof)

Measured validation record for a local vLLM and Qwen inference stack on an NVIDIA RTX PRO 4000 Blackwell workstation, including failure taxonomy, runtime baselines, request-governor revisions, and reproducible evidence.

**Technical areas:** Linux systems debugging · GPU inference operations · Docker · runtime validation

## Technical domains

| Area | Scope |
|---|---|
| **Systems integration** | Power, harnesses, instrumentation, serial communication, software, and operator workflow |
| **Test automation** | Deterministic execution, explicit pass/fail criteria, failure-path testing, and structured artifacts |
| **Python software** | FastAPI, Pydantic, SQLAlchemy, pytest, asynchronous services, CLI tooling, and data processing |
| **Telemetry** | Binary packet contracts, CRC validation, sequence behavior, raw-frame preservation, and retrieval |
| **Hardware validation** | Embedded devices, UART, I²C, bench instrumentation, qualification testing, and root-cause isolation |
| **Linux and containers** | Docker Compose, service health checks, logs, process isolation, and reproducible environments |

## Engineering principles

Preserve original evidence, validate interfaces early, isolate one failure layer at a time, make rejection behavior explicit, and verify outcomes with repeatable tests.
