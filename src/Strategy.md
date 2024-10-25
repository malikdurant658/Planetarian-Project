# Test Strategy Document

## Testing Strategies
- Boundary Value Analysis: Test input values at the outliers of input ranges, such as the minimum and maximum password lengths.
- Equivalence Partitioning: Divide input data into valid and invalid classes, such as testing uniqueness of usernames.
- Error Guess Testing: Identify potential defects by testing common error scenarios, like submitting forms without required inputs.
- Exploratory Testing: Perform unscripted testing to discover defects and assess usability, focusing on user navigation, interactions, and system responses to unexpected behavior.

## Strategies for Use Cases
- Account Creation & Login: Test with valid and invalid data to ensure account creation and login functionality works properly.
- Planet & Moon Management: Ensure that the creation and deletion of planets and moons behave as expected for both valid and invalid data.
- Access Control: Ensure users can only manage their own planets and moons.

## Testing Objectives
- Broad Goal: Ensure that the Planetarium system is stable, secure, and functional according to specifications.
- Specific Objectives:
  - Verify all user interactions and data inputs work as expected.
  - Ensure proper error handling for invalid inputs.
  - Validate security controls (e.g., no plaintext passwords, restricted access).
  - Confirm smooth integration of all components.

## Effort Estimate
- Boundary Value Analysis: 1 day
- Equivalence Partitioning: 2 days
- Error Guess Testing: 1-2 days
- Exploratory Testing: 3-5 days