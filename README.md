# Alaa Jarad — NFC Digital Business Card

Responsive digital contact card featuring Call, WhatsApp, Email, LinkedIn, and downloadable vCard contact.

## Publish free with GitHub Pages
1. Create a **public** GitHub repository, e.g. `alaa-jarad-card`.
2. Upload all four files — `index.html`, `Alaa-Jarad.vcf`, `alaa-jarad-profile.jpg`, and `README.md` — to the repository root. Keep the photo filename unchanged.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. Wait for deployment. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/alaa-jarad-card/`

## Program the NFC card
1. Open NFC Tools on your phone.
2. Choose **Write → Add a record → URL/URI**.
3. Paste the published GitHub Pages website URL (not the VCF URL).
4. Tap **Write** and hold your phone against the NFC card.
5. Test with another phone.

The NFC card stores only the website URL, so you can update the page later without rewriting the NFC chip as long as the URL remains unchanged.
