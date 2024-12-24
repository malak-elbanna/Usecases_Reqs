### Use Case Name:
    Book an Appointment
### Actors:
    Patient
### Stakeholders:
    Doctor, Reception
### Pre-conditions:
    - The patient is registerd and logged into the ERM system. 
    - The doctor's availability is configured and up-to-date in the system.
### Post-conditions:
    The appointment is booked and a confirmation message is sent to the patient and the doctor.

### Main Scenario:
    1. The patient logs into the EMR system and navigates to the "Book Appointment" section.
    2. The patient selects a specialty or searches for a specific doctor.
    3. The system displays available doctors and time slots for the selected specialty.
    4. The patient chooses a suitable time slot from the displayed options.
    5. The patient selects the payment method (e.g., cash, insurance, or card).
    6. The patient clicks "Confirm" to finalize the booking.
    7. The system verifies that the selected slot is conflict-free and available.
    8. The system updates the schedule to include the new appointment.
    9. The system sends a confirmation notification to both the patient and the doctor.
### Alternative Scenario:
    2a. The searched doctor is not found
        System action: The system displays an error message that the entered data is invalid 
        Resolution: The patient re-enters the name of the doctor or the user scrolls through the displayed doctors of a selected speciality
    6a. The selected appointment has conflicts (double booking)
        System action: The system alerts the patient that the selected time slot is no longer available
        Resolution: 
            - The system displays suggested time slots
            - The patient searches for another available time slot