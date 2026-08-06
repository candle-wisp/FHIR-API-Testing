# FHIR R4 API Test Suite

Automated API testing project for healthcare interoperability. For this project, we will be using Postman, CLI, and Github Actions.

# Overview

This project tests an FHIR R4 API using the HAPI FHIR public server.

Test suite validations:
- Patient, Observation and MedicationRequest resources
- Response Structure
- Resource Relationships
- API Behavior

  ## Technologies
  - Postman
  - Postman CLI
  - JavaScript
  - FHIR R4
  - HAPI FHIR Server
  - Github Actions
 
  ## Test Coverage
Test collection includes:
- Patient resource retrieval and validation
- Observation and MedicationRequest validation
- FHIR Bundle Structure validation
- Negative Testing:
- Invalid Patient ID
- Empty search results
- Search with no parameters

## Running Tests

Run locally with:

```bash
postman collection run "FHIR Project" --env-var base_url=https://hapi.fhir.org/baseR4
```

## CI/CD

Github Actions automatically runs the test suite on repository changes.
