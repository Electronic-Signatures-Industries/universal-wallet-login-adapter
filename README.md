# universal-wallet-login-adapter
XDV Universal Wallet Login Adapter

## Summary

Currently, XDV Universal Wallet users needs to use passphrases stored into a local database, which can be troublesome if you forget your passphrase, it might block an user for accessing is key pairs.

This adapter interface allows adding operating systems access to login infrastructure, the first API is a for WebAuthn FIDO2 CTAP2, using `HMAC-SECRET`

## References

- https://github.com/gebogebogebo/ctap-hid-fido2
- https://github.com/Yubico/libfido2

## MIT Licensed
Copyright Industrias de Firmas Electronicas SA, 2021
