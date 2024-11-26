
### Use Case Name:
    Search for Medical Records  

### Actors:
    Admin  

### Stakeholders:
    Patient, Hospital  

### Pre-conditions:
    - The Admin must be logged into the system with appropriate permissions.  

### Post-conditions:
    - The system displays a list of records matching the search criteria.  
    - The action is logged in the audit trail for accountability.  

#### Main Scenarios:
    1. The Admin selects the "Search Medical Records" option from the menu.  
    2. The Admin enters search criteria, such as patient ID, name, date range, or diagnosis keywords.  
    3. The system queries the database and displays matching records in a list.  
    4. The Admin selects a record to view detailed information.  

#### Alternate Scenarios:
    2a. Invalid input:  
        The system displays an error message: "Invalid input. Please provide at least one search criterion."  
        The Admin corrects the input and retries.  

    3a. No matching records:  
        The system displays: "No records found matching the criteria."  
        The Admin adjusts the search parameters and retries.  

