### Use Case name:
    Manage Pharmacy Charges
### Actors:
    Patient, Pharmacy staff, MIS system, Financial system
### Stakeholders:
    Hospital Administration, Patients, Pharmacy staff
### Pre-conditions:
    The patient must be registered in the system and the prescription must be processed by the pharmacy staff
### Post-conditions:
    - The pharmacy charge is successfully created, updated, and linked to the patient’s billing account.
    - The payment for the pharmacy charges is processed and recorded in the financial system.
### Main Scenario:
    1. The pharmacy staff enters the prescription details into the system and creates a charge for the patient.
    2. The pharmacy staff updates the charges if necessary, based on the latest prescription changes.
    3. The pharmacy charge is linked to the patient's billing account, ensuring that it is added to the overall bill.
    4. The patient makes the payment for the pharmacy charges. The system processes the payment and updates the billing records accordingly.
### Alternative flow:
    1. Invalid Prescription
        Condition: If the prescription entered by the pharmacy staff is invalid (e.g., missing medication or incorrect dosage).
        System Action: The system displays an error message indicating that the prescription is invalid.
        Resolution: The pharmacy staff must correct the prescription details before proceeding with the charge creation.