# BRUTE-FORCE

A Brute Force attack is a hacking method that uses trial and error to crack passwords, login credentials, and encryption keys. The hacker tries multiple usernames and passwords, often using a computer to test a wide range of combinations, until they find the correct login information.

## Types of Brute Force Attacks

### 1. Credential Brute Force

When trying to access user accounts, the process involves testing combinations of usernames and passwords. The main focus is on login endpoints.

- **Dictionary Attacks**: Employing a predetermined list of possible passwords.
- **Exhaustive Search**: Testing all potential character combinations.

### 2. Rate Limiting Evasion

Bypassing the WAF’s rate limiting rules designed to prevent too many requests in a short period. It targets any endpoint with a rate limiting feature.

- **IP Rotation**: Using multiple IP addresses to distribute the requests.
- **Time Delays**: Sending requests at intervals to stay under the rate limit frame.

### 3. Credential Stuffing

Attackers collect username and password combinations they have stolen, which they then test on other websites to see if they can gain access to additional user accounts. This approach is successful if people use the same username and password combination or reuse passwords for various accounts and social media profiles.

- **Reuse of Compromised Credentials**: The primary source of the credentials used in these attacks are previous data breaches where large amounts of usernames and passwords were leaked.

### 4. Session Hijacking and Token Brute Forcing

Trying to brute force session tokens or authentication tokens to hijack sessions.

- **Token Guessing**: Attempting to guess session tokens using known patterns or token formats.
- **Replay Attacks**: Reusing captured tokens to authenticate as a legitimate user.

## Preventive Measures

### 1. Create Strong, Multicharacter Passwords

The basic rule is passwords should be more than 10 characters in length and include capital and lowercase letters, symbols, and numerals. This vastly increases the difficulty and time it takes to crack a password.

### 2. Use Unique Passwords for Every Account

Credential stuffing allows hackers to log in to other websites if the same passwords are used on all the websites.

### 3. Use High Encryption Rates

Encrypting system passwords with the highest available encryption rates, such as 256-bit, limits the chances of a brute force attack succeeding and makes passwords harder to crack.

### 4. Use CAPTCHA to Support Logins

Adding a CAPTCHA box to the login process can prevent an attacker from using computers to brute force their way into a user account. CAPTCHA options must include checking of multiple image boxes and identifying objects that appear.



