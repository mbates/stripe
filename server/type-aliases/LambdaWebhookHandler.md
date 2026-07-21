[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / LambdaWebhookHandler

# Type Alias: LambdaWebhookHandler

> **LambdaWebhookHandler** = (`event`, `context`) => `void` \| `Promise`\<`void`\>

Defined in: [server/middleware/lambda.ts:42](https://github.com/mbates/stripe/blob/d05db190d1acd9c7f09c8b66474d38e19ceee172/src/server/middleware/lambda.ts#L42)

Handler for a Lambda webhook event.

## Parameters

### event

[`WebhookEvent`](WebhookEvent.md)

### context

[`WebhookEventContext`](../interfaces/WebhookEventContext.md)

## Returns

`void` \| `Promise`\<`void`\>
