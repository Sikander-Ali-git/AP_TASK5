# SQL Injection Findings

## Objective
Identify SQL Injection vulnerabilities in DVWA.

## Attack Performed
Payload:
1' OR '1'='1'#

## Result
Multiple database records were returned due to insufficient input validation.

## Risk
Unauthorized access to sensitive data.

## Mitigation
- Prepared Statements
- Parameterized Queries
- Input Validation

