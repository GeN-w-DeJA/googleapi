# OAuth 1.0a and the Google OAuth Client Library for Java#

[OAuth 1.0](http://tools.ietf.org/html/rfc5849) is a standard specification for
allowing end users to securely authorize a client application to access protected
server-side resources.

## Important notices

The OAuth 1.0a support provided by the Google OAuth Client Library for Java is `@Beta`.

Do not use OAuth 1.0 to access
Google APIs, because Google has deprecated its support for OAuth 1.0 in favor
of OAuth 2.0. If you currently have an app that accesses Google APIs using
OAuth 1.0, see
[Migrating from OAuth 1.0 to OAuth 2.0](https://developers.google.com/accounts/docs/OAuth_ref#migration).

## Using OAuth 1.0

The Google OAuth Client Library for Java supports two types of signature methods
for OAuth 1.0a (`@Beta`), which we provide foruse with non-Google services:

  * HMAC-SHA1 ([`OAuthHmacSigner`](https://googleapis.dev/java/google-oauth-client/latest/com/google/api/client/auth/oauth/OAuthHmacSigner.html))
  * RSA-SHA1 ([`OAuthRsaSigner`](https://googleapis.dev/java/google-oauth-client/latest/com/google/api/client/auth/oauth/OAuthRsaSigner.html))

For details, see the
[Javadoc for the OAuth 1.0 package](https://googleapis.dev/java/google-oauth-client/latest/com/google/api/client/auth/oauth/package-summary.html).
