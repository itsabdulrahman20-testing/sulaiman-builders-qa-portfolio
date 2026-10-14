Bug Reports – Manual QA Testing

Project: Sulaiman Builders Website
Website: https://sulaimanbuilders72-source.github.io/Sulaiman.builders/

Purpose

This document records defects identified during manual testing. Each bug report includes steps to reproduce, expected and actual results, severity, priority, and status.

Bug Report Template

Bug Report BUG001: Contact Form Emails Sent to Incorrect Address

* Bug ID: BUG001
* Bug Title: Contact form configured with an incorrect recipient email address
* Project: Sulaiman Builders Website
* Environment: Website tested on an iPhone using a mobile browser
* Preconditions: Contact form is available.
* Steps to Reproduce:
    1. Open the website.
    2. Navigate to the Contact section.
    3. Fill in the required fields with test information.
    4. Submit the form.
    5. Verify whether the message reaches the intended recipient.
* Expected Result: The submitted message should be sent to the correct recipient email address.
* Actual Result: The recipient email address configured in the website code was incorrect, preventing the message from reaching the intended inbox.
* Root Cause: Incorrect recipient email address in the website code.
* Fix Applied: Corrected the recipient email address in the code.
* Retest Result: The contact form email was received after the correction.
* Severity: Medium (initial assessment)
* Priority: Resolved after correction
* Status: Fixed — retest passed
* Evidence: Add screenshots of the successful form submission and received email, with personal information hidden.
* Severity: Tentatively Medium — pending verification of the impact.
* Priority: To be determined by the website owner/development team.
* Status: Open — needs further verification.
* Evidence: Capture a screenshot of the success message. Record the test date and time.
* Notes: Email delivery failure has not yet been confirmed. Further checks are required to verify whether the form submission reached the backend or email service.
