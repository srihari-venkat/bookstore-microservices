# CityCare Hospital Management System

A Python-based Hospital Management System developed to manage hospital operations, patient records, appointments, billing, and other healthcare workflows using Object-Oriented Programming principles.

## Features

- **Patient Management** – Register, search, and manage patient records.
- **Appointment Management** – Book, cancel, and manage appointments.
- **Doctor and Staff Management** – Manage doctors, nurses, and staff-related operations.
- **Admission and Discharge** – Handle inpatient admissions, ward transfers, and discharge workflows.
- **Prescription Management** – Manage prescriptions with allergy and drug-interaction checks.
- **Billing and Payments** – Generate bills, manage payments, and support insurance-based billing.
- **Surgery Scheduling** – Schedule surgeries based on theatre and staff availability.
- **Hospital Services** – Manage laboratory tests, health packages, referrals, follow-ups, diet plans, and visitors.
- **Audit and Reporting** – Maintain audit logs, support undo operations, and generate hospital reports.
- **Exception Handling** – Handle invalid operations and application errors using custom exceptions.

## Tech Stack

- **Language:** Python
- **Concepts:** Object-Oriented Programming, Inheritance, Polymorphism, Abstraction, Encapsulation, Design Patterns
- **Tools:** Git, GitHub
- **Interface:** Command-Line Interface (CLI)

## Project Structure

```text
hms/
├── models/
├── services/
├── exceptions/
├── data/
├── main.py
└── __init__.py
```

- `models/` – Contains hospital entities and domain models.
- `services/` – Contains business logic for appointments, billing, admissions, reporting, and other operations.
- `exceptions/` – Contains custom exception classes.
- `data/` – Contains seed data and initial application records.
- `main.py` – Entry point for the command-line application.

## Getting Started

### Prerequisites

- Python 3.10 or later
- Git

### Run the Application

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-folder>
   ```

3. Run the application from the directory containing the `hms` package:

   ```bash
   python -m hms.main
   ```

## Testing

Run the project tests using the test command configured for your environment. For example, with pytest:

```bash
python -m pytest
```

## Learning Outcomes

- Applied OOP principles to build a modular application.
- Implemented business rules and validation for hospital workflows.
- Used design patterns to organize operations and manage application state.
- Practiced Git-based version control and incremental development.
- Developed and tested a multi-feature command-line application.

## Author

**V Srihari**

