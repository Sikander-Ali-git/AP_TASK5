# Cross Site Scripting Findings

## Stored XSS
Payload:
<script>alert('Stored XSS')</script>

## Reflected XSS
Payload:
<script>alert('Reflected XSS')</script>

## Risk
Execution of malicious JavaScript in victim browsers.

## Mitigation
- Output Encoding
- Content Security Policy
- Input Validation
