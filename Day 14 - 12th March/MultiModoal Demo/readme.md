# Multimodal Document Processing App

## Overview

This project is a simple **multimodal AI application** that processes different types of inputs such as **audio, images, documents, and text**.
It extracts useful information from these inputs and converts the data into a **structured tabular format** that can be saved as a CSV file.

The system uses the **OpenAI API** to understand and extract information from multimodal inputs.

---

## Features

* Upload and process **images** (prescriptions, bills, receipts)
* Process **audio files** (voice notes, spoken prescriptions)
* Handle **text or document inputs**
* Extract structured information such as:

  * document type
  * items
  * quantity
  * price
  * total amount
* Convert extracted data into a **table**
* Export results as a **CSV file**

---

## Supported Inputs

The app can process multiple input types:

| Input Type | Example                     |
| ---------- | --------------------------- |
| Image      | Prescription photo, invoice |
| Audio      | Doctor voice notes          |
| Text       | Typed notes                 |
| Document   | Bills or receipts           |

---

## Workflow

1. Upload files (image, audio, or document)
2. The system analyzes the input using AI
3. Information is extracted and converted to structured data
4. Data is displayed in a table
5. Results are exported as a CSV file

---

## Installation

Install the required libraries:

```
pip install openai pandas pillow
```

---

## Usage

1. Run the Python script or notebook
2. Upload files when prompted
3. The system extracts information automatically
4. The output table is generated
5. A CSV file containing the processed data is saved

---

## Example Output

| Document Type | Item        | Quantity | Price |
| ------------- | ----------- | -------- | ----- |
| Prescription  | Amoxicillin | 10       | $15   |
| Bill          | Paracetamol | 2        | $5    |

---

## Applications

This type of system can be used for:

* Medical prescription digitization
* Receipt and invoice processing
* Expense tracking
* Insurance claim automation
* Document management systems

---

## Future Improvements

* Support for **PDF documents**
* Real-time document scanning
* Integration with databases
* Web interface for uploads
* Advanced analytics and reporting

---

## License

This project is for **educational and demonstration purposes**.
