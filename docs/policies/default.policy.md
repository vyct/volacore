# Default Execution Policy

rule: DEFAULT_DENY

description:
All AI execution is denied unless explicitly authorized
by a signed and validated policy.

allow:
- none

deny:
- all
