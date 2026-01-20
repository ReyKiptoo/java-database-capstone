# User Story Template

**Admin User Story Login:**
_As an admin, I want to log in to the portal with username and password, so that I can manage the platform securely._

**Acceptance Criteria:**
1. The system validates that the username and password match a record in the Admin JPA Entity
2. The user is redirected to the AdminDashboard upon successful authentication
3. An error message is displayed for incorrect credentials, and access is denied

**Priority:** [High]
**Story Points:** [3]

**Admin User Story Logout:**
_As an admin, I want to log out of the portal, so that I can protect system access._

**Acceptance Criteria:**
1. The user should be logged in
2. The back button on browser should not log the user back in.
3. All sessions should be cleared once the user logs out.

**Priority:** [High]
**Story Points:** [3]

**Admin User Story - Add doctors:**
_As an admin, I want to add doctors to the portal so that patients can be able to book them._

**Acceptance Criteria:**
1. There is a form to be added to provide the doctor details.
2. The admin can save the doctors details and they are immediately available for booking.

**Priority:** [Medium]
**Story Points:** [2]

**Admin User - Delete doctor:**
_As an admin, I want to delete doctor profile from the portal._

**Acceptance Criteria:**
1. The admin must be logged in.
2. The doctor must be an existing doctor.
3. The doctor should not have any pending appointments from one or more patients.

**Priority:** [Medium]
**Story Points:** [2]

**Admin User Story - Run Query:**
_As an admin, I want to run a query to know the total number of appointments per month and to also track the usage statistics of the platform._

**Acceptance Criteria:**
1. The admin should be logged in.
2. If the query fails to run becuase of any reason the admin should be notified.

**Priority:** [Medium]
**Story Points:** [2]

**Patient User Story - View Doctors:**
_As a patient I want to view a list of doctors without loggin in to explore options without registering._

**Acceptance Criteria:**
1. The system should have a list of doctors on the home page. 
2. The patient should have full access to the list with search to enable easy retrieval.


**Priority:** [High]
**Story Points:** [3]

**Patient User Story - Sign UP:**
_As a patient I want to sign up using email and password to be able to book appointments._

**Acceptance Criteria:**
1. The system should validate the email and password (and any other data) with all validation criteria.

**Priority:** [High]
**Story Points:** [3]

**Patient User Story - Log In:**
_As a patient I want to log in using email and password to manage bookings._

**Acceptance Criteria:**
1. The system should allow the patient once logged in to make a booking.
2. If the patient has a previous booking they should be able to manage it - cancel, postpone etc.

**Priority:** [Medium]
**Story Points:** [2]

**Patient User Story - Log Out:**
_As a patient I want to log out of the system to secure the account._

**Acceptance Criteria:**
1. The system should clear all the sessions of the patient.
2. The system should prevent the back button from giving the user access once they are logged out.

**Priority:** [High]
**Story Points:** [3]

**Patient User Story - Hour Long Appoinment:**
_As a patient I want to login and book an hour long appointment with a doctor to consult._

**Acceptance Criteria:**
1. The system should ensure that the doctor is available for the specified period by the patient.

**Priority:** [Medium]
**Story Points:** [2]

**Patient User Story - View Appintments:**
_As a patient I want to view my appointments so that I can plan accordingly._

**Acceptance Criteria:**
1. The portal should give a list of all the bookings for the patient.
2. If there are not bookings yet the portal should allow the patient to make a booking.

**Priority:** [Medium]
**Story Points:** [2]

**Doctor User Story - Log In:**
_As a doctor, I want to login to the portal to manage my appointments._

**Acceptance Criteria:**
1. The system should validate the email and password (and any other data) with all validation criteria.
2. If the login is successful the doctor should be able to see all their appointments.

**Priority:** [High]
**Story Points:** [3]

**Doctor User Story - Log out:**
_As a doctor, I want to log out of the portal to secure my account._

**Acceptance Criteria:**
1. The system should clear all the sessions once the user is able to log out.
2. The system should give a successful logout message to the user once they are able to log out.

**Priority:** [High]
**Story Points:** [3]

**Doctor User Story - View Calendar:**
_As a doctor, I want to view my appointment calendar so I can stay organized._

**Acceptance Criteria:**
1. The portal should show all the upcoming appointments of the doctor if any.


**Priority:** [Medium]
**Story Points:** [2]

**Doctor User Story - Mark Unavailability:**
_As a doctor, I want to mark unavailability to inform patients of available slots._

**Acceptance Criteria:**
1. There should be no active appointment for the period that the doctor wants to mark unavailability.

**Priority:** [Medium]
**Story Points:** [2]

**Doctor User Story - Update Profile:**
_As a doctor, I want to update profile with specialization and contact information._

**Acceptance Criteria:**
1. The doctor must not leave any blank specialization or contact information.

**Priority:** [Medium]
**Story Points:** [2]

**Doctor User Story - View Patient Details:**
_As a doctor, I want to view patient details for planning purposes_

**Acceptance Criteria:**
1. The doctor must have appointment from a patient to be able to see their details.

**Priority:** [Medium]
**Story Points:** [2]
