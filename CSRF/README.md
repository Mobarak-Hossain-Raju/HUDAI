# Csrf

## Description
CSRF vulnerabilities allow attackers to perform actions on behalf of authenticated users.

## Payload Used
Forged authenticated request

## Testing Steps
1. Generate unauthorized request.
2. Submit request while authenticated.
3. Verify action execution.


## Result
The application accepted unauthorized state-changing requests.

## Risk Level
Medium

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
