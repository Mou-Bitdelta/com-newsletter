BitDelta newsletter — 30 October 2026

Files
newsletter.html       Standard table-based email HTML with inline styling and Outlook background fallbacks.
newsletter.amp.html   AMP for Email (not AMP for websites). Official AMP validator: PASS with no warnings.
assets/               Optimized PNG and original-format SVG assets, plus email-compatible PNG versions of SVGs and exact cropped image-fill viewports.
assets-manifest.json  Source format, source dimensions, and original versus optimized byte counts. Dimensions refer to source files.
preview-600.png       Desktop browser preview.
preview-375.png       Mobile browser preview.

All runtime image URLs point to:
https://raw.githubusercontent.com/Mou-Bitdelta/com-newsletter/main/newsletter-2026-10-30/assets/

Editable text, prices, dates, and links match the supplied Figma design. They have not been independently verified as market information. Archivo falls back to Arial/Helvetica where unavailable.

Sending
Use newsletter.html as the text/html part. For AMP-capable delivery, use newsletter.amp.html as the text/x-amp-html MIME part alongside text/html and text/plain. AMP rendering requires a supported email service/client and any sender registration required by that provider. Uploading AMP as the normal HTML part does not enable AMP.
Configure your email platform's unsubscribe/preferences link and List-Unsubscribe headers before sending a campaign; the supplied design did not contain a working unsubscribe URL.

Verification
Official AMP4EMAIL validator: PASS, no errors or warnings.
Browser previews checked at 600px and 375px with all image assets loaded and no horizontal overflow.
This is browser validation; live rendering in Outlook, Gmail and Apple Mail was not tested by sending a campaign.

Figma source
https://www.figma.com/design/Cm8XEAP4claVjwLRZ71dfq/?node-id=2050-405
