# Ways-to-auth
Aggregated list of different ways to authenticate

## Unsorted

This list can be sorted later on.

- Basic auth
- OAuth 1
- OAuth 1.1a
- OAuth2
- OpenID Connect
- SAML
- SAML 2.0

---

#### General structure

```markdown
## Type

### Category

#### Method (way to authenticate)

- Description
- Activity diagram

##### Potential variant
```

---

## Primary

### Basic Auth

Using the classical username & password.

Activity diagram.

### OAuth2

## Secondary / MFA

- Sms
- Microsoft authenticator
- Google authenticator
- Authy

### OTP

- HOTP
- TOTP
- OTP (SMS)

###### Software tokens

###### Hardware tokens

### U2F

### Tokens

# Undefined

- Sign in via email by receiving a sentence and type it down (Vercel does this)
- Using a token as your identity
- SSH & PGP
- Using your other device as confirmation by sending a key to that device and require you to input the delivered key (signing in to iCloud for example)
- Relying on platforms such as Github, Google, Facebook to perform the authentication
- Using your phone as two-step-verification via sms  
- Using your phone as two-step-verification via apps like Google / Microsoft authenticator
- Email / username & password
- Hardwares like Yubikey

