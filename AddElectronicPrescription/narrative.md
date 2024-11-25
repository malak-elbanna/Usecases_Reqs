### Use Case Name:
    Add Electronic Prescription for a Patient

### Actors:
    Doctor
### Stakeholders:
    Patient, Pharmacy
### Pre-conditions:
    The doctor must be logged in and autherized to add prescriptions.
    The patient must have an active record in the EMR system.
### Post-conditions:
    Prescription is added to the EMR database and accessible to pharmacies.
    Patient is notified of the new prescription.
#### Main Scenarios:
    1. The doctor accesses the patient's medical record on the EMR system.
    2. The doctor goes to the "Add Prescription" section.
    3. The doctor enters the prescription details including any special comments.
    4. The system validates the prescription for any typos, conflicts, or critical conditions.
    5. The doctor confirms and submits the prescription.
    6. The system stores the prescription in the EMR database and attach it to the patien's record.
    7. The system notifies the patient about the newly added prescription on the portal.
    8. The system makes the prescription accessible to the integrated pharmacies.
### Alternate Scenarios:
    1a. Patient not found
        System Action: The system alerts the doctor that the patient record is missing.
        Resolution: The doctor requests the admin to add a new patient record.
    4a. Presciption conflicts found
        System Action: The system alerts the doctor about detected conflicts (e.g., allergies).
        Resolution: - The doctor views the alert message.
                    - If it's valid, the doctor makes the necessary changes.
                    - If invalid, the doctor declines the alert.
    5a.The system encounters an issue (e.g., timeout or lost connection) during account creation.
        System Action: The system notifies the user of the issue and asks them to try again later.
        Resolution: The user retries after the connection is restored or the system issue is resolved.
