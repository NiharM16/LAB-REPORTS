# File Mapping

Where each existing report goes, based on the current file list. Rename as noted, then drop into the target folder.

| Current name | Target folder | Rename to |
|---|---|---|
| Authentication and sessions V1 | `authentication-and-sessions/sessions-fundamentals/` | `sessions-fundamentals_v1.docx` |
| Authentication and sessions | `authentication-and-sessions/sessions-fundamentals/` | ⚠️ duplicate of above — confirm which is newer, keep one |
| 2FA simple bypassV1 | `authentication-and-sessions/2fa-bypass/` | `2fa-bypass_v1.docx` |
| 2FA_Simple_Bypass_Lab_Report | `authentication-and-sessions/2fa-bypass/` | ⚠️ duplicate of above — likely the final version; if so keep as `2fa-bypass_final.docx` and drop the V1 |
| Lab_ Host header authentication bypass Final | `access-control/host-header-bypass/` | `host-header-bypass_final.docx` |
| Lab_ Referer-based access control V1 | `access-control/referer-based-access-control/` | `referer-based-access-control_v1.docx` |
| Injection and first applications V1 | `injection/first-applications/` | `first-applications_v1.docx` |
| SQL injection vulnerability allowing login bypassV1 | `injection/sql-injection-login-bypass/` | `sql-injection-login-bypass_v1.docx` |
| _DOM XSS in document.write sink using source location.search Draft | `xss/dom-xss-document-write/` | `dom-xss-document-write_draft.docx` |
| DOM XSS in innerHTML sink using source location.search Draft | `xss/dom-xss-innerhtml/` | `dom-xss-innerhtml_draft.docx` |
| DOM XSS in jQuery anchor href attribute sink using location Draft | `xss/dom-xss-jquery-href/` | `dom-xss-jquery-href_draft.docx` |
| Reflected XSS into HTML context with nothing encoded Draft | `xss/reflected-xss-html-context/` | `reflected-xss-html-context_draft.docx` |
| XSS and browser trust Draft | `xss/xss-and-browser-trust/` | `xss-and-browser-trust_draft.docx` |
| Authentication vs. Authorization, IDOR, and Horizontal_Vertical Access Control Draft | `concept-references/` | `authn-vs-authz-idor-access-control_draft.docx` |
| HTTP and Burp Suite_ Introduction and Lab Report Final | `http-fundamentals/burp-suite-intro/` | `burp-suite-intro_final.docx` |
| Synopsis Report | `reports/synopsis/` | `synopsis_final.docx` |

## Before your first commit

1. **Resolve the two duplicate pairs** (sessions, 2FA) — open both, keep the more complete/recent one, delete the other rather than committing both.
2. All the XSS and the AuthN/AuthZ concept report are still `_draft` — worth finishing those passes before pushing, or push as-is and let the suffix signal it's WIP (a portfolio with visible in-progress work reads as honest, not sloppy).
3. Once files are placed, delete this `FILE_MAPPING.md` — it's a one-time migration aid, not part of the permanent repo.
