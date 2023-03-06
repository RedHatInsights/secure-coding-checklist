Input Validation: Never Trust User Input
----------------
- Check data length
- Validate characters set
- Check data format
- Use restrictions

Manage Authentication and Passwords
----------------
- Use transport layer security (TLS) client authentication
- Implement authentication error messages
     If your error message clearly states that a specific username doesn’t exist, the user will know it, but it means the attacker will, too. And this will give him an advantage. Never give out too much information. This will ensure that if the authentication fails, the user (or bad guy) will get a generic error message that doesn’t provide them with info they can use to try to access the application
- Store, control and manage your passwords safely
- Transmits passwords securely
- Never store credentials within the app’s script
    Even if embedding credentials as plain text into codes can be handy during development, it’s never a good idea. Why? Because often people forget to remove the credentials before publishing their code on sites like GitHub. This serves up your credentials as a feast to bad guys, and that can have serious consequences for you and your customers. For a real-world example of this type of situation, just look at what [happened to Uber](https://www.trendmicro.com/vinfo/pl/security/news/cybercrime-and-digital-threats/uber-breach-exposes-the-data-of-57-million-drivers-and-users) back in 2016…

Sanitize Data First, Then Send the Inputs to Other Systems
----------------
- Use a whitelist (allowlist)
- Use a blacklist (blocklist)
- Escape inputs to keep things safe

Adopt the Principle of Least Privilege
----------------
- Validate permissions on every request
- Create tests to validate permissions before release
- Periodically review permissions

Architecture: Make It Unique and Secure
----------------
- Use subsystems
- Follow OWASP’ secure architecture (SA) practice
- Load only secure plugins and libraries

Keep It Intuitive But Effective
----------------
- Use a simple and small design
- Don’t over-complicate your security controls
- Be user-friendly

Deny Access by Default
----------------
- Keep unauthenticated users out
- Apply this policy to new user accounts too
- Keep new features sealed

Secure Your Work and Communication
----------------
- Use strong, readily available encryption
- Protect your database
- Use trusted security certificates
- Sign your code before releasing it

Check the Quality of Your Code and Follow Coding Standards
----------------
- Review your code
- Use effective quality assurance mechanisms
- Use coding standards developed by international bodies
- Prevent attacks with threat modeling



