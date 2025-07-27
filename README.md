# SkyCrate
Skycrate is a web based file management system that uses Hadoop as filesystem.


1. Dockerized a Hadoop cluster to resolve dependency issues, hosting it internally and exposing it to the team via Tailscale.
2. Integrated internationalization (i18n) for multilingual support across the frontend.
3. Implemented hybrid RSA-AES encryption for each file, utilizing user-specific key pairs.
4. Established strong password policies with breach checks via Have I Been Pwned.
5. Utilized JWT-based authentication with refresh token support and a blacklist feature upon logout.
6. Implemented brute-force login protection through rate limiting.
7. Enforced HTTPS with automatic redirection from HTTP to HTTPS.
8. Enabled encrypted file upload and download to/from HDFS, with metadata stored in a database.
9. Developed audit logging and structured Data Transfer Objects (DTOs) with validation.
10. Created a token refresh endpoint and ensured secure session handling.
11. Automated user directory creation in HDFS upon user registration.
12. Enhanced Spring Security, streamlined configuration, and established a modular service structure.
