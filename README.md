# No longer required. Use official SecureBlue

## InsecureBlue

Unofficial [SecureBlue](https://github.com/secureblue/secureblue) kinoite-asus-nvidia-userns-hardened with hardened malloc disabled
(Not really insecure)

## Verification

These images are signed with [Sigstore](https://www.sigstore.dev/)'s [cosign](https://github.com/sigstore/cosign). You can verify the signature by downloading the `cosign.pub` file from this repo and running the following command:

```bash
cosign verify --key cosign.pub ghcr.io/blue-build/legacy-template
```
