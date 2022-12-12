GT-3
User should be able to Log In using phone number

-
Automation
Automated
Status
Actual
Pre-conditions
Existing account

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on “Log in” button
Input data
Expected result Log in page should be displayed
Step 3
Action Type your phone number
Input data
Expected result You should receive code by text message
Step 4
Action Input received code
Input data
Expected result User should land on dashboard page



GT-4
User should not be able to log in without phone number

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Go to homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click “Log In” button
Input data
Expected result Log In page should be displayed
Step 3
Action Click on "=>" button (arrow to the right) without typing phone number
Input data
Expected result Phone number textbox is highlighted in red. User is not able to login



GT-9
User should be able to log out

Severity
 Not set
Priority
 Not set
Behavior
Positive
Type
Functional
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
The user has an existing account.
Pre-conditions
User is already logged in

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login to existing account
Input data
Expected result Dashboard page appears
Step 3
Action Click on profile icon on the top right corner
Input data
Expected result Profile pop up appears
Step 4
Action Click "Logout" button
Input data
Expected result User logout successfully and appears on the home page



GT-82
User should not be able to login with incorrect security code

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on “Log in” button
Input data
Expected result Log in page should be displayed
Step 3
Action Type your phone number
Input data
Expected result You should receive code by text message
Step 4
Action Input incorrect security code
Input data
Expected result User should not be able to login with incorrect code



GT-83
User should not be able to login if phone number missing a numbers

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on “Log in” button
Input data
Expected result Log in page should be displayed
Step 3
Action Type incomplete phone number
Input data
Expected result
Step 4
Action Click button "=>"
Input data
Expected result Red texbox appears. User should not be able to login with incomplete phone number.



GT-66 / Dashboard / Financial Goals
User should see "One Time" option as default while creating a financial goal

Severity
 Normal
Priority
 Not set
Behavior
Positive
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://dev.gigturbo.com/dashboard
Pre-conditions
Must be logged in

Steps to reproduce
Step 1
Action Log In and navigate to Gigturbo dashboard
Input data
Expected result Dashboard must be displayed
Step 2
Action Click +Add Goal button on the right side
Input data
Expected result A pop up Add Goal must appear
Step 3
Action Click on "Financial Goal" button
Input data
Expected result
Step 4
Action Verify that "One Time" button is highlighted in black by default
Input data
Expected result



GT-28 / Dashboard / Financial Goals
Changing amount of $ per Month should change accordingly to the position of scrollbar financial goal.

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Go to GigTurbo home page
Input data
Expected
result Home page opens
Step 2
Action Login to existing account
Input data
Expected
result User is redirected to dashboard page
Step 3
Action Click on button 'Add Goal' button on the right side
Input data
Expected
result Add a goal popup appears with financial and learning goals options
Step 4
Action Click on "Financial Goal" button
Input data
Expected
result Popup was updated to "Let’s add a goal!"
Step 5
Action In goal textbox type "Breakfast+random number"
Input data
Expected
result
Step 6
Action Click "Recurring" goal type
Input data
Expected
result
Step 7
Action Type in 500 in Cost textbox
Input data
Expected
result
Step 8
Action Click button "Monthly"
Input data
Expected
result Notice how in "Dedicating hours per week" displaying 20 hours
Step 9
Action Change number to 5000 in texboxt "Cost"
Input data
Expected
result Notice how in "Dedicating hours per week" displaying 65 hours
Step 10
Action Change number to 50000 in texboxt "Cost"
Input data
Expected
result Notice how in "Dedicating hours per week" displaying 648 hours
Step 11
Action Verify that changing amount of $ per Month should change accordingly to the position of scrollbar financi
al goal.
Input data
Expected
result



GT-27 / Dashboard / Financial Goals
Changing amount of $ per WEEK should change accordingly to the position of scrollbar financial goal.

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
Pre-conditions
User has existing GigTurbo account
User is not logged in

Steps to reproduce
Step 1
Action Go to GigTurbo home page
Input data
Expected
result Home page opens
Step 2
Action Login to existing account
Input data
Expected
result User is redirected to dashboard page
Step 3
Action Click on button 'Add Goal' button on the right side
Input data
Expected
result Add a goal popup appears with financial and learning goals options
Step 4
Action Click on "Financial Goal" button
Input data
Expected
result Popup was updated to "Let’s add a goal!"
Step 5
Action In goal textbox type "Lunch+random number"
Input data
Expected
result
Step 6
Action Click "Recurring" goal type
Input data
Expected
result
Step 7
Action Type in 100 in Cost textbox
Input data
Expected
result
Step 8
Action Click button "Weekly"
Input data
Expected
result Notice how in "Dedicating hours per week" displaying 20 hours
Step 9
Action Change number to 1000 in texboxt "Cost"
Input data
Expected
result Notice how in "Dedicating hours per week" displaying 56 hours
Step 10
Action Change number to 10000 in texboxt "Cost"
Input data
Expected
result Notice how in "Dedicating hours per week" displaying 556 hours
Step 11
Action Verify that changing amount of $ per WEEK should change accordingly to the position of scrollbar financi
al goal.
Input data
Expected
result



GT-16 / Dashboard / Financial Goals
User should be able to edit financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://dev.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login to existing account
Input data
Expected result User should land on dashboard
Step 3
Action Click on created 'Financial Goal' in section 'Goals'
Input data
Expected result Financial Goal page should be displayed
Step 4
Action Click on icon 'Edit'
Input data
Expected result “Edit Goal” popup should be displayed
Step 5
Action Change amount of your goal
Input data
Expected result Your amount has changed
Step 6
Action Click on the button 'Next'
Input data
Expected result Financial Goal was change



