# espanso-config

This is a repo for a few of my [espanso](espanso.org) configs. 

## autofill.yml

Enables you to "autofill" a username, password, and TOTP anywhere you can type with espanso. It relies on the [Bitwarden Vault Management API](https://bitwarden.com/help/vault-management-api/), but can be easily modified to work with something else.

Example usage:
```
u(github) # will inject the username for github
p(Anki App) # will inject the password for Anki App
t(docker hub) # will inject the TOTP for docker hub
```