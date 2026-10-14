Bug Reports

This document contains defects identified while testing the Sulaiman Builders website.

BUG001: Contact form email recipient was incorrectly configured

Bug ID: BUG001
Project: Sulaiman Builders Website
Module: Contact Form / Email Functionality
Severity: Medium
Priority: Medium
Status: Fixed — Retest Passed
Testing Type: Functional Testing

Description

The contact form email functionality was not working as expected because the recipient email address was incorrectly configured in the website code.

Steps to Reproduce

1. Open the Sulaiman Builders website.
2. Navigate to the contact form.
3. Submit the form with the required details.
4. Check whether the submitted message reaches the configured recipient.

Expected Result

The contact form message should be delivered to the correct recipient email address.

Actual Result

The message was not received because the recipient email address was incorrectly configured.

Root Cause

The recipient email address in the website code was incorrect.

Fix Applied

Corrected the recipient email address in the website code.

Retest Result

After correcting the recipient address, submitted a test message and verified that the email was received successfully.

Retest Status: PASS

Evidence

Screenshots of the contact form and successful email delivery can be added here.