GT-15 / Dashboard / Financial Goals
User should be able to delete financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://dev.gigturbo.com/
Pre-conditions
User must be logged in

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login to existing account
Input data
Expected result User should land on dashboard page
Step 3
Action Create a new financial goal
Input data
Expected result Goal was created
Step 4
Action Click on the goal that you just created
Input data
Expected result
Step 5
Action Delete the goal
Input data
Expected result
Step 6
Action Verify that goal is not displaying on the dashboard page anymore
Input data
Expected result Goal was removed successfully



GT-62 / Dashboard / Financial Goals
User should be able to add recurring monthly financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on button 'Add Goal' button on the right side
Input data https://dev.gigturbo.com/dashboard
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on Financial Goal button
Input data
Expected result Popup was updated to "Let’s add a goal!"
Step 4
Action In goal textbox type "Dinner+random number"
Input data
Expected result Dinner+random number appear in the textbox
Step 5
Action Click "Recurring" goal type
Input data
Expected result
Step 6
Action Type in 100 in Cost textbox
Input data
Expected result
Step 7
Action Click button "Monthly"
Input data
Expected result
Step 8
Action Set up "Dedicating hours per week" for 20 hours
Input data
Expected result
Step 9
Action Click button "Next"
Input data
Expected result
Step 10
Action Verify goal appeared on the dashboard
Input data
Expected result Name, amount, days, percentage done, repeating
Step 11
Action Click on goal name
Input data
Expected result Verify same data appears on the goal page



GT-14 / Dashboard / Financial Goals
User should be able to add one-time financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on button 'Add Goal' button on the right side
Input data https://dev.gigturbo.com/dashboard
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on "Financial Goal" button
Input data
Expected result Popup was updated to "Let’s add a goal!"
Step 4
Action In goal textbox type "Dinner+random number"
Input data
Expected result Dinner+random number appear in the textbox
Step 5
Action Click "One Time" goal type
Input data
Expected result Goal type One time is selected
Step 6
Action Type in 100 in "Cost" textbox
Input data
Expected result
Step 7
Action Select date 5 days away from now
Input data
Expected result
Step 8
Action Click button "Next"
Input data
Expected result
Step 9
Action Verify goal appeared on the dashboard
Input data
Expected result Name, amount, days, percentage done



GT-88 / Dashboard / Learning Goals
User should be able to explore more learning courses on udacity.com page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click button "Add Goal"
Input data
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on "Learning Goal" button
Input data
Expected result Popup appears
Step 4
Action Click on any category
Input data
Expected result List of courses appears
Step 5
Action Click on link "Explore courses on udacity.com" on the top of the page
Input data
Expected result Notice you was redirected to Udacity page
Step 6
Action Verify that upon clicking link "Explore courses on udacity.com" user is redirecting to Udacity page
Input data https://www.udacity.com/
Expected result



GT-87 / Dashboard / Learning Goals
User is able to search more courses after choosing a course in learning goals

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click button "Add Goal"
Input data
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on "Learning Goal" button
Input data
Expected result Popup appears
Step 4
Action Click on any category
Input data
Expected result List of courses appears
Step 5
Action Click on any course from the list
Input data
Expected result Notice pop up with course information appears
Step 6
Action Click "Explore more options" button
Input data
Expected result Notice the list of the courses appears
Step 7
Action Verify that upon clicking "Explore more options" button the list of the courses appears.
Input data
Expected result




GT-86 / Dashboard / Learning Goals
User should be able to search for category in learning goals

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click button "Add Goal"
Input data
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on "Learning Goal" button
Input data
Expected result Popup appears
Step 4
Action Click on the search box on the top of the screen
Input data
Expected result
Step 5
Action Type in "Tech" in to the search box
Input data
Expected result Notice it found "Tech" category
Step 6
Action Click on any course
Input data
Expected result Notice pop up with course information appears
Step 7
Action Click "Get Started" button
Input data
Expected result
Step 8
Action Select any date from next month
Input data
Expected result
Step 9
Action Click button "Next"
Input data
Expected result Verify that learning goal appears on the dashboard.



GT-85 / Dashboard / Learning Goals
User should be able to create learning goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click button "Add Goal"
Input data
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on "Learning Goal" button
Input data
Expected result Popup appears
Step 4
Action Click on Art & Design category
Input data
Expected result List of courses appears
Step 5
Action Click on any course from the list
Input data
Expected result Notice pop up with course information appears
Step 6
Action Click "Get Started" button
Input data
Expected result Notice "Let's add a goal!" pop up appears
Step 7
Action Select date 10 days from now
Input data
Expected result
Step 8
Action Click button "Next"
Input data
Expected result
Step 9
Action Verify that this goal appears in the dashboard
Input data
Expected result



GT-84 / Dashboard / Learning Goals
User should be able to add recurring weekly financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on button 'Add Goal' button on the right side
Input data
Expected result Add a goal popup appears with financial and learning goals options
Step 3
Action Click on Financial Goal button
Input data
Expected result Popup was updated to "Let’s add a goal!"
Step 4
Action In goal textbox type "Dinner+random number"
Input data
Expected result Dinner+random number appear in the textbox
Step 5
Action Click "Recurring" goal type
Input data
Expected result Goal type One time is selected
Step 6
Action Type in 100 in "Cost" textbox
Input data
Expected result
Step 7
Action Click button "Weekly"
Input data
Expected result
Step 8
Action Set up "Dedicating hours per week" for 10 hours
Input data
Expected result
Step 9
Action Click button "Next"
Input data
Expected result
Step 10
Action Verify goal appeared on the dashboard
Input data
Expected result Name, amount, days, percentage done, repeating
Step 11
Action Click on goal name
Input data
Expected result Verify same data appears on the goal page



GT-91 / Dashboard / Events
User should be able to edit the date of the event

Severity
 Not set
Priority
 Medium
