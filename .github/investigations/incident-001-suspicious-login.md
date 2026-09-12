# Incident 001 – Suspicious Geographic Sign-in

## Scenario

A successful Microsoft 365 sign-in was detected from an unfamiliar geographic location shortly after activity from a known location.

## Severity

Medium to High, depending on supporting evidence.

## Initial Triage

The analyst should determine:

- Who performed the login?
- Where did the login originate?
- What IP address was used?
- Which application was accessed?
- Was MFA completed?
- Was the device recognised?
- Is the location expected for the user?

## Investigation Steps

1. Review Microsoft Entra ID sign-in logs.
2. Identify the source IP address.
3. Review geographic location.
4. Check device information.
5. Review MFA and authentication details.
6. Search for additional suspicious activity.
7. Determine whether the activity is legitimate.

## Potential Indicators of Compromise

- Unfamiliar country
- Unfamiliar IP address
- New device
- Suspicious authentication activity
- Multiple geographic locations within a short period

## Recommended Response

If compromise is suspected:

1. Revoke active sessions.
2. Reset the user's password.
3. Review registered MFA methods.
4. Investigate additional sign-in activity.
5. Block malicious infrastructure where appropriate.
6. Continue monitoring the account.

## Conclusion

The alert should not automatically be treated as a confirmed compromise. Additional evidence is required before making a final determination.
