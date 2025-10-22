# Phishing Email Analysis

This repository contains a sample phishing email along with a detailed step-by-step analysis of phishing traits, including:

- Sender spoofing
- Email header discrepancies
- Suspicious links and attachments
- Urgent or threatening language
- Grammar and spelling errors
- Mismatched URLs

## Contents

- `sample_email/`: Contains a sanitized phishing email sample (`.eml` format).
- `analysis/`: Markdown report of phishing analysis.
- `tools/`: Tips and guides for analyzing email headers and detecting phishing.

## Usage

1. Open the `.eml` file in any email client or text editor to inspect the email.
2. Review the analysis in `analysis/phishing_analysis.md`.
3. Use `tools/header_analysis_tips.md` to check SPF/DKIM/DMARC and Received chain.

## References

- MXToolbox Message Header Analyzer: https://mxtoolbox.com/EmailHeaders.aspx
- Google Message Header Analyzer: https://toolbox.googleapps.com/apps/messageheader/
- KnowBe4 Phishing Guide: https://www.knowbe4.com/phishing
