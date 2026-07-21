[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookVerificationResult

# Interface: WebhookVerificationResult

Defined in: [server/types.ts:71](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L71)

Result of webhook signature verification.

## Properties

### error?

> `optional` **error?**: `string`

Defined in: [server/types.ts:75](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L75)

Error message if invalid

***

### valid

> **valid**: `boolean`

Defined in: [server/types.ts:73](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L73)

Whether the signature is valid
