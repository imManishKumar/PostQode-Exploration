# Reddit Login Page - Critical Functional Scenarios

## Test Scenarios

| TC ID | Type | Scenario | Steps | Expected Result |
|---|---|---|---|---|
| TC_CRIT_01 | Critical Functional | Verify user can open the Reddit login modal from the login page | 1. Open the Reddit login page<br>2. Click the `Log In` button | The login modal should open successfully and display authentication options and login fields. |
| TC_CRIT_02 | Critical Functional | Verify login with email/username and password fields are available and accept input | 1. Open the login modal<br>2. Enter a valid email or username in the `Email or username` field<br>3. Enter a password in the `Password` field | Both fields should accept input correctly without UI issues. |
| TC_CRIT_03 | Critical Functional | Verify the user can continue login using Google authentication | 1. Open the login modal<br>2. Click `Continue with Google` | The Google sign-in flow should launch successfully for authentication. |
| TC_CRIT_04 | Critical Functional | Verify the user can request login via one-time link using email | 1. Open the login modal<br>2. Click `Email me a one time link`<br>3. Provide a valid email address when prompted | The system should accept the email and initiate the one-time login link process successfully. |

## Notes
- These scenarios are based on the Reddit login modal visible in the provided screenshot.
- The scenarios focus on core login functionality and authentication entry points.
