Learning Practice: Test Planning

Step 1: Define the Test Context

Test Objectives

Verify that users can successfully create a booking by selecting a rental, entering valid check-in and checkout dates, and providing the correct number of guests.

Verify that users can view their bookings and that application controls correctly increase, decrease, and reset values.

Test Scope

Section

Description

In Scope

Rental selection, booking form, date validation, guest count, booking creation, and booking list.

Out of Scope

Payment processing, email notifications, and third-party rental services.

Test Basis

Application requirements, user stories, source code, and user interface designs.

Assumption

The application and test environment will be available before testing begins.

Constraint

Testing must be completed within one week.

Step 2: Identify Roles and Responsibilities

Role

Responsibilities

When Involved

Communication

Test Manager

Creates the test plan, assigns tasks, and monitors testing progress.

Planning and throughout testing.

Communicates with the entire team.

Software Tester

Designs test cases, performs testing, and reports defects.

During test planning and execution.

Reports defects to developers.

Developer

Fixes identified bugs and supports automated testing.

During development and defect resolution.

Communicates with testers and the test manager.

Product Owner

Reviews requirements and confirms the application meets user expectations.

Planning and final review.

Communicates with the test manager and development team.

Step 3: Define the Test Approach

The application will be tested using a combination of manual and automated testing to identify problems before release.

Testing Strategy

Test Levels: Component testing, integration testing, and system testing.

Test Types: Functional testing, usability testing, and regression testing.

Test Techniques: Boundary value analysis and equivalence partitioning.

Manual Testing: Test the booking process, rental selection, and user interface.

Automated Testing: Use Jest to test application functions and booking validation.

Test Activities and Deliverables

Test Area

Test Level or Type

Technique

Manual or Automated

Deliverable

Booking form

Component testing

Boundary value analysis

Automated

Jest test file

Guest count

Functional testing

Equivalence partitioning

Automated

Test results

Rental selection

Integration testing

Decision table testing

Manual

Test cases

Booking creation

System testing

End-to-end testing

Manual

Test completion report

Booking list

Regression testing

Re-testing

Automated

Test results

Test Deliverables

Test plan

Test cases

Automated test files

Test execution results

Defect reports

Final test completion report

Step 4: Identify Test Requirements

The following resources are needed to complete testing.

Requirement

Description

Test Environment

Local development environment with the booking application installed.

Browsers

Google Chrome, Safari, and Firefox.

Devices

Desktop and mobile devices.

Testing Tools

VS Code, Jest, JavaScript/TypeScript, and GitHub.

Test Data

Valid and invalid dates, rental selections, and guest counts.

Access

Access to the application source code and GitHub repository.

Accounts

Test user accounts for creating and viewing bookings.

People

Testers, developers, and a product owner.

Training

Team members should understand the application requirements and testing tools.

Step 5: Create a Risk Register

Risk

Type

Likelihood

Impact

Mitigation

Users can create bookings with invalid dates.

Product Risk

Medium

High

Test date validation using valid and invalid date combinations.

The test environment becomes unavailable.

Project Risk

Low

High

Confirm the environment is working before testing begins.

Guest counts can exceed the allowed limit.

Product Risk

Medium

High

Test minimum, maximum, and invalid guest values.

Testing takes longer than expected.

Project Risk

Medium

Medium

Prioritize high-risk features and follow the testing schedule.

Step 6: Define Entry Criteria

The following conditions must be met before testing begins.

The application must be installed and accessible in the test environment.

All planned test cases must be written and reviewed.

Required testing tools, including Jest, must be installed and working.

Test data must be prepared and available.

Developers must complete initial component testing before system testing begins.

Step 7: Define Exit Criteria

Testing will be considered complete when the following conditions are met.

At least 95% of all planned test cases have been executed.

All critical and high-priority test cases pass.

No critical or high-severity defects remain unresolved.

All major booking features have been tested successfully.

Regression testing has been completed with no new critical defects.

A final test completion report has been submitted.

Step 8: Create a Test Schedule

The testing process will take place over five working days.

Activity

Responsible Role

Time

Dependency

Review application requirements

Test Manager and Product Owner

Day 1

Requirements must be available.

Create test cases

Software Tester

Day 1

Requirements have been reviewed.

Set up test environment and test data

Developer

Day 2

Application source code is available.

Perform component and integration testing

Tester and Developer

Day 3

Test environment is ready.

Perform system and regression testing

Software Tester

Day 4

Earlier testing is completed.

Review results and create final report

Test Manager

Day 5

All planned testing activities are completed.

Step 9: Define the Communication Plan

The team will communicate regularly to share testing progress, report defects, and discuss issues.

Information

Audience

Method

Frequency

Test progress

Project team

Daily stand-up

Daily

Defect reports

Developers

GitHub Issues

Whenever a defect is found

Test results

Test Manager

Test report

After each testing phase

Testing risks

Project team

Team meetings

When a risk is identified

Final test completion report

Product Owner and project team

GitHub and project report

At the end of testing

