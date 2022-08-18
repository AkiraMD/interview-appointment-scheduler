# Appointment Scheduler Service
“As a patient, I would like to book an appointment with an available clinician when its convenient for me to do so. “

Your task is to prototype the backend service for an appointments scheduler application given the following input and outputs:

**Input**:
Please use the following mock data to power your API

**Acceptance Criteria**:
* As a user, I want to be able to see which clinicians are available in my province
* As a user, I want to be able to see what 30min slots are available to me based on a particular clinician
* As a user, I want to be able to book an available slot
* As a user, I want to see all my upcoming confirmed appointments
* As a clinician, I want to see upcoming booking requests
* I should not be able to book in the past

**Expectations**:
* Create a database schema to support this API service using the data above
* Should be built using node
* Should include a data migration using the input data
* All tests should pass and be representative of the acceptance criteria but should not just be the happy path
* Should include instructions on how to setup, run and test.

**Assumptions**:
* Do not worry about authentication, lets assume the user and clinicians are already authenticated.
