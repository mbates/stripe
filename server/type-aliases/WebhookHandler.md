[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookHandler

# Type Alias: WebhookHandler\<E\>

> **WebhookHandler**\<`E`\> = (`event`) => `void` \| `Promise`\<`void`\>

Defined in: [server/types.ts:19](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/server/types.ts#L19)

Handler for a webhook event of a specific type.

## Type Parameters

### E

`E` *extends* [`WebhookEvent`](WebhookEvent.md) = [`WebhookEvent`](WebhookEvent.md)

## Parameters

### event

`E`

## Returns

`void` \| `Promise`\<`void`\>
