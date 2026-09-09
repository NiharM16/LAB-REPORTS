# Lab Writeups

Professional lab reports from hands-on web application security testing, produced while working through PortSwigger Web Security Academy labs using Burp Suite. Part of a structured 90-day AppSec learning roadmap.

Each report follows a consistent format: report metadata, step-by-step execution with captioned screenshots, impact, remediation, and conclusion.

## Index

| Category | Labs |
|---|---|
| [Authentication & Sessions](authentication-and-sessions/) | Session fundamentals, 2FA bypass |
| [Access Control](access-control/) | Host header bypass, Referer-based access control |
| [Injection](injection/) | First applications, SQL injection login bypass |
| [XSS](xss/) | DOM XSS (document.write, innerHTML, jQuery href sinks), Reflected XSS, browser trust |
| [Concept References](concept-references/) | AuthN vs AuthZ, IDOR, Horizontal/Vertical access control |
| [HTTP Fundamentals](http-fundamentals/) | HTTP & Burp Suite introduction |
| [Reports](reports/) | Synopsis report |

## Status legend

Each report file is suffixed with its status:

- `_v1` — first complete pass, not yet reviewed
- `_draft` — in progress / pending revision
- `_final` — reviewed and complete

## Structure

Each lab lives in its own folder as `<category>/<lab-name>/`, containing the `.docx` report and a short `README.md` stub describing the lab so it's readable without opening the file.

See [`FILE_MAPPING.md`](FILE_MAPPING.md) for where each existing report file goes, including flagged duplicates to resolve before the first commit.
