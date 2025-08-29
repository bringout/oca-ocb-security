# 2FA by mail


2FA by mail
===============
Two-Factor authentication by sending a code to the user email inbox
when the 2FA using an authenticator app is not configured.
To enforce users to use a two-factor authentication by default,
and encourage users to configure their 2FA using an authenticator app.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-auth_totp_mail_enforce
```

## Dependencies

This addon depends on:
- auth_totp
- mail

## Manifest Information

- **Name**: 2FA by mail
- **Version**: N/A
- **Category**: Extra Tools
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `auth_totp_mail_enforce`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md
