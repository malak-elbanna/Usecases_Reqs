### Use Case Name:
    Book an Appointment
### Actors:
    Patient, Doctor
### Stakeholders:
    Doctor, Reception
### Pre-conditions:
    - The patient is registerd and logged into the ERM system. 
    - The doctor's availability is configured and up-to-date in the system.
### Post-conditions:
    The appointment is booked and a confirmation message is sent to the patient and the doctor.

### Main Scenario:
    1. The patient navigates to the "Book appointment" section.
    2. The patient selects a speciality or searches for a specific doctor.
    3. The system dsiplays the doctors of the selected speciality and their available slots.
    4. The patient selects the appropriate slot.
    5. The patient clicks "Confirm".
    6. The system verifies that the selected slot has no conflicts.
    7. The system updates the schedule and notifies the patient and the doctor.
### Alternative Scenario:
    2a. The searched doctor is not found
        System action: The system displays an error message that the entered data is invalid 
        Resolution: The patient re-enters the name of the doctor or the user scrolls through the displayed doctors of a selected speciality
    6a. The selected appointment has conflicts (double booking)
        System action: The system alerts the patient that the selected time slot is no longer available
        Resolution: 
            - The system displays suggested time slots
            - The patient searches for another available time slot