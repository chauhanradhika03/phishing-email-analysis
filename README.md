# phishing-email-analysis
Analysis of phishing emails to identify malicious indicators and social engineering techniques.


**Objective**

The objective of this project is to analyze suspicious phishing URLs and identify indicators commonly used in phishing attacks and social engineering campaigns.

This project demonstrates how attackers use fake domains, impersonation techniques, misleading branding, and malicious links to trick users into revealing sensitive information.

**Tools Used**

- VirusTotal
- PhishTank
- Web Browser
- Manual URL Analysis

**Steps Performed**

1. Collected phishing and suspicious URL samples from PhishTank
2. Analyzed suspicious domains and URL structures
3. Examined phishing indicators and impersonation techniques
4. Verified URLs using VirusTotal
5. Documented findings and risk levels

**Analysis & Findings**

| Email/URL | Suspicious Indicator | Risk Level |
|------------|----------------------|-------------|
| smartpay1-1gb.pages.dev | Suspicious hosted phishing domain | High |
| beneflt-resources.com | Typosquatting impersonation domain | Medium |
| facebook-invoice.invoice-ads-manager.com | Fake Facebook invoice impersonation domain | High |

**URL Analysis**

**Email Sample 1**

*Suspicious URL*

https://smartpay1-1gb.pages.dev/

**Indicators Found**

- Suspicious subdomain structure
- Hosted on free cloud infrastructure
- Potential credential harvesting attempt
- Randomized naming convention
- Detected by security vendors on VirusTotal

**Risk Level**

High

**VirusTotal Result**

2 out of 93 security vendors flagged the URL as malicious during analysis.

**Email Sample 2**

*Suspicious URL*

http://www.beneflt-resources.com/

**Indicators Found**

- Typosquatting domain ("beneflt" instead of "benefit")
- Uses HTTP instead of HTTPS
- Suspicious impersonation-style naming
- Potential social engineering attempt

**Risk Level**

Medium

**VirusTotal Result**

No security vendors flagged the URL as malicious at the time of analysis. However, manual inspection revealed phishing indicators commonly associated with impersonation attacks.

**Email Sample 3**

*Suspicious URL*

https://facebook-invoice.invoice-ads-manager.com/

**Indicators Found**

- Impersonates Facebook branding
- Misleading invoice/payment-related naming
- Suspicious multi-level subdomain structure
- Possible business account phishing attempt
- Designed to create urgency and trust

**Risk Level**

High

**VirusTotal Result**

The domain structure and impersonation behavior strongly indicate phishing or credential harvesting activity.

**Key Learnings**

Through this project, the following cybersecurity concepts were explored :

- Phishing detection techniques
- URL and domain analysis
- Typosquatting identification
- Social engineering tactics
- Threat intelligence verification using VirusTotal
- Manual phishing investigation methods

**Conclusion**

- This project demonstrates how phishing attacks use deceptive domains, impersonation techniques, and social engineering tactics to target users.
- The analysis highlights the importance of manual investigation in addition to automated security tools, since some phishing domains may not yet be detected by antivirus vendors.
- Identifying suspicious domains, fake branding, and malicious URL structures can help prevent credential theft and cyber attacks.
