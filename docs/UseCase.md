# Fully Dressed Use Case: Manage Patient Records

**Use Case Name:** Manage Patient Records
**Actor:** Doctor
**Goal:** Enter, update, and view patient details from an Android phone.

## Preconditions
- Doctor has the Patient Tracker app installed.
- Doctor is logged into the app.

## Postconditions
- Patient details are saved locally on the phone.
- Doctor can search/view the patient’s history later.

## Main Flow (Success Scenario)
1. Doctor launches the app.
2. Doctor selects **“Add New Patient”**.
3. System prompts for patient details (name, disease, medication, date, cost).
4. Doctor enters the data and confirms.
5. System saves the patient record.
6. Doctor can later search patients by name or date.

## Alternate Flow
- If the patient already exists, the system allows updating the patient record.

## Failure Flow
- If mandatory fields (like name or date) are missing, the system shows an error and does not save.
- If data storage fails, the system shows an error message.

