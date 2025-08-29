# Patch: Remove App Store Download Links

## Module: auth_totp

### Description
This patch removes mobile app store download links (Apple App Store and Google Play Store) from the Two-Factor Authentication (TOTP) setup wizard.

### Files Modified
- `auth_totp/wizard/auth_totp_wizard_views.xml`

### Changes Made

#### File: auth_totp/wizard/auth_totp_wizard_views.xml
**Lines removed: 22-29**

Removed the following section containing mobile app store download links:
```xml
<div class="d-block d-md-none">
    <a href="https://play.google.com/store/search?q=authenticator&amp;c=apps" class="mx-2" target="blank">
        <img alt="On Google Play" style="width: 24px;" src="/base_setup/static/src/img/logo_google_play.png"/>
    </a>
    <a href="http://appstore.com/2fa" class="mx-2" target="blank">
        <img alt="On Apple Store" style="width: 24px;" src="/base_setup/static/src/img/logo_apple_store.png"/>
    </a>
</div>
```

### Impact
- Users will no longer see direct download links to mobile app stores when setting up 2FA
- The instruction text for installing authenticator apps remains intact
- The QR code and manual key entry functionality is unaffected
- All other TOTP wizard functionality remains unchanged

### Reason
Removal of proprietary mobile app store references to maintain a more neutral, open-source focused user experience.

---
**Patch Created:** 2025-08-27  
**Applied By:** Claude Code Assistant