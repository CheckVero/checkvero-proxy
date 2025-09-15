Check Vero — Add‑ons (Links page + Email signature)

Where to put these files in your GitHub repo (checkvero-proxy):

- public/links/index.html  → becomes https://www.checkvero.org/links/
- (Optional) public/email_signature_marcel.html → just for storage/backup (not needed for live use)

How to use the email signature (quick):
1) Open public/email_signature_marcel.html in your browser.
2) Select all → copy → paste into your email client's signature editor.
   - Gmail: Settings → See all settings → General → Signature → Create new → paste (Rich Text).
   - Apple Mail (macOS): Mail → Settings → Signatures → + → paste (uncheck 'Always match my default message font' if needed).
   - Outlook (web): Settings gear → Mail → Compose and reply → New signature → paste.
   - Outlook (desktop): File → Options → Mail → Signatures → New → paste.

Tips:
- Change the phone number/title inline after pasting.
- Images are referenced via https://www.checkvero.org/logo/... so keep those files in /public/logo/ on Vercel.
- If an email client blocks remote images by default, the recipient will still see alt text and can click 'display images'.
