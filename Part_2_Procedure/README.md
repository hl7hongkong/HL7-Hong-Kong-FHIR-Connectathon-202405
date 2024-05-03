# Exercise 2 - Procedure

1. [E3P2Q1] Which of the following choice is the best way to represent the Level 3 'Recognised Terminology' in FHIR JSON?

  (A)
  ```json
  {
    "system": "https://snomed.org/sct",
    "code": "726426008",
    "display": "Lobectomy of lower lobe of left lung"
  }
  ```

  (B)
  ```json
  {
    "system": "SNOMED CT",
    "code": "726426008",
    "display": "Lobectomy of lower lobe of left lung"
  }
  ```

  (C)
  ```json
  {
    "system": "https://ehealth.gov.hk/HKCTT",
    "code": "23815",
    "display": "Lobectomy of lung - left lower lobe"
  }
  ```

  (D)
  ```json
  {
    "system": "HKCTT",
    "code": "23815",
    "display": "Lobectomy of lung - left lower lobe"
  }
  ```

Answer: &lt;PUT YOUR ANSWER HERE&gt;

2. Find out the actual field values from the provided `Procedure` resource ([PX_Exercise.json](PX_Exercise.json)) and update this file.

  |Question|Field Name|Description|Value|
  |:--|:--|:--|:--|
  |E3P2Q2|Link to recognized terminology coding system which indicate the [Procedure performed - recognised terminology name]|Name of the recognised terminology / classification from which the procedure performed is referenced to|&lt;PUT YOUR ANSWER HERE&gt;|
  |E3P2Q3|[Procedure performed identifier – recognised terminology]|Unique identifier of the procedure performed in the recognised terminology|&lt;PUT YOUR ANSWER HERE&gt;|
  |E3P2Q4|[Procedure performed description - recognised terminology]|The description of the procedure performed in the recognised terminology. It should be the corresponding description of the selected [Procedure performed identifier - recognised terminology]|&lt;PUT YOUR ANSWER HERE&gt;|
  |E3P2Q5|Link to local terminology coding system|--|&lt;PUT YOUR ANSWER HERE&gt;|
  |E3P2Q6|[Procedure performed local code]|Local code created by the healthcare provider for the procedure performed|&lt;PUT YOUR ANSWER HERE&gt;|
  |E3P2Q7|[Procedure performed local description]|Local description created by the healthcare provider for the procedure performed|&lt;PUT YOUR ANSWER HERE&gt;|
