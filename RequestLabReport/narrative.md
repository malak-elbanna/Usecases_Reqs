### Use Case ID
    UC_003

### Use Case Name
    Request Lab Report

### Actors
    Patient

### Stakeholders
    Patient
    Hospital Administration
    Laboratory Personnel

### Pre-conditions
    - The patient must be registered on the portal and logged in.
    - The patient must have completed at least one laboratory test.
    - The laboratory system must be integrated with the portal to handle report requests.

### Main Scenario
    1. The patient logs into the portal and navigates to the "Manage Lab Tests" page.
    2. The system displays a list of all available labs where the patient may have undergone tests.
    3. The patient selects the laboratory where the test was conducted.
    4. The system prompts the patient to enter the serial number or unique identifier of the test.
    5. The patient submits a request for the lab report.
    6. The system notifies the laboratory personnel about the request.
    7. Once the lab report is ready, the laboratory personnel upload or push the report to the portal.
    8. The patient receives a notification and can view/download the lab report.

### Alternate Scenarios

    System Unavailable
    The system displays a message indicating that the system is currently unavailable 

    Test Report Already Requested
    The system displays a message indictaing that the test report request has already been submitted

    3a. Laboratory Not Selected
    The system displays a prompt: "Please select a laboratory before requesting the report."
    
    4a. Invalid Test Serial Number
    The system displays an error message: "Invalid test identifier. Please check and re-enter the correct serial number."


### Post-conditions
    The lab report request is successfully submitted and logged in the system.
    The patient is notified when the lab report is ready for viewing or download.
    
