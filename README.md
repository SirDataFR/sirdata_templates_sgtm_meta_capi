# Optimizing Meta/Facebook Conversion API in GTM Server-Side with Enhanced Consent and Data Handling

You can use this tag in the Google Tag Manager Server-Side container to configure the Meta/Facebook Conversion API and manage cookies, data transmission, and pixel activation directly in the browser with built-in controls.

The tag operates based on GA4 requests and supports custom settings and parameters.

The Facebook Conversion API (formerly known as Facebook server-side tracking) serves the same purpose as the Facebook Pixel, tracking user interactions on your website. However, while the Pixel processes requests in the user's browser, the Conversion API operates through a cloud server, enabling various optimizations such as bypassing ad blockers.

This tag works with any container hosting service (Google Cloud, Stape, Sirdata, Taggrs), and is optimized for Sirdata's data enrichment layer, which is compatible with all hosting platforms. This additional layer of data enables several enhancements, including:
- Utilizing TCF consent signals in addition to Consent Mode signals
- Supporting a cookieless user ID when consent is not provided
- Handling consent under GDPR where applicable, and adjusting behavior where GDPR does not apply.
