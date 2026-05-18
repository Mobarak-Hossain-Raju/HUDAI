# Xss Reflected

## Description
Reflected XSS executes malicious scripts immediately through reflected input.

## Payload Used
<script>alert(1)</script>

## Testing Steps
1. Insert JavaScript payload.
2. Submit vulnerable request.
3. Observe browser execution.


## Result
Client-side script execution was successful.

## Risk Level
Medium

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
