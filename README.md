# Clinic-Management
This project is a complete Healthcare Management System built using Oracle APEX, integrating SQL and PL/SQL to manage patients, doctors, appointments, treatments, prescriptions, billing, and analytics. The system demonstrates strong skills in database design, business logic implementation, and building interactive APEX pages.

The solution includes multiple functional modules:

1. Patient Management

Interactive Report + Form to manage patient records (add/edit/delete).

Dynamic Action triggers a PL/SQL function (CALCULATE_PATIENT_AGE) to auto-display the patient’s age.

2. Doctor Management

Full CRUD operations for doctors.

A specialized report showing doctors with no scheduled appointments.

3. Appointment Scheduling

Interactive Report + Form to view and schedule appointments.

Appointment creation uses the SCHEDULE_APPOINTMENT procedure.

Built-in validation prevents booking conflicts using existing triggers.

4. Treatments & Prescriptions

Validation logic that ensures requested medication does not exceed available stock.

5. Billing & Payments

Interactive billing pages showing treatments and costs.

Adding prescriptions automatically updates stock via triggers.

Bills can be updated, and when marked as Paid, payment date is recorded.

Includes a chart showing Revenue per doctor, using the PL/SQL function GET_TOTAL_REVENUE_BY_DOCTOR.

6. Analytics Dashboard

A multi-region dashboard containing:

Top 3 prescribed medicines

Average treatment cost per specialization

Patients with more than 3 appointments

Revenue by specialization

7. Appointment Calendar

A calendar view on the Home page showing all appointments.

Allows drag-and-drop date changes, doctor updates, and adding new appointments
