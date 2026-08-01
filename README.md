# FloAudit Workflow Templates

![License](https://img.shields.io/badge/license-MIT-blue)
![Workflow Testing](https://img.shields.io/badge/Workflow-Business-red)
![API Testing](https://img.shields.io/badge/API-REST-green)
![Playwright](https://img.shields.io/badge/Browser-Playwright-blue)
![Kafka](https://img.shields.io/badge/Kafka-Events-orange)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)

Production-ready workflow templates for validating APIs, databases, Kafka, RabbitMQ, browser automation, files, and complete business workflows using FloAudit.

---

## Why this repository?

Modern applications rarely consist of a single API.

A single customer journey may involve:

- REST APIs
- GraphQL APIs
- PostgreSQL
- MySQL
- Kafka
- RabbitMQ
- Files
- Browser automation
- Email
- Background jobs

This repository provides reusable workflow templates that help engineering teams validate complete business workflows instead of testing isolated components.

---

## Included Templates

### API Validation

- Login API
- Payment API
- User Registration
- GraphQL Validation
- JWT Authentication
- File Upload API

---

### Database Validation

- PostgreSQL Validation
- MySQL Validation
- Order Verification
- Inventory Validation
- User Data Validation

---

### Event Validation

- Kafka Payment Event
- Kafka Shipment Event
- RabbitMQ Queue Validation
- Order Created Event
- Inventory Updated Event

---

### Browser Validation

- Login Flow
- Checkout Flow
- Registration Flow
- Password Reset
- File Upload

---

### File Validation

- PDF Validation
- CSV Validation
- Excel Validation
- Report Verification
- Invoice Validation

---

## Repository Structure

```
workflow-templates
│
├── api/
├── database/
├── kafka/
├── browser/
├── files/
└── docs/
```

---

## Getting Started

Clone the repository

```bash
git clone https://github.com/FloAudit/workflow-templates.git
```

Browse the category that matches your use case.

Import the workflow into FloAudit.

Customize variables, endpoints, databases, or event brokers for your own environment.

---

## Example Use Cases

✔ Validate customer onboarding

✔ Verify payment processing

✔ Test order processing

✔ Validate Kafka events

✔ Verify generated PDF invoices

✔ Test Playwright browser flows

✔ Validate database updates

✔ End-to-End business workflow testing

---

## Documentation

Documentation:

https://floaudit.com/docs

Website:

https://floaudit.com

---

## Contributing

Contributions are welcome.

If you'd like to contribute templates, documentation improvements, or bug fixes, please open a Pull Request.

---

## Related Resources

- Business Workflow Testing
- API Testing
- Database Testing
- Kafka Testing
- Browser Automation
- End-to-End Testing
- Test Automation
- Playwright
- PostgreSQL Validation

---

## About FloAudit

FloAudit is a visual Business Workflow Testing Platform built for modern engineering teams.

Validate APIs, databases, Kafka, RabbitMQ, files, browser automation, scheduled jobs, and complete business workflows from one platform.

Learn more:

https://floaudit.com

---

## License

MIT License