Behavior
Negative
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click on Dashboard page button '+Add Event'
Input data
Expected result Popup appears 'Add Event'
Step 3
Action Click 'I have an Event' button
Input data
Expected result Popup appears 'Add to my schedule'
Step 4
Action Click "Add to my schedule" button
Input data
Expected result Notice your event appears in the dashboard page
Step 5
Action Click on icon "Edit"
Input data
Expected result Notice pop up with event appears
Step 6
Action Change the date of the event
Input data
Expected result
Step 7
Action Click button "Save"
Input data
Expected result
Step 8
Action Verify that the date of the event changed successfully
Input data
Expected result



GT-90 / Dashboard / Events
User should be able to edit the time of the event

Severity
 Not set
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click on Dashboard page button '+Add Event'
Input data
Expected result Popup appears 'Add Event'
Step 3
Action Click 'I have an Event' button
Input data
Expected result Popup appears 'Add to my schedule'
Step 4
Action Click "Add to my schedule" button
Input data
Expected result Notice your event appears in the dashboard page
Step 5
Action Click on icon "Edit"
Input data
Expected result Notice pop up with event appears
Step 6
Action Change the time of the event
Input data
Expected result
Step 7
Action Click button "Save"
Input data
Expected result
Step 8
Action Verify that the time of the event changed successfully
Input data
Expected result



GT-89 / Dashboard / Events
User should be able to delete an event

Severity
 Not set
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Login to existing account
Input data https://dev.gigturbo.com
Expected result Dashboard page displays
Step 2
Action Click on Dashboard page button '+Add Event'
Input data
Expected result Popup appears 'Add Event'
Step 3
Action Click 'I have an Event' button
Input data
Expected result Popup appears 'Add to my schedule'
Step 4
Action Click "Add to my schedule" button
Input data
Expected result Notice your event appears in the dashboard page
Step 5
Action Click on icon "Delete"
Input data
Expected result Pop up "Are you sure you want to remove this event?" appears
Step 6
Action Click "Remove"
Input data
Expected result Verify that event was deleted
Step 7
Action Verify that user is able to delete the event and even no longer displaying on dashboard page
Input data
Expected result



GT-60 / Dashboard / Events
User should be able to add Add event with connected goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://dev.gigturbo.com/

Steps to reproduce
Step 1
Action Login to qa site
Input data https://dev.gigturbo.com/
Expected result Dashboard is displayed
Step 2
Action Click on Dashboard page button '+Add Event'
Input data
Expected result Popup appears 'Add Event'
Step 3
Action Click 'I have an Event' button
Input data
Expected result Popup appears 'Add to my schedule'
Step 4
Action Click button "Add"
Input data
Expected result Popup appears with events appears
Step 5
Action Type in search box "shop"
Input data
Expected result Notice events appears
Step 6
Action Choose any category and click on it
Input data
Expected result This category added on the page 'I have an Event'
Step 7
Action Select date 5 days away from now from 3pm to 11pm
Input data
Expected result
Step 8
Action Click 'More Options'
Input data
Expected result
Step 9
Action Connect it to home goal
Input data
Expected result
Step 10
Action Click "Add to my schedule"
Input data
Expected result
Step 11
Action Verify even appears on the page
Input data
Expected result Name, "from" date and time and "to" date and time



GT-59 / Dashboard / Events
User should be able to add Add event without connected goal

Severity
 Not set
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://dev.gigturbo.com/

Steps to reproduce
Step 1
Action Login to qa site
Input data https://dev.gigturbo.com/
Expected result Dashboard is displayed
Step 2
Action Click on Dashboard page button '+Add Event'
Input data
Expected result Popup appears 'Add Event'
Step 3
Action Click 'I have an Event' button
Input data
Expected result Popup appears 'Add to my schedule'
Step 4
Action Click on the button "Add"
Input data
Expected result
Step 5
Action Type in BD Party + random number
Input data
Expected result
Step 6
Action Select date 5 days away from now from 3pm to 11pm
Input data
Expected result
Step 7
Action Click "Add to my schedule"
Input data
Expected result
Step 8
Action Verify event appears on the page
Input data
Expected result Name, "from" date and time and "to" date and time



GT-106 / Dashboard / Events
Should get redirected to the service site, up click on "Go to app"

Severity
 Major
Priority
 Not set
Behavior
Negative
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
Pre-conditions
User must be logged in to the website

Steps to reproduce
Step 1
Action Login to the website
Input data
Expected result
Step 2
Action Click Go to app in my events section of the dashboard
Input data
Expected result User was redirected to service site



GT-95 / Dashboard / Dashboard Icons
User should be able to sync calendar from Dashboard page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Sync your calendar" link
Input data
Expected result User should be redirected to calendar page
Step 4
Action Click on Google icon to sync your calendar
Input data
Expected result
Step 5
Action Verify that calendar synced successfully
Input data
Expected result




GT-94 / Dashboard / Dashboard Icons
User should be able to delete the account on the top right corner of the Dashboard page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action On Dashboard page on the top right corner click "Profile" icon
Input data
Expected result Notice Profile pop up displays
Step 4
Action Click button "Delete Account"
Input data
Expected result Confirmation pop up should appear
Step 5
Action Verify that user deleted the profile successfully and was redirected to Homepage
Input data https://dev.gigturbo.com/
Expected result



GT-93 / Dashboard / Dashboard Icons
User should be able to see Profile page by clicking on the "Profile" button on the top right corner on Dashboard page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected
result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected
result User is landing on dashboard page
Step 3
Action On Dashboard page on the top right corner click "Profile" icon
Input data
Expected
result Profile pop up appears
Step 4
Action Click on button "Profile"
Input data
Expected
result Notice that user was redirected to General page
Step 5
Action Verify that user was redirected to "General" page upon clicking the profile button on the top right corner of
Dashboard page
Input data
Expected
result



