# QAAnalystProject

## What questions would you ask in order to clarify requirements?

- Are all fields mandatory (Email, First name and last name). If not which fields are mandatory?
- The fields accept special characters like space, comma etc?
- Should the system validate the email? For example search for an @ ?
- The temporary password needs to be change shortly, how shortly (how much time? )
- If the user fills a field with wrong data (for example 5 characters), what should happen (shows an error message)?
- The mockup of the homepage doesn't show the email, where should it be?
- All fields must have up to 30 characters but the database doens't allowed. What shoud be changed? The data base or the limit?
- The 3 second limit it's an expectation or a hard limit?

## Specify 5 test cases to test this requirement

- Fill all the fields with valid Data and click in the save button and expect that the user got created correctly (happy path)
- Do a login and validate if the homepage shows the email, and first an last name (happy path)
- Validate that the form follows the mockup (have 3 fields: email, first and last name, and 2 buttons: save and cancel) (happy path)
- Fill the form with an invalid email (less than 6 characters or more than 30 characters) and expect that the user is not created.
- Fill all the fields with valid Data and click in the cancel button and expect that the user doesn't get created
