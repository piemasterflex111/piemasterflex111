
# Payam Adloo

Engineer focused on **hardware validation, embedded systems, and automated test infrastructure**.

Background in spacecraft battery production engineering and embedded system testing.  
Currently building tools that demonstrate how **Python automation interacts with embedded hardware systems**.

---

# Engineering Focus

- Embedded systems validation
- Firmware testing infrastructure
- Hardware communication protocols (UART / CAN)
- Python test automation
- Manufacturing test systems
- Backend API services

---

# System Architecture Focus

```mermaid
flowchart LR

A[Test Automation Framework] --> B[Hardware Interface Layer]

B --> C[UART Communication]
B --> D[CAN Communication]

C --> E[Embedded Device]
D --> E

E --> F[STM32 Firmware]
F --> G[Sensors / Peripherals]

G --> H[Validation Results]
H --> A
```

This workflow represents the architecture used across my validation frameworks.

Python test systems interact with embedded hardware through structured interface layers, allowing automated validation of firmware behavior and device responses.

---

# Key Projects

## STM32 Hardware Validation Framework

Python-based embedded validation environment demonstrating automated testing of an STM32 microcontroller using UART and CAN communication.

```mermaid
flowchart TD

A[Test Runner] --> B[UART Interface]
A --> C[CAN Interface]

B --> D[STM32 Command Protocol]
C --> D

D --> E[Sensor Data / Device Responses]

E --> F[Validation Logic]
F --> G[Test Results]
```

Repository:

https://github.com/piemasterflex111/stm32-hardware-validation-framework

---

## Spacecraft Test Automation Framework

Prototype infrastructure for automated validation workflows used in aerospace hardware test environments.

```mermaid
flowchart TD

A[Test Execution Engine] --> B[Hardware Communication Layer]

B --> C[Power Systems]
B --> D[Telemetry Systems]
B --> E[Sensor Systems]

C --> F[Validation Engine]
D --> F
E --> F

F --> G[Test Artifacts]
```

Repository:

https://github.com/piemasterflex111/spacecraft-test-automation-framework

---

## Manufacturing Data Automation

Tools for analyzing and automating manufacturing test data pipelines.

```mermaid
flowchart LR

A[Test Stations] --> B[Data Collection Scripts]
B --> C[Processing Pipeline]
C --> D[Structured Reports]
D --> E[Engineering Insights]
```

Repository:

https://github.com/piemasterflex111/manufacturing-data-automation

---

## Backend Auth System

Python backend service demonstrating authentication workflows and API infrastructure.

```mermaid
flowchart LR

A[Client Application] --> B[API Layer]
B --> C[Authentication Service]
C --> D[Database]
D --> B
```

Repository:

https://github.com/piemasterflex111/backend-auth-system

---

# Validation Workflow Philosophy

```mermaid
flowchart TD

A[Test Definition] --> B[Test Execution]
B --> C[Hardware Interaction]
C --> D[Data Capture]

D --> E[Validation Logic]
E --> F[Test Artifacts]

F --> G[Engineering Feedback]
G --> A
```

The goal of automated validation systems is to create a **closed feedback loop between firmware behavior and engineering insight**.

---

# Current Focus

Developing validation frameworks that bridge:

- embedded firmware
- automated test infrastructure
- hardware communication interfaces
- structured validation artifacts

---

# Technologies

**Languages**

Python  
C/C++ (embedded firmware)

**Protocols**

UART  
CAN

**Tools**

PySerial  
python-can  
pytest  
FastAPI

---

# Contact

GitHub  
https://github.com/piemasterflex111
