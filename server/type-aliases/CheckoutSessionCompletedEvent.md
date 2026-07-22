[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / CheckoutSessionCompletedEvent

# Type Alias: CheckoutSessionCompletedEvent

> **CheckoutSessionCompletedEvent** = `Extract`\<`Stripe.Event`, \{ `type`: `"checkout.session.completed"`; \}\>

Defined in: [server/types.ts:73](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/server/types.ts#L73)

Convenience aliases for the subscription-lifecycle events, each narrowed to
its concrete `data.object` type. Handy for typing standalone handler
functions without re-deriving the `Extract<…>`.
