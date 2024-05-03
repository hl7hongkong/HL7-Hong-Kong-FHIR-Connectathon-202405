# Exercise 1 - Problem

1. Fill in the FHIR `Condition.code.coding` data fields in the ([PROB_Exercise.json](PROB_Exercise.json)) with below given condition information.

  ```
  SNOMED CT Code: 55822004
  Preferred Term: Hyperlipidemia
  HKCTT Term ID: 4323
  eHR Description: Hyperlipidaemia
  ICD10-2001 Code: E78.5
  ICD10-2001 Full Name: Hyperlipidaemia, unspecified
  ```

Update the below JSON code block.

  ```json
  {
    "system": "[(E3P1Q1) System of the condition]",
    "code": "[(E3P1Q2) Codex of the condition]",
    "display": "[(E3P1Q3) Description of the condition]"
  }
  ```

2. [E3P1Q4] If 3 diagnoses were made in the 1st visit (record key: V1) and 2 diagnoses were made in the 2nd visit (record key: V2). If we put all diagnoses into a single FHIR Bundle, how many entries should be found in the FHIR `Composition.section.entry` array?

  (A) 2

  (B) 3

  (C) 5

  (D) 6

Answer: &lt;PUT YOUR ANSWER HERE&gt;
