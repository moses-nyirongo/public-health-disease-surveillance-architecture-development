# Public Health Disease Surveillance Architecture Development Project

## Overview
This project presents the development of a multi-system public health disease surveillance architecture completed across six course modules. The architecture simulates four virtual hospitals and one Health Information Exchange (UPHIE) to demonstrate how health data can be generated, stored, exchanged, aggregated, and visualized for disease outbreak surveillance.

The project combines virtual machine configuration, OpenEMR deployment, synthetic patient generation with Synthea, HAPI FHIR server setup, FHIR interoperability testing with Postman, and dashboard-based outbreak analytics.

---

## System Architecture
The baseline architecture consists of five virtual machines:
- Aspirus Hospital
- Portage Health Hospital
- Baraga County Memorial Hospital (BCMH)
- Marquette General Hospital (MGH)
- Upper Peninsula Health Information Exchange (UPHIE)

The four hospital VMs simulate healthcare organizations that manage patient data, while the UPHIE VM serves as the central interoperability and aggregation layer.

---

## Project Components

### Part 1 – Virtual Machine Configuration and Testing
Configured five virtual machines using a shared IP address scheme to enable network connectivity between four hospitals and one HIE. Verified communication using the ping command from the UPHIE VM to each hospital VM.

### Part 2 – OpenEMR Installation, Configuration, and Security
Installed and configured OpenEMR 6.0.1 on the four hospital virtual machines. Secured the OpenEMR environment and documented configuration and security steps used in the deployment.

### Part 3 – Synthea Patient and Syndromic Surveillance Data Generation
Generated synthetic patient and COVID-19 syndromic surveillance data using Synthea. Created FHIR `.json` files for each hospital to simulate a disease outbreak scenario across the region.

### Part 4 – HAPI FHIR Server Installation and Configuration
Installed and configured the HAPI FHIR server for interoperability support. Performed memory and port availability checks, validated container deployment, and reviewed optional server customization.

### Part 5 – Interoperability: FHIR Data Exchange with HAPI FHIR
Used Postman to create FHIR resources against the HAPI FHIR server. Documented the process for resource creation, authentication handling, and troubleshooting error responses during data exchange.

### Part 6 – Aggregation and Visualization for Disease Outbreak Surveillance
Aggregated hospital FHIR JSON data using Python and transformed the results into formats suitable for analysis and visualization. Built a Google Looker Studio dashboard to display COVID-19 cases by geographic region and city.

---

## Technologies Used
- Virtual Machines
- Ubuntu/Linux
- OpenEMR
- Synthea
- HAPI FHIR
- Postman
- Python
- Google Looker Studio
- HL7 FHIR JSON data

---

## Learning Outcomes
This project demonstrates skills in:
- Health informatics architecture design
- EHR deployment and configuration
- Synthetic healthcare data generation
- FHIR interoperability
- Public health surveillance workflows
- Health data aggregation and visualization

---

## Repository Contents
Each folder in this repository corresponds to one part of the full architecture development project and contains reports, screenshots, scripts, and supporting files completed throughout the course.

---

## Author
Moses Nyirongo
Physician | AI in Healthcare | Clinical Data Science
