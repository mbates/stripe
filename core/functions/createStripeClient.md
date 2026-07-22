[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / createStripeClient

# Function: createStripeClient()

> **createStripeClient**(`config`): [`StripeClient`](../classes/StripeClient.md)

Defined in: [core/client.ts:127](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/client.ts#L127)

Create a new Stripe client instance.

## Parameters

### config

[`StripeClientConfig`](../interfaces/StripeClientConfig.md)

Client configuration

## Returns

[`StripeClient`](../classes/StripeClient.md)

Configured Stripe client

## Example

```typescript
const stripe = createStripeClient({
  apiKey: process.env.STRIPE_SECRET_KEY!,
});
```
