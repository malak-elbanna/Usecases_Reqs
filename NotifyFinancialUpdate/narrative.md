### Use Case name:
    Notify Financial Updates
### Actors:
    Patient, Hospital Staff, MIS system, Financial system
### Stakeholders:
    Patients, Billing Department, Hospital Administrators
### Pre-conditions:
    The patient is registerd and has completed a financial transaction
### Post-condtions:
    The patient and the hospital are notified of the successful payment 
### Main Scenario:
    1. The Patient makes a payment or the Financial System processes a financial transaction (e.g., payment confirmation or due payment).
    2. The MIS System receives the transaction details from the Financial System and triggers the notification process.
    3. Patient Notification:
        a. If the payment is successful, the Patient receives a notification confirming the payment.
        b. If the Patient has pending dues, they receive a notification with the outstanding balance.
        c. If the Patient has not yet made a payment, a payment reminder is sent.
    4. Staff Notification:
        a. The Hospital Staff is notified about the patient’s successful payment, pending dues, or reminders to follow up on payment.
        b. The MIS System sends an alert to the Billing Department regarding any payment issues, pending balances, or discrepancies.
    5. The MIS System maintains a record of all notifications sent, ensuring a transparent and audit-friendly trail.

### Alternative flow:
    1. No Payment Made:
        System Action: If no payment is made or processed, the system sends a pending dues notification to the Patient and a reminder notification.
        Resolution: The Patient is encouraged to make the payment. The Staff is informed about the status for follow-up.