# ShadyURL 🔗

**Live site:** https://jlaiii.github.io/ShadyURL/

Make your links look sketchy as hell. Perfect for pranking friends.

## How it works

1. Go to the site
2. Paste any URL (YouTube, Google, whatever)
3. Pick a shady theme like `download-free-creditcard-generator` or `urgent-court-summons-pdf`
4. Choose link length: **Mid** or **Very Very Long**
5. Copy the generated link and send it to your friends
6. They click it, see a fake "security alert" screen, then get redirected to your actual URL

## Example

Input: `https://youtube.com`

Output (Mid):  
`https://jlaiii.github.io/ShadyURL/download-free-creditcard-generator/confirm/secure/validate/redirect/#aHR0cHM6Ly95b3V0dWJlLmNvbQ`

Output (Very Very Long):  
`https://jlaiii.github.io/ShadyURL/download-free-creditcard-generator/confirm-account-verification/secure-authentication-gateway/identity-validation-process/external-resource-redirect/session-token-validation/two-factor-bypass-module/?ref=...&track=pixels&utm=scam&.../#aHR0cHM6Ly95b3V0dWJlLmNvbQ`

Looks sketchy. Goes exactly where you wanted.

## Tech

Pure static HTML/CSS/JS. Hosted free on GitHub Pages. No backend, no database, no tracking. The destination URL is encoded in the link itself with URL-safe base64.

## Disclaimer

This is a joke / prank tool. It does NOT contain malware, viruses, or anything harmful. It simply redirects to the URL you entered. Use responsibly.
