[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / SubscriptionDeletedEvent

# Type Alias: SubscriptionDeletedEvent

> **SubscriptionDeletedEvent** = `Extract`\<`Stripe.Event`, \{ `type`: `"customer.subscription.deleted"`; \}\>

Defined in: [server/types.ts:76](https://github.com/mbates/stripe/blob/d05db190d1acd9c7f09c8b66474d38e19ceee172/src/server/types.ts#L76)

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
