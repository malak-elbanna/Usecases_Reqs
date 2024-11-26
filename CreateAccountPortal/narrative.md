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
    1. Patient opens the ERM portal from an app or a web browser. 
    2. Patient selects "Create Account" from the login page.
    3. Patient enters their information (Name, Age, Gender, Address, ...etc).
    4. Patient clicks "Create".
    5. The system validates that the entered data is correct and complete.
    6. System saves the information and notifies the patient that the account is created successfully.
### Alternative Scenario:
    3a. Patient forgets to fill one of the required fields.
        System action: System alerts the patient that a field is missing.
        Resolution: Patient fills the missing field.
    6a. The entered data already exists.
        System action: The system notifies the patient that the entered info already exists.
        Resolution: The patient is prompted to login or select forgot password if needed.
    