
### Use Case Name:
    Access Medical History  

### Actors:
    Admin, Medical Staff  

### Stakeholders:
    Patient, Hospital  

### Pre-conditions:
    - The Admin,Medical Staff must be logged into the system with appropriate permissions.  
    - The patient must have an existing record in the EMR system.  

### Post-conditions:
    - The system displays the patient’s complete medical history.  
    - Access is logged in the audit trail for compliance and security.  

#### Main Scenarios:
    1. The user selects the "Access Medical History" option on the system dashboard.  
    2. The user enters the patient’s unique identifier (e.g., national ID or registration number).  
    3. The system retrieves the patient’s medical history, including diagnoses, treatments, prescriptions, allergies, and immunizations.  
    4. The user reviews the retrieved information.  

#### Alternate Scenarios:
    2a. Patient not found:  
        - an error message is displayed: "no record was found"  
        - The user verifies the entered ID and retries.  

  