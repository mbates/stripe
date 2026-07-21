[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CancelSubscriptionOptions

# Interface: CancelSubscriptionOptions

Defined in: [core/services/subscriptions.service.ts:99](https://github.com/mbates/stripe/blob/15e917425b05c6cb89295d7a886146a00e971266/src/core/services/subscriptions.service.ts#L99)

Options for cancelling a subscription

## Properties

### atPeriodEnd?

> `optional` **atPeriodEnd?**: `boolean`

Defined in: [core/services/subscriptions.service.ts:104](https://github.com/mbates/stripe/blob/15e917425b05c6cb89295d7a886146a00e971266/src/core/services/subscriptions.service.ts#L104)

Cancel at the end of the current period instead of immediately.

#### Default

```ts
false
```
