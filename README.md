# Scenarios

### Scenario 1: Account Lockout After Failed Logins

Goal: Trigger and observe an account lockout after repeated failed login attempts.

Steps:

- Create a GPO to set lockout policy (3 failed attempts, 5 min duration).

- Use one of the users to login

- Use the CLIENT1 machine to attempt incorrect logins for a user.

- Enter Wrong password and until you are locked out. And see the message...

<img src="https://github.com/user-attachments/assets/50d14822-53e5-4aa2-9adb-552ea239a867" height="75%" width="75%" alt="Disk Sanitization Steps"/>

- On the DC unlock the account for the user.
- Go to Users and Computers, Double-click User, Account.
- Check Unlick account, OK.
- 
<img src="https://github.com/user-attachments/assets/6e3a4129-6c2c-4a8f-bedf-7a9bd8082bd8" height="65%" width="65%" alt="Disk Sanitization Steps"/>
  

  
- View logs on DC1 using Event Viewer.


