# Privacy Policy for zMEGA VPN

**Last updated:** September 29, 2026

---

## 1. Overview

zMEGA VPN ("the Extension") is a browser proxy extension that routes your browser traffic through a proxy server to help you access websites freely and privately. This Privacy Policy explains what data the Extension collects, stores, and transmits.

---

## 2. Data We Do NOT Collect

The Extension does **not** collect, store, or transmit:

- Your browsing history
- Websites you visit
- Your real IP address
- Personal information (name, email, phone number)
- Cookies or login credentials
- Any analytics or telemetry data

---

## 3. Data Stored Locally on Your Device

The Extension stores the following data **locally on your device only** using the browser's built-in storage API (`chrome.storage.local`). This data never leaves your device and is never transmitted to any server:

| Data | Purpose |
|------|---------|
| Selected server | Remember which proxy server you chose |
| Language preference | Remember your interface language |
| WebRTC protection setting | Remember your privacy setting |
| Connection state | Restore connection state after browser restart |

---

## 4. Proxy Server Connection

When you enable the VPN, your browser traffic is routed through our proxy server. The proxy server processes network requests on your behalf. The proxy server:

- Does **not** log your browsing activity
- Does **not** store your IP address beyond the duration of the connection
- Does **not** sell or share your traffic data with third parties

---

## 5. Third-Party Connectivity Checks

The Extension periodically sends requests to the following URLs to measure connection latency and verify proxy availability:

- `https://www.cloudflare.com/cdn-cgi/trace`
- `https://www.gstatic.com/generate_204`
- `https://www.apple.com/library/test/success.html`
- `https://detectportal.firefox.com/success.txt`

These requests are standard connectivity probes. No personal data is included in these requests.

---

## 6. Advertising

The Extension displays occasional in-extension advertisements for third-party services (serpmax.ru, vibes.su). These are static links — no tracking pixels, no ad networks, no user profiling. Clicking an ad opens the advertiser's website in a new tab. The advertiser's own privacy policy applies once you visit their site.

---

## 7. Permissions Justification

| Permission | Why it is needed |
|------------|-----------------|
| `proxy` | Required to route browser traffic through the proxy server |
| `storage` | Required to save your settings locally |
| `webRequest` | Required to handle proxy authentication |
| `privacy` | Required to enable WebRTC leak protection |
| `alarms` | Required to monitor connection health in the background |
| `notifications` | Required to notify you if the connection drops unexpectedly |
| `<all_urls>` | Required for the proxy to intercept and route all browser requests |

---

## 8. Children's Privacy

The Extension is not directed at children under the age of 13. We do not knowingly collect any information from children.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected by updating the "Last updated" date at the top of this page. Continued use of the Extension after changes constitutes acceptance of the updated policy.

---

## 10. Contact

If you have any questions about this Privacy Policy, please contact us at:

**Email:** zmega.tmz@gmail.com 
---

*This privacy policy applies to the zMEGA VPN browser extension for Chrome, Firefox, Edge, and Opera.*
