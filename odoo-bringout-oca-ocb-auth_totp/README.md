# Two-Factor Authentication (TOTP)


Two-Factor Authentication (TOTP)
================================
Allows users to configure two-factor authentication on their user account
for extra security, using time-based one-time passwords (TOTP).

Once enabled, the user will need to enter a 6-digit code as provided
by their authenticator app before being granted access to the system.
All popular authenticator apps are supported.

Note: logically, two-factor prevents password-based RPC access for users
where it is enabled. In order to be able to execute RPC scripts, the user
can setup API keys to replace their main password.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-auth_totp
```

## Dependencies

- web

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 19.0
- Path: addons/auth_totp

## License

This package preserves the original LGPL-3 license.
