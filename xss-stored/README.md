# Xss Stored

## Description
Stored XSS permanently stores malicious scripts inside the application.

## Payload Used
<script>alert(document.cookie)</script>

## Testing Steps
1. Submit persistent payload.
2. Reload affected page.
3. Verify repeated script execution.


## Result
Stored malicious script executed for multiple sessions.

## Risk Level
High

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
