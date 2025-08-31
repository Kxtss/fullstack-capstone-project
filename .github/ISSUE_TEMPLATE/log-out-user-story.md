**As a** logged-in user,
**I need** to be able to log out securely
**So that** my account is not accessible to others on a shared device.

### Details and Assumptions

    - The user must be logged in to see the "Log Out" option.
    - After logging out, the user should not be able to access any pages that require authentication.

### Acceptance Criteria

    Given I am logged in to my account,
    When I click the "Log Out" button in the navigation menu,
    Then I am signed out of my account and redirected to the login page.
