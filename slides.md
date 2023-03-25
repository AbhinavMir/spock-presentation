---
# try also 'default' to start simple
theme: apple-basic
class: 'text-center'
highlighter: shiki
lineNumbers: true
---

# Problem
- Traditional username and password authentication system has long been a target for cybercriminals
- Cybercriminals steal user credentials and gain unauthorized access to sensitive information
- Even with complex passwords and two-factor authentication, user accounts are still vulnerable to hacking attempts
- Password-based authentication system is cumbersome and users often struggle to remember multiple login credentials
---
# Importance
- Spock offers a passwordless authentication system using public/private ECDSA keys to verify user identity
- Spock aims to provide a more secure, user-friendly, and convenient login experience for both users and developers
- By eliminating the need for traditional passwords, Spock makes it more difficult for cybercriminals to steal user credentials and gain unauthorized access to sensitive information
---
# Project Identification
- Need for a more secure and user-friendly authentication system has been identified by cybersecurity experts and researchers
- Passwordless authentication using public/private key pairs is gaining popularity as a more secure alternative to traditional password-based systems
- Spock aims to build on this trend and provide a comprehensive and easy-to-use authentication solution for web applications
---
# Technical Approach
- Spock uses public/private ECDSA key pairs to authenticate users
- The user generates a key pair that is stored securely on their device
- When they want to log in to a website or application that uses Spock, they sign a challenge with their private key, which is then verified by the server using the user’s public key
- The Spock SDK provides developers with the necessary tools to integrate passwordless authentication into their web applications
---
# Intermediary Results
- Spock is still in development
- No intermediary results have been achieved yet
- Spock's technical approach has been designed and is being tested to ensure that it is secure, reliable, and compatible with different browsers and web applications
---
# Related Work
- Other passwordless authentication solutions available in the market, such as biometric authentication and one-time passwords
- These methods still require users to remember some form of login credentials or use specialized hardware devices
- Public/private key authentication offers a completely passwordless solution that eliminates the need for users to remember any login credentials
- Spock aims to build on this concept and offer a more user-friendly and convenient authentication system for web applications
