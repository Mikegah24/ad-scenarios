# ad-scenarios

### Scenario 1: Account Lockout After Failed Logins

Goal: Trigger and observe an account lockout after repeated failed login attempts.

Steps:

- Create a GPO to set lockout policy (3 failed attempts, 5 min duration).

- Use one of the users to login

- Use the CLIENT1 machine to attempt incorrect logins for a user.

- Enter Wrong password and until you are locked out. And see the message...

- View logs on DC1 using Event Viewer.