GT-92 / Dashboard / Dashboard Icons
User should be able to see notifications on the top right corner on Dashboard page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action On Dashboard page on the top right corner click on "alarm" button
Input data
Expected result Notice "Notification" pop up appears
Step 4
Action Verify that message "No new notifications" appears on theNotifications pop up
Input data
Expected result



GT-17 / Dashboard / Dashboard Icons
User should be able to add location on the top right corner

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://dev.gigturbo.com/
Pre-conditions
User Must Be Logged In

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action On Dashboard page on the top right corner click button "Add location"
Input data
Expected result General page appears
Step 4
Action Input you location in "Location" textbox
Input data
Expected result
Step 5
Action Click button "Save Changes"
Input data
Expected result
Step 6
Action Navigate to dashboard page
Input data https://dev.gigturbo.com/dashboard
Expected result Verify that your location was saved and displaying on the top right corner on Dashboard page



GT-61
Total amount of $ should update after adding new financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Goals" button on the left navigation menu bar
Input data
Expected result User is redirected to Goals page
Step 4
Action Notice how much money is displaying on your Total " Financial Goal" icon
Input data
Expected result
Step 5
Action Add new financial goal with $100 in "Cost" text box
Input data
Expected result
Step 6
Action Verify that total amount of money in financial goals icon increase by $100.
Input data
Expected result



GT-96
Total amount of $ should update after removing a financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Goals" button on the left navigation menu bar
Input data
Expected result User is redirected to Goals page
Step 4
Action Notice how much money is displaying on your Total " Financial Goal" icon
Input data
Expected result
Step 5
Action Add new financial goal with $100 in "Cost" text box
Input data
Expected result Notice that total amount of money in financial goals icon increase by $100.
Step 6
Action Delete this goal
Input data
Expected result
Step 7
Action Verify that total amount of money in financial goals icon decrease by $100.
Input data
Expected result



GT-97
Total amount of hours should update after adding new learning goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Goals" button on the left navigation menu bar
Input data
Expected result User is redirected to Goals page
Step 4
Action Notice how many hours is displaying on your Total " Learning Goal" icon
Input data
Expected result
Step 5
Action Add new learning goal with 100 hours in it
Input data
Expected result
Step 6
Action Verify that total amount of money in learning goals icon increase by 100 hours.
Input data
Expected result



GT-98
Total amount of hours should update after removing a learning goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Goals" button on the left navigation menu bar
Input data
Expected result User is redirected to Goals page
Step 4
Action Notice how many hours is displaying on your Total " Learning Goal" icon
Input data
Expected result
Step 5
Action Remove learning goal that contains 100 hours
Input data
Expected result
Step 6
Action Verify that total amount of money in learning goals icon decrease by 100 hours.
Input data
Expected result



GT-99
Total amount of goals should update after adding a new financial goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Goals" button on the left navigation menu bar
Input data
Expected result User is redirected to Goals page
Step 4
Action Notice how many hours is displaying on your Total " In progress " icon
Input data
Expected result
Step 5
Action Add new financial goal
Input data
Expected result
Step 6
Action Verify that total amount of goals in "In progress" icon increase by 1 goal.
Input data
Expected result



GT-100
Total amount of goals should update after adding a new learning goal

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is Displayed
Step 2
Action Login to existing account
Input data
Expected result User is landing on dashboard page
Step 3
Action Click on "Goals" button on the left navigation menu bar
Input data
Expected result User is redirected to Goals page
Step 4
Action Notice how many hours is displaying on your Total " In progress " icon
Input data
Expected result
Step 5
Action Add new learning goal
Input data
Expected result
Step 6
Action Verify that total amount of goals in "In progress" icon increase by 1 goal.
Input data
Expected result



GT-107
User should be able to choose a first Goal at In progress section

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on Goals in the main menu
Input data
Expected result Goals page is displayed
Step 3
Action Click on first goal at Goals In progress list
Input data
Expected result Selected in progress goal description is displayed



GT-108
User should be able to choose a first Goal in Completed section

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on Goals in the main menu
Input data
Expected result Goals page is displayed
Step 3
Action Click on Completed section in Goals page
Input data
Expected result List of Completed goals should be displayed
Step 4
Action Click on first goal at Goals Completed list
Input data
Expected result Selected Completed goal description is displayed



GT-109
User should be able to see In progress goals list after switching from Completed goals list

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on Goals in the main menu
Input data
Expected result Goals page is displayed
Step 3
Action Click on Completed section in Goals page
Input data
Expected result List of Completed goals should be displayed
Step 4
Action Click on In progress section in Goals page
Input data
Expected result List of In progress goals should be displayed



GT-110
User should be able to navigate to Total Financial Goal page

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on Goals in the main menu
Input data
Expected result Goals page is displayed
Step 3
Action Click Financial Goal button
Input data
Expected result Financial Goal page should be displayed



GT-111
User should be able to navigate to Total Learning Goal page

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
qa site = https://dev.gigturbo.com

Steps to reproduce
Step 1
Action Login to qa site with your phone number
Input data
Expected result Dashboard is displayed
Step 2
Action Click on Goals in the main menu
Input data
Expected result Goals page is displayed
Step 3
Action Click Learning Goal button
Input data
Expected result Learning Goal page is displayed



GT-58 / Settings / General
Should be able to update timezone in Calendar

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Settings' in menu items
Input data
Expected result Settings dropdown is displayed
Step 4
Action Click on primary timezone
Input data
Expected result dropdown with timezone appears
Step 5
Action Select different timezone
Input data
Expected result dropdown closes and new timezone shows as chosen
Step 6
Action Refresh the page and verify that new time zone saved successfully
Input data
Expected result



