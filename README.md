# ad-scenarios

### Scenario 1: Account Lockout After Failed Logins

Goal: Trigger and observe an account lockout after repeated failed login attempts.

Steps:

Create a GPO to set lockout policy (3 failed attempts, 5 min duration).

Use the CLIENT1 machine to attempt incorrect logins for a user.

View logs on DC1 using Event Viewer.

Event ID 4625 → failed logon

Event ID 4740 → account locked out

(Optional) Export .evtx log file.
