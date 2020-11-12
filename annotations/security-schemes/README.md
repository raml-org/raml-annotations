# Security scheme annotations

## `customOauth2Settings`

### Purpose

> OAuth 2.0 allows to extend the specification with custom access token types,
  endpoint parameters, grant types or response types.
  This annotation allows you to annotate the `settings` property of OAuth 2.0
  security scheme type to inform applications about additional settings.

(see full [description](oauth-2-custom-settings.raml))

### What's included

This directory contains the following RAML `AnnotationTypeDeclaration` fragment:

- oauth-2-custom-settings.raml

and the following example:

- oauth-2-custom-settings-example.raml

### Which tools support this

- [mulesoft/api-console (v5.0.x)](https://github.com/mulesoft/api-console)

## `pkce`

### Purpose

Defines annotation that adds support for RFC 7636: Proof Key for Code Exchange.

### Which tools support this

- [mulesoft/api-console (v6.x.x)](https://github.com/mulesoft/api-console)