GT-19 / Settings / General
User should be able to update preferred work time

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://dev.gigturbo.com/
Pre-conditions
User should be Logged in

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Settings' in menu items
Input data
Expected result Settings menu items is opening
Step 4
Action Click on section 'Calendar' in menu Settings
Input data
Expected result Calendar page is displayed
Step 5
Action Change your "preferred work time” in one of the dates
Input data
Expected result "preferred work time” is set
Step 6
Action Click on button 'Save Changes'
Input data
Expected result User should be able to update preferred work time



GT-102 / Settings / General
User should be able to remove days in preferred work time section

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Settings' in menu items
Input data
Expected result Settings menu items is opening
Step 4
Action Click on section 'Calendar' in menu Settings
Input data
Expected result Calendar page is displayed
Step 5
Action Remove selected day by unchecking the box
Input data
Expected result Check box uncheck
Step 6
Action Click on button 'Save Changes'
Input data
Expected result Work day was removed successfully



GT-101 / Settings / General
User should be able to add days in preferred work time section

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Settings' in menu items
Input data
Expected result Settings menu items is opening
Step 4
Action Click on section 'Calendar' in menu Settings
Input data
Expected result Calendar page is displayed
Step 5
Action Add a day by check marking a box
Input data
Expected result Yellow "check mark" appears in the box
Step 6
Action Click on button 'Save Changes'
Input data
Expected result New work day was added successfully



GT-20 / Settings / General
User should be able to "sync your calendar" with Google account

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Functional
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://dev.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on 'Settings' in menu Items
Input data
Expected result Settings menu items is opens
Step 4
Action Click on section 'Calendar' in menu Settings
Input data
Expected result Calendar page is displayed
Step 5
Action Click on icon Google in section 'Sync your calendar'
Input data
Expected result Popup Google account
Step 6
Action Choose your Google account
Input data
Expected result Google account successfully sync with calendar



GT-31
Should be able to see calendar with current day showing in yellow color upon navigation to calendar page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Calendar' in menu items
Input data
Expected result Calendar page opens
Step 4
Action Verify that current day is showing in yellow color
Input data
Expected result



GT-32
Should be able to switch between Day, Week and Month, Agenda view and see changes in table accordingly

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Calendar' in menu items
Input data
Expected result Calendar page is displayed
Step 4
Action Click on the button 'Month' and change in for "Week"
Input data
Expected result See changes in table accordingly
Step 5
Action Click same button 'Week' and change it for "Day"
Input data
Expected result See changes in table accordingly
Step 6
Action Click same button "Day" and change it to "Agenda"
Input data
Expected result See changes in table accordingly
Step 7
Action Verify that all table views are working as expected
Input data
Expected result



GT-33
Should be able to switch between Previous, Next and Today DAY views by clicking Previous, Next and Today buttons

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Calendar' in menu items
Input data
Expected result Calendar page is displayed
Step 4
Action Click on the button 'Day'
Input data
Expected result The table changes on Day
Step 5
Action Click on switch left
Input data
Expected result See Previous day
Step 6
Action Click on button 'Today'
Input data
Expected result See Today day
Step 7
Action Click on switch right
Input data
Expected result See Next day



GT-34
Should be able to switch between Previous, Next and Today WEEK views by clicking Previous, Next and Today buttons

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Calendar' in menu items
Input data
Expected result Calendar page is displayed
Step 4
Action Click on the button 'Week'
Input data
Expected result The table changes on Week
Step 5
Action Click on switch left
Input data
Expected result See Previous week
Step 6
Action Click on button 'Today'
Input data
Expected result See Today week
Step 7
Action Click on switch right
Input data
Expected result See Next week



GT-35
Should be able to switch between Previous, Next and Today Month views by clicking Previous, Next and Today buttons

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Calendar' in menu items
Input data
Expected result Calendar page is displayed
Step 4
Action Click on the button 'Month'
Input data
Expected result The table changes on Month
Step 5
Action Click on switch left
Input data
Expected result See Previous month
Step 6
Action Click on button 'Today'
Input data
Expected result See Today month
Step 7
Action Click on switch right
Input data
Expected result See Next month



GT-65
User should be able to add an event on Calendar page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on section 'Calendar' in menu items
Input data
Expected result Calendar page is displayed
Step 4
Action Click on "Add event" button
Input data
Expected result event pop up appears
Step 5
Action Filled down the fields
Input data
Expected result
Step 6
Action Click "Add to my schedule" button
Input data
Expected result
Step 7
Action Verify that event was add to your calendar
Input data
Expected result



GT-114
Should have primary time Zone set to Pacific

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://dev.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to Homepage.
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed.
Step 2
Action Login with existing account.
Input data
Expected result Dashboard page is displayed.
Step 3
Action Click on "Settings" button on the menu.
Input data
Expected result Settings options appears.
Step 4
Action Click on the "Calendar" button.
Input data
Expected result Calendar page open.
Step 5
Action Select the "Time zone" section and set to Pacific time.
Input data
Expected result
Step 6
Action Click "Save Changes" button
Input data
Expected result Pacific time zone set successfully.



GT-38
User should be able to discover gigs by typing company name in search box

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Functional
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to the Home page
Input data https://beta.gigturbo.com/
Expected result The home page is displayed
Step 2
Action Click on the Discover Gigs
Input data
Expected result Discover Gigs is displayed
Step 3
Action Choose and click any popular job
Input data For example: Driving
Expected result The button Driving will be highlighted
Step 4
Action Click on the button Next
Input data
Expected result 'The most popular platforms and jobs' page is displayed
Step 5
Action Type Uber in the Searchbox
Input data
Expected result Uber icon is displayed



GT-41
User should be able to filter categories by platforms

Severity
 Major
