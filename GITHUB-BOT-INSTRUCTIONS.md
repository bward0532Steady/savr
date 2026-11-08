# COPY THIS ENTIRE BRIEF INTO THE GITHUB ASSISTANT

Build and publish a minimal public website called **SAVR — Signature Analysis & Verification Registry** using the attached files. I own the project. I want it live quickly, for $0 monthly, with GitHub Pages and no database, subscriptions, paid apps, build pipeline or framework.

## Immediate tasks
1. Create a public repository named `savr` in my GitHub account, or use the existing repo if I specify one. Do not delete existing files without asking.
2. Commit the attached `index.html`, `verify.html`, `record.schema.v1.1.json`, and `assets/savr-brand-board.png` to the repository root as shown.
3. Enable GitHub Pages from the main branch, root folder. Wait for deployment and give me the ACTUAL published URL. Do not invent or assume my username.
4. Open/test the live homepage and verification URLs. Test on mobile viewport and ensure the site does not render an empty black section.
5. Make sure `https://<ACTUAL_USERNAME>.github.io/savr/verify.html?id=SAVR-000001` loads the music demo and `...id=SAVR-000002` loads the historical demo. Both MUST prominently say DEMONSTRATION — NOT VERIFIED, not AUTHENTICATED.
6. Keep a working serial search and clear "Record not found" response. No misleading green verified status for demo items.
7. Give me simple instructions for adding my FIRST REAL ITEM: I will supply a photograph, item title, category, signer/creator, my determination (Pending, Verified, or Not Verified), and optional NFC UID/tamper serial. Create a new record only from those facts; never invent evidence or authentication conclusions.
8. Keep the SAVR gold/black/crimson brand identity and broad categories: Sports; Music & Entertainment; Film & TV; Art & Collectibles; Historical & Cultural. The brand board is visual reference, not a real certificate or a source of verified item data.
9. Keep the two certificate types: `signature_authentication` and `artifact_verification`. A record may be listed as pending or not verified; do not call it authenticated without a documented issuer decision.
10. Return the live link for the first NFC card. Use an HTTPS URL pointing directly to an item record. NFC Tools writes that URL to NTAG215; the buyer needs no app.

## Important technical details
- This is static hosting: no server-side authentication, no admin dashboard, no secret keys in public code. To add/change records initially, edit and commit repository files. Do NOT expose a public editable form or promise that visitors can publish records.
- The existing `verify.html` has two embedded demo records. They are sample placeholders, not authentic items. For quick launch, leave them embedded. Later, refactor into `records.json` only if that does not delay launch.
- Preserve serial format `SAVR-000001`, tamper label format `SAVR-T000001`.
- Brand colors: black `#0B0D10`, gold `#D4AF37`, crimson `#8B0000`, green `#1E7E34` (verified real records only), silver `#C0C0C0`, ivory `#F9F6F0`.
- Montserrat regular and bold; mobile-first, high contrast, accessible labels.
- The `assets/savr-brand-board.png` is an AI-created concept image; it includes illustrative certificates, dates, QR codes, and marks. Do not reuse its example QR codes or imply its examples are real. Do not use ® until trademark registration is confirmed.
- Verification of a registry serial or a standard NTAG215 URL is NOT cryptographic proof of a physical item's authenticity.
- If GitHub Pages is not enabled, explain the exact settings I need to approve. Do not claim deployment succeeded without a real working URL.

## Definition of done
A buyer can visit the live SAVR homepage, enter a serial number, view the matching item information and verification status, and share the direct HTTPS link. I can send you a new item's facts and have you update the repository. Keep it simple and ship today.
