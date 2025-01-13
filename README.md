# Med-Track
A Hospital Management System (HMS) built with Django is a web-based application designed to streamline and manage hospital operations efficiently. It leverages Django's robust framework to offer features such as patient registration, appointment scheduling, medical record management, staff management, and billing.

## Features
:: Admin Features
:: -----------------
:: Sign up and log in without requiring approval.
:: Manage doctors:
::   - Register, view, approve, reject, or delete doctor accounts.
::   - Approve applications from doctors seeking jobs at the hospital.
:: Manage patients:
::   - Admit, view, approve, reject, or discharge patients.
::   - Discharge patients upon treatment completion.
:: Generate and download invoices in PDF format:
::   - Include medicine costs, room charges, doctor fees, and additional charges.
:: Manage appointments:
::   - View, book, approve, or reject appointment requests from patients.

:: Doctor Features
:: -----------------
:: Apply for hospital jobs (requires admin approval to log in).
:: Access assigned patient details:
::   - View patient symptoms, names, and contact numbers.
:: View the list of discharged patients under their care.
:: Manage appointments:
::   - View appointments scheduled by the admin.
::   - Remove appointments after completing them.

:: Patient Features
:: -----------------
:: Create an account for hospital admission (requires admin approval to access).
:: View assigned doctor details:
::   - Access specialization, contact number, and address.
:: Manage appointment requests:
::   - Book appointments (requires admin approval).
::   - Check the status of appointments (pending/confirmed).
:: View and download invoices:
::   - Access invoices in PDF format after discharge by the admin.
