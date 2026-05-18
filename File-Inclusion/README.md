# File Inclusion

## Description
File Inclusion vulnerabilities allow unauthorized local or remote file access.

## Payload Used
../../etc/passwd

## Testing Steps
1. Navigate to the file inclusion feature.
2. Inject path traversal payload.
3. Observe included file content.


## Result
Sensitive server-side files became accessible.

## Risk Level
High

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