Priority
 High
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to home page
Input data https://beta.gigturbo.com
Expected result home page is displayed
Step 2
Action Click on section DISCOVER GIGS
Input data
Expected result Page 'The most popular platforms and jobs' is displayed
Step 3
Action Click on any icon of platforms
Input data
Expected result Icon platforms will be highlighted and sort at the bottom on the NEXT button



GT-40
User should be redirected on Fitness Trainer company website by clicking on "Join now" [IN DEVELOPMENT]

Severity
 Not set
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to home page
Input data https://beta.gigturbo.com
Expected result Home page is displayed
Step 2
Action Click on section DISCOVER GIGS
Input data
Expected result Page 'The most popular platforms and jobs' is displayed
Step 3
Action Type “Fitness ” in the searchbox
Input data
Expected result Company Fitness trainer is displayed
Step 4
Action Click on ‘Company Fitness trainer”
Input data
Expected result “Fitness trainer” in the searchbox is displayed
Step 5
Action Scroll down until section SERVICE
Input data
Expected result Button “Fitness Trainer” is displayed
Step 6
Action Click on ‘Join now” on the button Fitness trainer
Input data
Expected result User redirected on FitnessTrainer company website



GT-49
User should receive "No items found" message when typing incorrect data in search box (e.g. "123") [IN DEVELOPMENT]

Severity
 Not set
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
Pre-conditions
none

Steps to reproduce
Step 1
Action navigate to Homepage
Input data https://beta.gigturbo.com
Expected result Homepage is displayed
Step 2
Action Click on the section “Discover Gigs” on top of the page
Input data
Expected result Discover page is displayed
Step 3
Action Click on the Search box and type incorrect data
Input data 123
Expected result Get “no items found” message below Search box



GT-57
User should be able to discover gigs by picking categories

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Functional
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to the Home page
Input data https://beta.gigturbo.com/
Expected result The home page is displayed
Step 2
Action Click on the Discover Gigs
Input data
Expected result Discover Gigs is displayed
Step 3
Action Choose and click any popular job
Input data For example: Driving
Expected result The button Driving will be highlighted
Step 4
Action Click on the button Next
Input data
Expected result 'The most popular platforms and jobs' page is displayed
Step 5
Action Type Uber in the Searchbox
Input data
Expected result Uber icon is displayed
Step 6
Action Click on the icon Uber
Input data
Expected result Popup page is displayed
Step 7
Action Click on the button 'Get started'
Input data
Expected result 'Let’s get you started!' page is displayed



GT-45
User should be able to find Lyft in Popular promotions by typing "Lyft" in a search box [IN DEVELOPMENT]

Severity
 Minor
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to home page
Input data https://beta.gigturbo.com
Expected result Home page is displayed
Step 2
Action Click on section PROMOTIONS
Input data
Expected result Page “All the latest promotions” is displayed
Step 3
Action Find searchbox “Popular promotions”
Input data
Expected result searchbox “Popular promotions” is displayed
Step 4
Action Type in the searchbox ‘Lyft”
Input data
Expected result Promotion “Lyft” is displayed



GT-46
User should be able to be redirected to Lyft page by clicking on "Redeem" button [IN DEVELOPMENT]

Severity
 Normal
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on Promotions section on the top the page
Input data
Expected result Promotions page is displayed
Step 3
Action Browse through popular promotions
Input data
Expected result Find Lyft Promotion
Step 4
Action Click on redeem
Input data
Expected result User redirected to Lyft page



GT-47
User should be able to Navigate to Community Guidelines section

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to home page
Input data https://beta.gigturbo.com/
Expected result Home page is displayed
Step 2
Action Click on the link FAQ on top of the page
Input data
Expected result FAQ page is open
Step 3
Action Choose Community Guidelines section
Input data
Expected result Community Guidelines section is highlighted
Step 4
Action Click on Community Guidelines section
Input data
Expected result Community Guidelines section is displayed



GT-48
User should be able to expand "Who Gigturbo is for?" in Gigturbo basic

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
Pre-conditions
none

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on the link “FAQ” on the top of the page
Input data
Expected result FAQ page is open
Step 3
Action If not chosen “Gigturbo basic” click on it
Input data
Expected result Gigturbo basics is highlighted
Step 4
Action Click on the link “Who Gigturbo is for?”
Input data
Expected result List has to expand



GT-53
User should take to FAQ page upon click on FAQ menu link in the header menu

Severity
 Normal
Priority
 Medium
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on FAQ menu link in the header menu
Input data
Expected result FAQ in page should be displayed



GT-67
User should be able to upload their photo

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on "Settings" button on the menu
Input data
Expected result Settings options appears
Step 4
Action Click on "General" button
Input data
Expected result General page opens
Step 5
Action Click on photo icon
Input data
Expected result
Step 6
Action Choose the photo from your computer
Input data
Expected result
Step 7
Action Verify that photo was added successfully
Input data
Expected result


GT-70
User should be able to update Locations

Severity
 Major
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on "Settings" button on the menu
Input data
Expected result Settings options appears
Step 4
Action Click on "General" button
Input data
Expected result General page opens
Step 5
Action Update the Location text box
Input data
Expected result
Step 6
Action Click button "Save Changes"
Input data
Expected result
Step 7
Action Verify that location was updated successfully
Input data
Expected result



GT-71
User should be able delete photo
Severity
 Major
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on "Settings" button on the menu
Input data
Expected result Settings options appears
Step 4
Action Click on "General" button
Input data
Expected result General page opens
Step 5
Action Click on photo icon
Input data
Expected result
Step 6
Action Choose the photo from your computer
Input data
Expected result
Step 7
Action Delete the photo by clicking "X" on the top right corner of the photo
Input data
Expected result
Step 8
Action Verify that the photo was deleted successfully
Input data
Expected result




