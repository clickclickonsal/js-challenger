Family Registration
===================

This application will test some basic form building skills. It should not be over-engineered
and should be solved as simple as you can with ES6 syntax. The application captures
information about a family that is registering for healthcare.
Develop a UI for building up the family details from the perspective of one of the parents.

Task
----

You have been given an HTML page with a form and a placeholder for displaying
a registration.

In the given index.js file, replace the "Your code goes here" comment with JavaScript that can:

* Validate data entry (age is required and > 0, relationship is required)
* Add people to a growing registration list
* Remove a previously added registration from the list
* Display the registration list in the HTML as it is modified
* Serialize the registration as JSON upon form submission as a fake trip to the server

Notes
-----

Do not modify the given index.html file in any way. You're of course still allowed to modify the DOM through Javascript.

The display of the registration list is up to you.

On submission, put the serialized JSON in the provided "debug" DOM element and display that element.

After submission the user should be able to make changes and submit the registration again.

You do not need to add validations around anything other than the age and relationship requirements described above. It's ok for someone to add 35 parents.

The focus here is on the quality of your JavaScript, not the beauty of your design. The controls you add around viewing and deleting
registration members should be usable but need not be much to look at.
