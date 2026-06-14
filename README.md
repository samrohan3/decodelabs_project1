# Prompt Engineering Internship – Week 1 Project 1

## Zero-Shot & Few-Shot Data Extraction

### Overview

This project demonstrates the application of Prompt Engineering techniques to extract structured information from unstructured text and convert it into a valid JSON format.

The prompt is designed to perform deterministic data extraction using delimiters, few-shot examples, JSON schema enforcement, and temperature control.

---

## Objective

To design a prompt that can extract candidate information from unstructured text and return it in a structured JSON format while maintaining consistency, accuracy, and proper handling of missing values.

---

## Data Model

```json
{
  "name": "",
  "email": "",
  "phone": "",
  "city": ""
}
```

---

## Prompt Engineering Techniques Used

### 1. Delimiter Usage

Used triple quotes (""") to clearly separate instructions from raw input data.

### 2. Few-Shot Prompting

Provided multiple input-output examples to teach the model the desired extraction pattern.

### 3. Deterministic Output

Forced the model to return only JSON without conversational text.

### 4. Missing Value Handling

Missing fields are returned as null.

---

## Files Included

* Instruction.txt
* Prompt_Text.txt
* Example1_Input.txt
* Example1_Output.json
* Example2_Input.txt
* Example2_Output.json
* Final_Test_Input.txt
* Final_Test_Output.json

---

## Conclusion

This project successfully demonstrates how prompt engineering techniques can transform unstructured text into structured machine-readable JSON data.