GT-103
User should be able to update first and last name

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Login with existing account
Input data
Expected result Dashboard page is displayed
Step 3
Action Click on "Settings" button on the menu
Input data
Expected result Settings options appears
Step 4
Action Click on "General" button
Input data
Expected result General page opens
Step 5
Action Update your First and Last name text boxes
Input data
Expected result
Step 6
Action Click button "Save Changes"
Input data
Expected result
Step 7
Action Verify that changes was saved successfully
Input data
Expected result



GT-24
User should be able to register with categories of interest

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result Page 'Let’s get you started!' is displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Page 'I’m here to help your reach your goals.' is displayed
Step 5
Action Click on button 'EARN'
Input data
Expected result Page 'Tell me more about how you earn today:' is displayed
Step 6
Action Click on the button NEXT
Input data
Expected result Page 'Tell me more about how you earn today:' is displayed
Step 7
Action Click on the section 'I do task-oriented work on platforms like'
Input data
Expected result This section will be highlighted
Step 8
Action Click on the button NEXT
Input data
Expected result Page 'I’m here to help you make the most of your time. is displayed
Step 9
Action Click on the button NEXT
Input data
Expected result Page 'Tell me more about yourself' is displayed
Step 10
Action Fill in all sections about yourself
Input data
Expected result
Step 11
Action Click on the button NEXT
Input data
Expected result Page 'What are you interested in?' is displayed
Step 12
Action Choose Painting category
Input data
Expected result page 'Based on your input, here are some options for you' is displayed
Step 13
Action Type 'spoon' in text box
Input data
Expected result Verify 'spoon' platform



GT-55
User should be able to register with few apps selected in "What
are you interested in?" page

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result Page 'Let’s get you started!' is displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Page 'I’m here to help your reach your goals.' is displayed
Step 5
Action Click on button 'EARN'
Input data
Expected result Page 'Tell me more about how you earn today:' is displayed
Step 6
Action Click on the button NEXT
Input data
Expected result Page 'Tell me more about how you earn today:' is displayed
Step 7
Action Click on the section 'I do task-oriented work on platforms like'
Input data
Expected result This section will be highlighted
Step 8
Action Click on the button NEXT
Input data
Expected result Page 'I’m here to help you make the most of your time. is displayed
Step 9
Action Click on the button NEXT
Input data
Expected result Page 'Tell me more about yourself' is displayed
Step 10
Action Fill in all sections about yourself
Input data
Expected result
Step 11
Action Click on the button NEXT
Input data
Expected result Page 'What are you interested in?' is displayed
Step 12
Action Select few apps
Input data
Expected result



GT-56
User should be able to register with categories of interest

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result Page 'Let’s get you started!' is displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Page 'I’m here to help your reach your goals.' is displayed
Step 5
Action Click on button 'EARN'
Input data
Expected result Page 'Tell me more about how you earn today:' is displayed
Step 6
Action Click on the button NEXT
Input data
Expected result Page 'Tell me more about how you earn today:' is displayed
Step 7
Action Click on the section 'I do task-oriented work on platforms like'
Input data
Expected result This section will be highlighted
Step 8
Action Click on the button NEXT
Input data
Expected result Page 'I’m here to help you make the most of your time. is displayed
Step 9
Action Click on the button NEXT
Input data
Expected result Page 'Tell me more about yourself' is displayed
Step 10
Action Fill in all sections about yourself
Input data
Expected result
Step 11
Action Click on the button NEXT
Input data
Expected result Page 'What are you interested in?' is displayed
Step 12
Action Choose any categories of interest
Input data
Expected result



GT-72
User should be able learn about ''The Complete Guide To Becoming A Babysitter''

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result Page 'Let’s get you started!' is displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Page 'I’m here to help your reach your goals.' is displayed
Step 5
Action Click on button 'Learn'
Input data
Expected result Page 'Tell me more about yourself' is displayed
Step 6
Action Fill in all sections about yourself
Input data
Expected result
Step 7
Action Click on the button NEXT
Input data
Expected result Page 'Tell me what you want to be better at:' is displayed
Step 8
Action click on 'Working with Children' category
Input data
Expected result Page 'Page 'Working with Children' is displayed
Step 9
Action Verify 'The Complete Guide To Becoming A Babysitter' is there and clickable
Input data
Expected result



GT-73
User should be able search 'spoon' platform

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result
Step 3
Action Type your phone number
Input data
Expected result
Step 4
Action Input received code
Input data
Expected result
Step 5
Action Click on button 'EARN'
Input data
Expected result
Step 6
Action Click on the button NEXT
Input data
Expected result
Step 7
Action Click on the section 'I do task-oriented work on platforms like'
Input data
Expected result
Step 8
Action Click on the button NEXT
Input data
Expected result
Step 9
Action Click on the button NEXT
Input data
Expected result
Step 10
Action Fill in all sections about yourself
Input data
Expected result
Step 11
Action Click on the button NEXT
Input data
Expected result
Step 12
Action Choose Painting category
Input data
Expected result This section will be highlighted
Step 13
Action Click on the button NEXT
Input data
Expected result page 'Let’s explore options based on your interests' displayed
Step 14
Action Click on the button NEXT
Input data
Expected result page 'Based on your input, here are some options for you' is displayed
Step 15
Action Type 'spoon' text box
Input data
Expected result



GT-74
User should be able Explore courses on udacity.com

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result Page 'Let’s get you started!' is displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Page 'I’m here to help your reach your goals.' is displayed
Step 5
Action Click on button 'Learn'
Input data
Expected result Page 'Tell me more about yourself' is displayed
Step 6
Action Fill in all sections about yourself
Input data
Expected result
Step 7
Action Click on the button NEXT
Input data
Expected result Page 'Tell me what you want to be better at:' is displayed
Step 8
Action click on 'Cooking' category
Input data
Expected result Page 'Cooking' is displayed
Step 9
Action click on Explore courses on udacity.com link
Input data
Expected result Page udacity.com is displayed



