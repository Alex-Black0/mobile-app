# mobile-app

The purpose of these services is to add, update, and delete contact objects within the application.

The contact service uses in-memory data structures to support storing contacts (no database required). In addition, there is no user interface for this milestone. You will verify the contact service through JUnit tests. The contact service contains a contact object along with the contact service. The requirements are outlined below.

Contact Class Requirements

The contact object shall have a required unique contact ID string that cannot be longer than 10 characters. The contact ID shall not be null and shall not be updatable.
The contact object shall have a required firstName String field that cannot be longer than 10 characters. The firstName field shall not be null.
The contact object shall have a required lastName String field that cannot be longer than 10 characters. The lastName field shall not be null.
The contact object shall have a required phone String field that must be exactly 10 digits. The phone field shall not be null.
The contact object shall have a required address field that must be no longer than 30 characters. The address field shall not be null.
Contact Service Requirements

The contact service shall be able to add contacts with a unique ID.
The contact service shall be able to delete contacts per contact ID.
The contact service shall be able to update contact fields per contact ID. The following fields are updatable:
firstName
lastName
Number
Address
