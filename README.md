
## 🚀 Key Features

- 📄 Medical document processing
- 📊 Interactive medical dashboard
- 🕒 Patient medical timeline
- 🕸️ Medical relationship graph
- 💊 Medication journey tracking
- 🧪 Laboratory result trends
- ⚠️ Conflict detection
- 🔍 Source and evidence tracking
- 📁 Document upload support
- 🖥️ User-friendly interface
- 🔗 Relationship analysis between medical entities

---

## 🎯 Problem Statement

Medical information is often stored across multiple documents such as prescriptions, laboratory reports, discharge summaries, and patient records.

Manually reviewing these documents can take significant time and important relationships between information may be difficult to identify.

MedIntel addresses this problem by organizing information from different medical documents into a single structured dashboard.

---

## 💡 Proposed Solution

MedIntel processes medical documents and converts important information into structured data.

The system presents the extracted information through:

- Medical timelines
- Medication journeys
- Laboratory trends
- Relationship graphs
- Conflict information
- Source document references

This provides a unified view of information contained in multiple medical documents.

---

## 🧠 How MedIntel Works


             Medical Documents
                    │
                    ▼
           Document Processing
                    │
                    ▼
         Information Extraction
                    │
                    ▼
        Entity & Relationship Analysis
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
      Timeline   Medications  Lab Results
          │         │         │
          └─────────┼─────────┘
                    ▼
            Conflict Detection
                    │
                    ▼
           Interactive Dashboard
````

---

## 📊 Main Modules

### 1. Dashboard

Provides an overview of the processed medical information.

It displays important statistics such as:

* Number of documents
* Extracted entities
* Medications
* Laboratory tests
* Detected conflicts

---

### 2. Medical Timeline

The timeline displays important medical events chronologically.

Example:


   │
   ├── Diagnosis
   ├── Medication
   └── Laboratory Result
        │
        ▼
2026-02-15
   │
   └── Medication Update
        │
        ▼
2026-04-15
   │
   └── Laboratory Result
```

This makes it easier to understand how medical information changes over time.

---

### 3. Relationship Graph

The relationship graph shows connections between different medical entities.

Example:

```text
             Patient
                │
       ┌────────┼────────┐
       ▼        ▼        ▼
   Diagnosis  Medication  Lab Test
       │        │          │
       │        │          ▼
       │        │      Lab Result
       │        │
       └────────┘
```

This helps users visually explore relationships between medical information.

---

### 4. Medication Journey

The medication module tracks medication information over time.

It can display:

* Medication name
* Dosage
* Frequency
* Start date
* Medication status
* Source document

---

### 5. Laboratory Trends

The laboratory module displays laboratory values recorded at different dates.

For example:

```text
HbA1c

8.2% ──────────●
                \
                 \
                  ●──────── 7.1%

      Jan 2026       Apr 2026
```

The system can help users observe changes in recorded laboratory values.

---

### 6. Conflict Detection

The system identifies information that may require further review.

For example:

```text
⚠️ Medication Review

Multiple medications are documented
across different prescriptions.

→ Metformin
→ Glimepiride

Further review may be required.
```

The system does not replace professional medical judgment.

---

### 7. Source Documents

The system keeps track of the source document associated with extracted information.

Example:

```text
Entity: HbA1c
Value: 8.2%
Date: 2026-01-10

Source:
lab_report.txt


##  Technologies Used

```text
Frontend:
HTML
CSS
JavaScript

Backend:
Python
Flask

Visualization:
Vis-Network



