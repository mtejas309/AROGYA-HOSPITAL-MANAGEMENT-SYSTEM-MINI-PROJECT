The management system should have the following features: -

Add a patient’s details to the system whenever there is a new patient admitted.
The patient details should include his/her name, age, gender, Aadhar Card number, contact number, city, address, date of admission,
guardian's name, guardian’s address, guardian’s contact number. Assign a unique id to each patient admitted.
Note: Validate user entered data. Such as
Number of digits in age is 1 or 2 digits.
Aadhar card number should contains 12 digits.
Contact number should contain 10 digits only.

The system can show the list of patients at any point of time. Basically, the system should be dynamic and a real time system.
In other words, it can provide results at any point of time without any delays. Display proper error message if patients list is empty.

Given the unique id assigned to a patient, provide all the details of that patient.
In other words, the system should provide details about a patient using his/her unique id or name.

The system can provide the list of all the patients from a particular city or a state.
Also provide the list of patients belonging to a particular age group.
For example, you can be asked to give the list of patients in the age group 50-60.
Handle NullPointerException if user entered values are empty.

Mark the patient recovered when he starts working fine.

The system should be able to delete the information of a patient when asked to.
Handle NullPointerException if user entered patient id is not present in list.
