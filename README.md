# 🎓 Student Entry Form — Excel VBA Automation

A smart and user-friendly **Student Entry Form built using Microsoft Excel and VBA**.

This project demonstrates how Excel can be transformed from a simple spreadsheet into a structured **data-entry and validation application** using VBA automation.

---

## 🚀 Project Overview

The Student Entry Form is designed to simplify student data collection while reducing manual errors and duplicate records.

The form includes automated Student ID generation, multi-select subjects, input validation, duplicate detection, and intelligent user prompts.

---

## ✨ Key Features

- 🔢 Auto-generated Student ID
- 🔒 Protected Student ID field
- 👤 Student information entry
- 🚻 Gender single-select dropdown
- 📚 VBA-based multi-select Subjects dropdown
- 🚫 Prevents duplicate subject selection
- ➖ Allows individual subject deselection
- 🧹 Allows clearing all selected subjects
- ⚠️ "Select None" confirmation
- 📐 Automatic Subjects field adjustment
- 📱 10-digit Mobile Number validation
- ☎️ 10-digit Landline validation
- ❗ Mandatory field validation
- 🧹 Smart Clear button
- 🔍 Duplicate student detection
- 💬 User-friendly validation messages
- 💾 Student record submission to Excel data table

---

## 🛠️ Technologies Used

- Microsoft Excel
- VBA (Visual Basic for Applications)
- Excel Data Validation
- Excel Tables
- VBA Automation
- Form Controls
- Input Validation

---

## 📋 Student Information

The form collects information such as:

- Student ID
- Student Name
- Address
- Age
- Gender
- Mobile Number
- Landline Number
- Subjects

---

## 🔐 Validation Rules

| Field / Feature | Validation |
|---|---|
| Student ID | Automatically generated and not editable |
| Student Name | Mandatory |
| Gender | Single selection |
| Subjects | Multiple selections allowed |
| Subjects | Duplicate values prevented |
| Subjects | Individual values can be removed |
| Subjects | All values can be cleared |
| Mobile | Exactly 10 digits |
| Landline | Exactly 10 digits |
| Student Record | Duplicate detection |
| Clear Button | Checks whether data exists before clearing |

---

## 📚 Subject Multi-Select

One of the main features of this project is the **multi-select Subjects field**.

Users can select multiple subjects from the dropdown, for example:

`Mathematics, Physics, Chemistry, Computer Science`

The VBA logic ensures that:

- Duplicate subjects cannot be selected.
- Individual subjects can be removed.
- All subjects can be cleared.
- "Select None" is handled appropriately.
- Longer selections remain visible through automatic field adjustment.

---

## 🔄 Application Flow

```text
Open Student Entry Form
          ↓
Enter Student Details
          ↓
Student ID Generated Automatically
          ↓
Select Gender
          ↓
Select Multiple Subjects
          ↓
Validate Input
          ↓
Check Existing Student Record
          ↓
 ┌───────────────┐
 │ Validation OK │
 └───────┬───────┘
         ↓
   Save Student Record
         ↓
   Excel Data Table
