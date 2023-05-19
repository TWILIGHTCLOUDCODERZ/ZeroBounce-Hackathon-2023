# ZeroBounce-Hackathon-2023
## What it does

Email Syntax:
The syntax of an email address typically follows the format: username@domain. Here's a breakdown of the different parts:

Username: This is the name chosen by the user and can include alphanumeric characters, dots (.), underscores (_), and hyphens (-). It cannot start or end with a dot and cannot have consecutive dots.

@ symbol: This symbol separates the username from the domain.

Domain: This is the unique identifier for the email server. It consists of two parts: the mail server's name and the top-level domain (TLD). The TLD can be generic (e.g., .com, .net, .org) or country-specific (e.g., .us, .uk, .au).

Email addresses can have additional parts like subdomains or more complex structures, but the basic syntax outlined above is the most common.

Domain:
The domain in an email address refers to the part that comes after the @ symbol. It represents the email server where the recipient's mailbox is hosted. For example, in the email address "john.doe@example.com," the domain is "example.com."

MX Record Validation Methods:
When validating an email address, one common method is to check the Mail Exchanger (MX) records of the domain. The MX records specify the email servers responsible for accepting incoming email for a particular domain. Here are a few methods to validate MX records:

DNS Lookup: Use the DNS (Domain Name System) to query the MX records for the given domain. If there are no MX records or if the lookup fails, it indicates that the domain may not have a valid email server.

SMTP Connection: Establish a Simple Mail Transfer Protocol (SMTP) connection to the email server specified in the MX records. Send a test email or simulate a handshake to check if the server responds positively. If the connection fails or if the server rejects the test email, it suggests an issue with the email server.

Email Validation Services: Utilize email validation services or APIs that handle the MX record validation for you. These services often provide additional checks for syntax, disposable email addresses, role-based accounts, and more.

## How we built it

Built using html css and java script for email validation steps:-
Step 1: Set up the HTML structure.
Step 2: Style the page with CSS
Step 3: Add email validation with JavaScript
Step 4: Link the CSS and JavaScript files to your HTML file
Step 5: Open the HTML file in a web browser
Step 6: Deployed in Github pages 


