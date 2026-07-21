[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / ParsedWebhookRequest

# Interface: ParsedWebhookRequest

Defined in: [server/types.ts:81](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L81)

A parsed and verified webhook request.

## Properties

### event

> **event**: `Event`

Defined in: [server/types.ts:87](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L87)

The parsed event

***

### rawBody

> **rawBody**: `string`

Defined in: [server/types.ts:83](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L83)

The raw request body

***

### signature

> **signature**: `string`

Defined in: [server/types.ts:85](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L85)

The signature from the `stripe-signature` header
