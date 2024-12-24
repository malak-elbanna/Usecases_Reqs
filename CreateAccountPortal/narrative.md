### Use Case Name:
    Create Account on Portal
### Actors:
    Patient
### Stakeholders:
    Hospital
### Pre-conditions:
    - The patient is not already registered into the system.
    - The EMR is available and functional.
### Post-conditions:
    The patient's account is created successfully.
### Main Scenario:
    1. Patient opens the EMR portal using a mobile app or web browser.
    2. Patient selects "Create Account" from the login page.
    3. Patient fills the required fields and enters their information, including:
    4. Personal details (Name, Age, Gender, Address, etc.).
    5. Health insurance information.
    6. Patient clicks "Create" to submit their details.
    7. System validates the entered data for completeness and correctness.
    8. System saves the patient's information and creates the account.
    9. System notifies the patient with a confirmation message: "Account created successfully."
### Alternative Scenario:
    3a. Patient forgets to fill one of the required fields.
        System action: System alerts the patient that a field is missing.
        Resolution: Patient fills the missing field.
    6a. The entered data already exists.
        System action: The system notifies the patient that the entered info already exists.
        Resolution: The patient is prompted to login or select forgot password if needed.
    