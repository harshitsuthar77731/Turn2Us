# Turn2Us
This repository is for the Turn2Us Apprentice technical test.

## Test Briefing

Create a basic homepage that will feature an age checker. This functionality is required to 
ensure users are of the appropriate age (18 years and older) to be eligible for benefits. Feel free 
to refer to any specific benefits from our welfare system to make the scenario more relatable 
(e.g., Universal Credit).

Your goal is to develop three distinct pages: a homepage, a success page for eligible users, and 
an error page for those too young to proceed. This test is designed to evaluate not only your 
coding abilities but also your understanding and basic implementation of accessibility 
principles. Accessibility is a core value of Turn2Us, as we strive to create inclusive digital tools 
for all our users, especially for those with disabilities

## User Stories

### User Story 1:
Title: Age Verification and Immediate Feedback
As a user, I want to enter my age and receive immediate feedback on the same page, so that I can instantly 
know whether I meet the age requirement to access benefits and do not have to navigate to a different page for this information.

Includes:

- Input for age on the homepage.
- Immediate feedback mechanism on eligibility.
- Accessibility features for the input and feedback areas (e.g., clear labels, high contrast, screen reader compatibility).

### User Story 2:
Title: Accessing Information After Successful Age Verification
As an eligible user, I want to be automatically redirected to a success page that details the benefits I qualify for,
So that I can learn about the benefits available to me without additional navigation hurdles.

Includes:

- Automatic redirection to the success page upon eligibility.
- Information about benefits laid out in an accessible format.

### User Story 3:
Title: Clear and Accessible Error Handling
As a user who does not meet the age criteria, I want to receive a clear, understandable explanation directly on the homepage, so 
that I am well-informed about why I cannot proceed and what steps I might consider next.

Includes:

- Error feedback provided on the homepage for users under the age limit.
- Suggestions for alternative actions or explanations regarding eligibility.
- Navigation aids to return to the homepage or to other relevant information easily accessible.

### User Story 4:
Title: Ensuring Full Accessibility in Navigation
As a user who relies on a screen reader or keyboard-only navigation,I want to easily navigate all pages of the site using just my keyboard or screen reader,
so that I can use the site independently without requiring mouse interaction.

Include:

- Keyboard Navigation: Ensure that all interactive elements are reachable and usable with the keyboard alone. This includes logical tab orders, visible focus indicators, and accessible dropdowns.
- Screen Reader Compatibility: Use ARIA roles and properties to enhance element descriptions. Make sure that form labels are properly linked to their inputs, headings are correctly used for structure, and all non-text content has text alternatives.
- Error Handling and Feedback: Provide accessible error messages and feedback that are easily interpreted by screen readers, allowing users to understand and rectify errors without visual cues.
- Consistent Navigation: Implement consistent navigation mechanisms across all pages to prevent disorientation among users unfamiliar with visual cues. This can include repeated navigation bars and proper landmark roles.
