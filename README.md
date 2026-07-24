# Payam Adloo

**Test Automation & Systems Integration Engineer**  
Aerospace hardware · Python · telemetry · Linux · validation infrastructure

Electrical engineer with eight years of experience in aerospace and defense test, hardware validation, systems integration, qualification, and failure investigation. I now build Python software that makes hardware testing repeatable, observable, and evidence-driven.

**Primary targets:** Hardware Test Software · Test Automation · Systems Integration · Verification and Validation · Python Internal Tools

## Flagship engineering proof

### [Secure Payload Command and Telemetry Gateway](https://github.com/piemasterflex111/cislunar-ground-platform)

Five-service Python system that receives a fixed binary telemetry frame, preserves the original bytes, validates the interface contract, prevents duplicate side effects, coordinates durable work through PostgreSQL and Redis, and returns an operator-readable result.

```bash
make hiring-demo
```

The isolated live demonstration proves:

- nominal telemetry ingestion and processing;
- byte-for-byte raw evidence preservation;
- idempotent handling of an exact duplicate;
- rejection of a deliberately corrupted CRC before processing.

**Stack:** Python · FastAPI · PostgreSQL · Redis · Docker Compose · pytest · structured telemetry

## Additional engineering evidence

### [STM32 Hardware Validation Framework](https://github.com/piemasterflex111/stm32-hardware-validation-framework)

Python-driven validation for an STM32F446RE development board, including UART command handling, serial evidence capture, I²C checks, BME280 sensor verification, and structured CSV/JSON artifacts.

**Demonstrates:** hardware/software integration · serial protocols · automated validation · evidence logging

### [TraceOps Evidence Demo](https://github.com/piemasterflex111/traceops-evidence-demo)

FastAPI and SQLAlchemy workflow for converting engineering evidence into reviewable requirements, claims, gaps, and deterministic validation results.

**Demonstrates:** typed APIs · persistence · automated tests · audit-oriented workflow design

### [Engineering Workflow Dashboard](https://github.com/piemasterflex111/engineering-workflow-dashboard)

Python automation for normalizing Jira and GitHub data, classifying work, generating reports, and separating dry-run planning from controlled live updates.

**Demonstrates:** REST API integration · internal tools · safe automation · reporting pipelines

### [Local AI Inference Validation](https://github.com/piemasterflex111/local-ai-inference-proof)

Measured validation record for a local vLLM and Qwen inference stack on an NVIDIA RTX PRO 4000 Blackwell workstation, including failure taxonomy, runtime baselines, request-governor revisions, and reproducible evidence.

**Demonstrates:** Linux systems debugging · GPU inference operations · benchmark discipline · failure analysis

## Engineering strengths

| Area | Evidence |
|---|---|
| **Systems integration** | Power, harness, instrumentation, serial communication, software, and operator workflow treated as one test system |
| **Test automation** | Deterministic execution, explicit pass/fail criteria, failure-path testing, and structured artifacts |
| **Python software** | FastAPI, Pydantic, SQLAlchemy, pytest, asynchronous services, CLI tooling, and data processing |
| **Telemetry** | Binary packet contracts, CRC validation, sequence behavior, raw-frame preservation, and operator retrieval |
| **Hardware validation** | Embedded devices, UART, I²C, bench instrumentation, qualification testing, and root-cause isolation |
| **Linux and containers** | Docker Compose, service health checks, logs, process isolation, and reproducible local environments |

## Working principle

Preserve the original evidence, validate interfaces early, isolate one failure layer at a time, make rejection behavior explicit, and verify the result with repeatable tests.
