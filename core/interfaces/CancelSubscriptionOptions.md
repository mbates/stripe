[**@bates-solutions/stripe API Reference v1.0.2**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CancelSubscriptionOptions

# Interface: CancelSubscriptionOptions

Defined in: [core/services/subscriptions.service.ts:99](https://github.com/mbates/stripe/blob/dfaed1936ced38c35148bf61aab578023de18d7b/src/core/services/subscriptions.service.ts#L99)

Options for cancelling a subscription

## Properties

### atPeriodEnd?

> `optional` **atPeriodEnd?**: `boolean`

Defined in: [core/services/subscriptions.service.ts:104](https://github.com/mbates/stripe/blob/dfaed1936ced38c35148bf61aab578023de18d7b/src/core/services/subscriptions.service.ts#L104)

Cancel at the end of the current period instead of immediately.

#### Default

```ts
false
```
