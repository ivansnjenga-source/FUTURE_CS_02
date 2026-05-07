# FUTURE_CS_02
# FUTURE_CS_02 — Phishing Email Detection & Awareness System

## Task 2: Phishing Email Detection & Awareness System

### Tools Used
- MXToolbox Email Header Analyzer — SPF, DKIM, IP blacklist analysis
- Browser DevTools (Console) — Safe URL inspection
- Manual Analysis — Domain, content and language review

### Key Findings
- 3 out of 3 emails confirmed as PHISHING
- All samples failed SPF authentication
- All samples missing DKIM digital signatures
- Sample 2 sending IP was blacklisted (known Tor exit node)

### Classification Results
| Sample | Sender Domain | SPF | DKIM | Verdict |
|--------|--------------|-----|------|---------|
| Fake Bank of America | bankofamerica-alert.com | FAIL | NONE | PHISHING |
| Fake PayPal | paypal-support.net | FAIL | NONE | PHISHING |
| Fake Microsoft | microsoft-security.info | FAIL | NONE | PHISHING |

### Files in this Repository
- Phishing_Detection_Report.docx — Full detailed report
- Phishing_Detection_Presentation.pdf — Canva presentation
- Screenshots/ — MXToolbox and DevTools evidence

### Skills Gained
- Phishing detection and email threat analysis
- Email header analysis using MXToolbox
- Risk classification (Safe/Suspicious/Phishing)
- Security awareness documentation
- Client-ready report writing
