### Use Case Name:
    Register a New Patient

### Actors:
    Admin, Patient
### Stakeholders:
    Reception, HIS staff
### Pre-conditions:
    The admin must be logged in and autherized to access the system.
### Post-conditions:
    Patient is added to the centralized EMR database.
#### Main Scenarios:
    1. Request the patient to make an account on the EMR system.
    2. The system gives the patient a unique ID for future correspondence.
    3. The admin should use the ID to access and record the patient's info.
    4. The admin should fill any gaps and add the new patient to the centralized database.
    3. Fill in the profile for the patient.
    4. Save patient's info
### Alternate Scenarios:
    1a. The patient is already found in any of the hospital's databases.
        System Action: The system highlights that the user is already registered and clarifies which database they are on.
        Resolution: - The admin retrieve the data of the patient from the database (including any needed personal info, medical records, and payments).
                    - The admin should check for any missing info and inquire the patient to provide them accordingly.
                    - The admin should fill in the profile and save the patient's info into the EMR database.
                    - The admin gives the patient a unique ID that's generalized across all hospitals systems.
                    - The patient should use this ID to register for an account on the system.
    3,4a.The system encounters an issue (e.g., timeout or lost connection) during account creation.
        System Action: The system notifies the user of the issue and asks them to try again later.
        Resolution: The user retries after the connection is restored or the system issue is resolved.
