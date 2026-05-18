# Sql Injection

## Description
SQL Injection occurs when user input is executed directly inside database queries.

## Payload Used
' OR '1'='1

## Testing Steps
1. Insert SQL payload into vulnerable parameter.
2. Submit request.
3. Observe unauthorized database output.


## Result
Authentication bypass and database disclosure were successful.

## Risk Level
High

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
