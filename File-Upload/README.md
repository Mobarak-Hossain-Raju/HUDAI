# File Upload

## Description
Insecure file upload vulnerabilities allow execution of malicious files on the server.

## Payload Used
shell.php

## Testing Steps
1. Upload crafted executable file.
2. Access uploaded file location.
3. Verify successful execution.


## Result
Uploaded malicious file executed successfully.

## Risk Level
High

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
