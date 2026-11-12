# Example: Max Mustermann-Testpatient - MII Implementation Guide Ophthalmologie v2028.0.0-alpha.1

* [**Inhaltsverzeichnis**](toc.md)
* [**Artefaktübersicht**](artifacts.md)
* **Example: Max Mustermann-Testpatient**

## Beispiel Patient: Example: Max Mustermann-Testpatient

-------

**German**

-------

Profile: [Example Patient — template starter](StructureDefinition-example-patient.md) version: 2028.0.0-alpha.1

Security Label: [test health data (Details: ActReason code HTEST = 'test health data')](http://terminology.hl7.org/7.3.0/CodeSystem-v3-ActReason.html)

Max Mustermann-Testpatient Male, DoB: 1990-01-01

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "ExamplePatientInstance",
  "meta" : {
    "extension" : [{
      "extension" : [{
        "url" : "packageId",
        "valueId" : "de.medizininformatikinitiative.kerndatensatz.ophthalmologie"
      },
      {
        "url" : "version",
        "valueString" : "2028.0.0-alpha.1"
      },
      {
        "url" : "uri",
        "valueUri" : "https://www.medizininformatik-initiative.de/fhir/modul-ophthalmologie"
      }],
      "url" : "http://hl7.org/fhir/StructureDefinition/package-source"
    }],
    "profile" : ["https://www.medizininformatik-initiative.de/fhir/modul-ophthalmologie/StructureDefinition/example-patient|2028.0.0-alpha.1"],
    "security" : [{
      "system" : "http://terminology.hl7.org/CodeSystem/v3-ActReason",
      "code" : "HTEST",
      "display" : "test health data"
    }]
  },
  "name" : [{
    "family" : "Mustermann-Testpatient",
    "given" : ["Max"]
  }],
  "gender" : "male",
  "birthDate" : "1990-01-01"
}

```
