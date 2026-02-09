# Healthcare Clinical Ontology

This repository contains the **Healthcare Clinical Ontology**, developed as part of the **Knowledge Representation** exam. The ontology is implemented in **OWL 2** and designed using **Protégé**.

## Purpose of the Ontology

The Healthcare Clinical Ontology aims to provide a semantic representation of clinical information by modeling:

- People involved in healthcare processes
- Healthcare organizations and structures
- Clinical data such as diagnoses and medical records
- Treatments, medications, and procedures
- Administrative and diagnostic activities

The ontology is designed for educational purposes and demonstrates the use of OWL 2 constructs such as classes, subclass hierarchies, object properties, data properties, and annotations.

## Ontology Structure

### Classes

The ontology defines **15 main classes**, including:

- `Person`
- `Patient`
- `HealthcareProfessional`
  - `Doctor`
  - `Nurse`
- `Hospital`
- `Department`
- `MedicalRecord`
- `Diagnosis`
- `Disease`
- `Treatment`
  - `Surgery`
- `Medication`
- `Appointment`
- `LaboratoryTest`

### Properties

The ontology includes **40 properties**, divided into:

#### Object Properties
Used to represent relationships between individuals, such as:
- patient–doctor relationships
- diagnoses and treatments
- organizational structures
- appointments and laboratory tests

Examples:
- `hasDiagnosis`
- `prescribesTreatment`
- `worksAt`
- `treatedBy`
- `hasAppointment`

#### Data Properties
Used to represent literal values and attributes, such as:
- names and identifiers
- dates and numeric values
- medical notes and test results

Examples:
- `hasName`
- `hasAge`
- `hasDiagnosisDate`
- `hasDosage`
- `hasTestValue`


