![LAB-REPORTS](https://socialify.git.ci/NiharM16/LAB-REPORTS/image?custom_description=Professional+security+lab+write-ups%E2%80%94web+app+pentesting+and+blue+team+detection.&description=1&font=Source+Code+Pro&name=1&owner=1&pattern=Circuit+Board&theme=Dark)

# LAB-REPORTS

Professional security lab writeups documenting hands-on web application
security testing, based on the PortSwigger Web Security Academy.

## Contents

| Folder | Focus |
|---|---|
| `portswigger/` | PortSwigger Web Security Academy labs (Burp Suite) |
| `concepts/` | Reference notes on core AppSec topics |

## Report Format

Each report follows a consistent template:

- Index with dot leaders
- Report Metadata table (lab name, category, date, tooling, difficulty)
- Step-by-step execution with captioned figures
- Impact assessment
- Remediation guidance
- Conclusion

## Progress

**Week 1 — HTTP and Burp**

- Basic Password Reset Poisoning
- Password Reset Poisoning via Dangling Markup
- Host Header Authentication Bypass

**Week 2 — Authentication and Sessions**

- Username Enumeration via Different Responses
- 2FA Simple Bypass
- URL-Based Access Control Bypass
- Referer-Based Access Control Bypass

**Week 3 — Access Control**

- Authentication vs. Authorization, IDOR, horizontal/vertical access control
- Portfolio-quality report on access control findings

**Week 4 — Injection and First Applications**

- SQL injection fundamentals and parameterized queries
- Applied findings against real-world target applications

**Week 5 — XSS and Browser Trust**

- Stored, reflected, and DOM-based XSS
- Remediation walkthrough for a live finding

**Week 6 — API Security**

- Endpoint enumeration, object-level authorization, rate limiting.

## Tooling

Burp Suite Community

## Disclaimer

All testing was performed on PortSwigger Web Security Academy, a platform
that explicitly authorizes this kind of testing. Nothing here is intended
for use against systems you do not own or have permission to test.

## License

MIT — see [LICENSE](LICENSE).
