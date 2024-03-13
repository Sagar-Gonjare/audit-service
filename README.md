Create User Validation Rule
Ensure that the AddUserRequest object includes all required fields (age, email, password, username). If any of these fields are missing, generate an AddUserResponse object with an error status and a message indicating incomplete data.

Implement Password Encryption Rule
Utilize the encryptionService.encrypt() method to encrypt the password provided in the AddUserRequest object. If encryption fails, set the error status and message in the AddUserResponse object accordingly.

Handle User Addition Success Rule
Upon successful addition of a new user to the Users table in the database, create an AddUserResponse object with a success status and include the user's information in the response.

Manage User Not Found Rule
If a user is not found in the database while searching by user ID, set the error status and message in the AddUserResponse object to indicate that the user was not found.

Process User Found Rule
When a user is found in the database by user ID, generate an AddUserResponse object with a success status and include the user's information in the response.

Enforce Email Format Validation Rule
Verify if the email provided in the AddUserRequest object follows a valid email format. If the email format is invalid, set the error status and message in the AddUserResponse object accordingly.





