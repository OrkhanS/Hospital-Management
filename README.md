# Hospital Management

The Hospital management system provides a well-tuned management system that helps to automate the workflow and activities of a hospital. This system manages the administrative and financial activities of the hospital along with all the medical facilities. There are four users in this system- Admin, Doctor, Patient. Admin can manage all the other users of the system and maintains the database of the system. Whole system supports the vital activities of daily tasks and interactions in a smooth manner.


## Installation

```bash

```

## Requirements

Patients:
1. Patients should be able to create their own accounts.
2. Patients should be able to log in to the system to use its functionalities.
3. Patients should be able to check the timetable of the doctor by typing its id or name.
4. Patients should be able to filter the doctors by their own categories.
5. Patients should be able to request to the doctors’ timetables.
6. Patients should be able to check the status of their requests.
7. Patients should be able to cancel or change the request unless there are less than 24 hours to the appointment.
8. Patients should be able to report the doctor to the admin in case of decline without a description.
9. Patients should be able to see detailed view of their requests list (with details added by doctor, if there is).
10. Patients should be able to remove their accounts unless there are unfinished appointments.
11. Patients should be able to change the email address and passwords in case they want to.


Doctors:
1. Doctors should be able to log in to the system by the given username and password by the admin.
2. Doctors should be able to accept or decline the requests, also should be able to write description.
3. Doctors should be able to add, delete and modify the activities to their weekly timetables.
4. Doctors should be able to search for other doctors and get the details of them.

Admins:
1. Admins also log in to the system with the same interface.
2. Admins should be able to add or delete doctors from the system.
3. Admins should be able to add or remove categories from the system.
4. Admins should be able to block or unblock the patients in the system.

## Class diagram
![alt text](https://github.com/OrkhanS/Hospital-Management/blob/main/UML.jpg)

## Simple Sequence Diagram for only Patient
#### Diagrams for Admin and Doctor can be done similarly.
![alt text](https://github.com/OrkhanS/Hospital-Management/blob/main/SequenceDiagramPatient.png)


## License
[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/DAVFoundation/captain-n3m0/blob/master/LICENSE)
