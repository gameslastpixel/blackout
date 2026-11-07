# Blackout privacy page

privacy-policy.html is a standalone page for Last Pixel Games and Blackout — Power Station. It contains no scripts, analytics, external fonts or tracking.

Publish this file through GitHub Pages, then provide its public HTTPS URL. The game currently includes the full policy locally. Its optional website link becomes available after PRIVACY_URL is set in Development/Godot/scripts/release_info.gd.

Review the policy's description of handling support correspondence and playtest material before hosting it.

The canonical text is Development/Godot/assets/legal/privacy-policy.txt. After editing it, regenerate the page from Development/Godot with

```powershell
node tools/build_privacy_page.mjs
```

Keep the in-game policy, hosted policy and Play Console Data safety answers aligned with the exact release. Revisit them when introducing billing, ads, automatic reporting or online accounts.

The policy was updated on 7 November for bundled AdMob/Billing and the proposed verifier. Confirm final hosting retention and audience details before enabling commercial services. The purchase-verifier folder contains a separate dynamic service and must not be published as part of the privacy site with credentials. GitHub Pages hosts only the policy HTML.
