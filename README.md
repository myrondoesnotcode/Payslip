# Israeli Payslip Explainer 🇮🇱🇺🇸

A simple, free tool for understanding your Israeli payslip (תלוש משכורת) in plain English.

**Live site:** https://myrondoesnotcode.github.io/Payslip/

## How it works

1. Upload your payslip PDF
2. The tool reads the text directly in your browser
3. Every Hebrew line is matched against a built-in dictionary of Israeli payslip terms
4. You get a clean English breakdown instantly — no API key, no account, completely free

## Privacy

- Your payslip never leaves your device
- No data is sent to any server
- Everything runs locally in your browser

## Supported payslip items

The tool recognizes all standard Israeli payslip terms including:

**Earnings:** Base salary, overtime, travel allowance, meal allowance, bonus, holiday gift, recreation pay (Havra'a), vacation payout, sick pay

**Deductions:** Income tax (Mas Hachnasa), National Insurance (Bituach Leumi), Health tax (Mas Briut), Pension (employee portion), Keren Hishtalmut (employee), loan repayments

**Employer contributions:** Pension (employer), Keren Hishtalmut (employer), Severance reserve, Disability insurance, Life insurance

## Requirements

Your payslip must be a **digital PDF** (one where you can select/highlight text). Scanned image PDFs won't work since there's no text layer to read.

Most payroll systems in Israel (iCount, Priority, HRPro, etc.) produce digital PDFs by default.

## Deploying to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Source: **Deploy from branch → `main` → `/ (root)`**
4. Your site will be live at `https://yourusername.github.io/Payslip/`
