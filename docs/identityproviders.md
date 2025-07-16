# Identity Providers

Not every identity provider is susceptible to resposne forging. And even those that are may require a different level of work to obtain the private key material needed for response forging.

At the core of it, for each identity provider you want to forge a response for, the identity provider must either:

- Offer a way to export the private key used for signing.
- Offer a way to import an external private key for signing.

This document provides information on the following types of identity providers:

- Those where response forging has been tested with SAMLSmith.
- Those whose documentation shows that a it should be possible but have not been tested.
- Those whose documentation shows that it should **not** be possible to forge a SAML response.

## SAMLSmith Tested
