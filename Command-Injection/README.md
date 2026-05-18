# Command Injection

## Description
Command Injection allows execution of system commands through unsanitized user input.

## Payload Used
127.0.0.1 && whoami

## Testing Steps
1. Access the vulnerable command execution feature.
2. Insert malicious command payload.
3. Submit request and review server response.


## Result
System command execution was successfully observed.

## Risk Level
High

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
