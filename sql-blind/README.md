# Sql Blind

## Description
Blind SQL Injection allows inference of database behavior through indirect responses.

## Payload Used
' AND SLEEP(5)--

## Testing Steps
1. Inject timing-based payload.
2. Observe delayed response behavior.
3. Confirm backend query manipulation.


## Result
Database behavior confirmed through timing response.

## Risk Level
High

## Recommendation
Proper input validation, output encoding, access controls, and security filtering mechanisms should be implemented to mitigate this issue.

## Screenshot References
Relevant screenshots are available inside the screenshots directory.