GT-69
The user should be able to come back on the Homepage

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on GET STARTED
Input data
Expected result Page 'Let’s get you started!' is displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Page 'I’m here to help your reach your goals.' is displayed
Step 5
Action Click on icon Giggurbo on the left top corner
Input data
Expected result User should be able come back on the Home page



GT-113
User should be able to add / remove a social media account on general settings section

Severity
 Normal
Priority
 Not set
Behavior
Not set
Type
Functional
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
Pre-conditions
User must be Logged in

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://dev.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on “Login” button
Input data
Expected result Login page should be displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sm
Step 4
Action Input received code
Input data
Expected result Dashboard page is displayed
Step 5
Action Click on section 'Settings' in menu items
Input data
Expected result Settings menu items is opening
Step 6
Action Click on section 'General'
Input data
Expected result Page General is displayed
Step 7
Action scroll down and Click on "+Add more" button on Social Media Section
Input data
Expected result Blank space is displayed
Step 8
Action Type in your social media account of choice
Input data
Expected result Social media account is recognized by Girturbo page
Step 9
Action Click on "Add" Button
Input data
Expected result Social media account is added to your profile
Step 10
Action Click on "Delete" Button
Input data
Expected result Social Media account is removed from your profile



GT-54
User should be able to add and save basic information (name, email, phone, city)

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual
https://beta.gigturbo.com/
Pre-conditions
User should be Logged in

Steps to reproduce
Step 1
Action Navigate to Homepage
Input data https://beta.gigturbo.com/
Expected result Homepage is displayed
Step 2
Action Click on “Login” button
Input data
Expected result Login page should be displayed
Step 3
Action Type your phone number
Input data
Expected result Input the 6-digit code which you received by sms
Step 4
Action Input received code
Input data
Expected result Dashboard page is displayed
Step 5
Action Click on section 'Settings' in menu items
Input data
Expected result Settings menu items is opening
Step 6
Action Click on section 'General'
Input data
Expected result Page General is displayed
Step 7
Action Fill in the following placeholders: name, email, phone, city
Input data
Expected result The button 'Save Changes' lights up
Step 8
Action Click on the button 'Save Changes'
Input data
Expected result Your information has been saved
Step 9
Action Click on Calendar page
Input data
Expected result Calendar page is displayed
Step 10
Action Then return again to General page (click on General page)
Input data
Expected result Check your completed information (name, email, phone, city)



GT-64
Should have Animal Care and Animal training under interests (+14154009912)

Severity
 Not set
Priority
 Not set
Behavior
Not set
Type
Other
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Not automated
Status
Actual

Steps to reproduce
Step 1
Action Press button 'Get started' on the right top
Input data
Expected result 'Let's get you started' page opened
Step 2
Action Type in the phone number '+14154009912'
Input data
Expected result
Step 3
Action Press yellow arrow button
Input data
Expected result Page where you need to type code opened
Step 4
Action Enter '000000' to the empty fields
Input data
Expected result Redirected you to the Initial page
Step 5
Action Press 'Earn' button
Input data
Expected result Earn page opened
Step 6
Action Select task and press 'Next' button
Input data
Expected result Gigs page opened
Step 7
Action Press 'Next' button
Input data
Expected result Profile page opened
Step 8
Action Press 'Skip for now' button
Input data
Expected result Interests page opened
Step 9
Action 'Animal Care' and 'Animal Training' are under interests
Input data
Expected result


GT-75
User should be able to navigate to "Discover Gigs" section fromthe Homepage

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://beta.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to homepage
Input data https://beta.gigturbo.com/
Expected result User is taken to the homepage
Step 2
Action Click "Discover Gigs" label at the top menu
Input data
Expected result User is redirected to Discover Gigs section



GT-76
User should be able to navigate to "Community" section from the Homepage

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://beta.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to homepage
Input data
https://beta.gigturbo.com/
Expected result
User is taken to the homepage
Step 2
Action Click "Community" label at the top menu
Input data
Expected result
User is redirected to Community section



GT-77
User should be able to navigate to "Promotions" section from the Homepage

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://beta.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to homepage
Input data https://beta.gigturbo.com/
Expected result User is taken to the homepage
Step 2
Action Click "Promotions" label at the top menu
Input data
Expected result User is redirected to Promotions section




GT-78
User should be able to navigate to "FAQ" section from the Homepage

Severity
 Normal
Priority
 Medium
Behavior
Positive
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://beta.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to homepage
Input data https://beta.gigturbo.com/
Expected result User is taken to the homepage
Step 2
Action Click "FAQ" label at the top menu
Input data
Expected result User is redirected to FAQ section



GT-79
User should be able to navigate to "Login" section from the Homepage

Severity
 Critical
Priority
 High
Behavior
Positive
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://beta.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to homepage
Input data https://beta.gigturbo.com/
Expected result User is taken to the homepage
Step 2
Action Click "Login" label at the top menu
Input data
Expected result User is redirected to Login section




GT-80
User should be able to navigate to "Get Started" section from the Homepage

Severity
 Critical
Priority
 High
Behavior
Positive
Type
Regression
Layer
Not set
Is Flaky
No
Milestone
-
Automation
Automated
Status
Actual
https://beta.gigturbo.com/

Steps to reproduce
Step 1
Action Navigate to homepage
Input data https://beta.gigturbo.com/
Expected result User is taken to the homepage
Step 2
Action Click "Get Started" label at the top menu
Input data
Expected result User is redirected to Sign up section_
![image](https://user-images.githubusercontent.com/106398846/205479868-27c88886-0cbe-442f-b17d-59bcc1db9f9e.png)
