KantekGO simple auth demo
Files:
- index.html       (home page)
- login.html       (login page)
- signup.html      (signup page)
- status.html      (protected page)

How to use:
1. Unzip and open index.html in your browser.
2. Click 'Masuk / Daftar' to create an account (stored in localStorage).
3. After signup you'll be auto-logged in. Click a gerai to view status.html.

Security:
- This is client-side demo only. Passwords are stored in localStorage in plaintext.
- Do NOT use this approach in production. Implement backend, hashing, HTTPS, sessions.