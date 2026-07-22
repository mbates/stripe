[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / SubscriptionCreatedEvent

# Type Alias: SubscriptionCreatedEvent

> **SubscriptionCreatedEvent** = `Extract`\<`Stripe.Event`, \{ `type`: `"customer.subscription.created"`; \}\>

Defined in: [server/types.ts:74](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/server/types.ts#L74)

@bates-solutions/stripe/server

Server utilities for handling Stripe webhooks.

## Example

```typescript
// Next.js App Router
import { createNextWebhookHandler } from '@bates-solutions/stripe/server';

export const POST = createNextWebhookHandler({
  signingSecret: process.env.STRIPE_WEBHOOK_SECRET!,
  handlers: {
    'payment_intent.succeeded': async (event) => {
      console.log('Paid:', event.data.object.id);
    },
  },
});
```
