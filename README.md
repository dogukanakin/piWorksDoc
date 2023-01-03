# piWorksDoc



User Management User Interface Specification

Purpose:

This user interface specification document outlines the requirements and design details for the user management pages in the application. The first page should allow the user to create new users, view users, and filter the displayed users by enabled status. The second page should allow the user to enter the details of a new user .

Requirements:

The first page should display a list of users, including their ID, username, and email and enabled status.
The list should be filterable by enabled status, with an option to show only enabled users or only disabled users.
The first page should include a button to create a new user.
When the user clicks the button to create a new user, the second page should be displayed.
The second page should include fields for the user to enter the following details:
username
display name
phone
email
user roles (guest, admin, super admin)
enabled (checkbox)
The second page should include a submit button to save the new user details.
UI Components:

First page:
•	New user button: This button will trigger the display of the second page for creating a new user.
•	Hide disabled users toggle: This toggle will filter the list of users to show only enabled users or only disabled users.
•	User list: This table will display the list of users, including their ID, username, and email. The table will be formatted as shown in the example provided, with a column for each field and a filter and sort button next to each field.

Second page:
•	Username field: This field will allow the user to enter the username for the new user.
•	Display name field: This field will allow the user to enter the display name.
•	Phone field: This field will allow the user to enter the phone number.
•	Email field: This field will allow the user to enter the email address for the new user.
•	User roles dropdown: This dropdown will allow the user to select the user role (guest, admin, super admin) for the new user.
•	Enabled checkbox: This checkbox will allow the user to specify whether the new user is enabled.
•	Save User button: This button will save the new user details and return to the first page. If any required field is left blank, a warning will be displayed.

Behavior:
•	When the first page loads, the user list should be displayed with all users shown, and the hide disabled users toggle should be set to "off."
•	When the user clicks the new user button on the first page, the second page should be displayed with all fields blank, ready for the user to enter the details of a new user.
•	When the user clicks the field filter and sort buttons on the first page, the user list should be filtered and sorted according to the corresponding field.
•	When the user clicks the hide disabled users toggle on the first page, the user list should be filtered to show only enabled users or only disabled users.
•	When the user clicks the save user button on the second page, the new user details should be saved and the user should be returned to the first page. If any required field is left blank, a warning should be displayed.
•	When the first page is displayed, it should show the list of users with all users visible, sorted by ID in ascending order.
•	If an error occurs while saving the new user details on the second page, a warning should be displayed to the user indicating the error.

![Uploading image.png…]()
