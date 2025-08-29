# 2FA Invite mail


2FA Invite mail
===============
Allow the users to invite another user to use Two-Factor authentication
by sending an email to the target user. This email redirect them to :
- the users security settings if the user is internal.
- the portal security settings page if the user is not internal. 
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-auth_totp_mail
```

## Dependencies

This addon depends on:
- auth_totp
- mail

## Manifest Information

- **Name**: 2FA Invite mail
- **Version**: N/A
- **Category**: Extra Tools
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `auth_totp_mail`.

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
