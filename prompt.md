Prompt 1 – Understand the Assignment

Review the assignment and explain the requirements in simple terms. Break down each task and highlight any assumptions, missing requirements, or areas that need clarification. Don't solve the assignment yet.

Follow-up

List any questions you would normally ask the Product Owner before starting testing.

Prompt 2 – Requirement Analysis

Create a requirement analysis document in Markdown. Include:

Functional Requirements
Non-Functional Requirements
Assumptions
Dependencies
Risks
Open Questions

Follow-up

Review the document and add anything you think is missing from a QA perspective.

Prompt 3 – Risk Analysis

Prioritize the features based on business risk and testing priority. Explain why each item has been ranked that way.

Follow-up

Review the priorities again from an end-user perspective and update them if needed.

Prompt 4 – Test Scenarios

Generate test scenarios covering:

Functional
UI
API
Validation
Keyboard
Accessibility
Security
Boundary
Negative
Performance
Usability

Follow-up

Remove duplicate scenarios.

Follow-up

Select the best 10 scenarios for this assignment.

Prompt 5 – Defect Identification

Compare the sample API response with FR-05 and identify any mismatches. Mention expected value, actual value, and the reason.

Follow-up

Review again and verify timestamp, locale, datatype, and response contract.

Prompt 6 – Test Cases

Create detailed manual test cases for the selected scenarios.

Include:

Test Case ID
Title
Preconditions
Test Steps
Expected Result
Test Data

Follow-up

Review and improve the test cases.

Follow-up

Add API validation wherever applicable.

Prompt 7 – Automation Design

Suggest a Playwright project structure using JavaScript and Page Object Model.

Follow-up

Explain why this structure is maintainable.

Prompt 8 – Playwright Framework

Generate the Playwright framework with:

Configuration
Page Objects
Test files
Reusable methods

Follow-up

Review the framework and simplify it where possible.

Prompt 9 – Keyboard Navigation

Write a Playwright test to verify keyboard navigation using the Tab key.

Follow-up

Add assertions after each step.

Prompt 10 – Keyboard Actions

Write Playwright tests for:

Enter key submission
Escape key behaviour

Follow-up

Update the test assuming Escape clears the input field.

Prompt 11 – Prefix Filtering

Write Playwright tests for prefix-based suggestion filtering.

Follow-up

Add negative validations.

Prompt 12 – Match Anywhere Filtering

Write Playwright tests for "Match Anywhere" filtering when the feature is enabled.

Follow-up

Verify all matching suggestions are displayed.

Prompt 13 – Suggestion Selection

Write a Playwright test to select a suggestion and verify the input value.

Follow-up

Verify the selected text matches exactly.

Prompt 14 – Successful Submission

Write Playwright automation for a successful form submission.

Follow-up

Validate the network response if it can be intercepted.

Prompt 15 – Invalid Submission

Write Playwright automation for invalid input.

Verify:

Error message
Success message is not displayed
Prompt 16 – API Automation

Write API tests using Playwright APIRequestContext.

Validate:

Response contract
Required fields
Datatypes

Follow-up

Add timestamp, locale and boolean validation.

Prompt 17 – Response Schema

Create a JSON schema based on FR-05.

Follow-up

Use it to validate the API response.

Prompt 18 – Locale Validation

Write assertions to validate locale using the IETF BCP 47 format.

Prompt 19 – Timestamp Validation

Validate:

Timestamp format
end_date is after start_date
Prompt 20 – Suggestion List Validation

Validate that suggestion_list contains only the matching suggestions.

Follow-up

Also verify the comma-separated format.

Prompt 21 – Negative API Tests

Suggest negative API test cases for this endpoint.

Follow-up

Select the best two for this assignment.

Prompt 22 – README

Create a README with:

Project overview
Prerequisites
Installation
Execution steps
Folder structure

Follow-up

Review the README for clarity.

Prompt 23 – Architecture

Write a short architecture note explaining:

Project structure
Page Object Model
Scalability

Follow-up

Add a short section on future improvements.

Prompt 24 – AI Reflection

Help me prepare the AI Reflection section.

Include:

Where AI was used
What was reviewed manually
Improvements made after AI suggestions
One limitation of AI during this assignment
Prompt 25 – Final Review

Review the assignment as a QA reviewer.

Identify:

Missing validations
Weak areas
Improvements

Follow-up

Suggest interview questions based on the submission.

Prompt 26 – Repository Review

Review the Git repository structure and check whether it matches the assignment requirements.

Highlight any missing files or improvements.

Prompt 27 – Final Review

Do one final review of the entire assignment.

Verify:

Documentation
Test scenarios
Test cases
Playwright automation
API automation
README
Folder structure

Report any inconsistencies or missing items.