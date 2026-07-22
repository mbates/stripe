[**@bates-solutions/stripe API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / StripeClientConfig

# Interface: StripeClientConfig

Defined in: [core/client.ts:16](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/client.ts#L16)

Configuration options for the Stripe client

## Properties

### apiKey

> **apiKey**: `string`

Defined in: [core/client.ts:20](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/client.ts#L20)

Stripe secret API key (e.g. `sk_test_…` or `sk_live_…`)

***

### apiVersion?

> `optional` **apiVersion?**: `string`

Defined in: [core/client.ts:26](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/client.ts#L26)

Pin a specific Stripe API version. Omit to use the version configured on
your Stripe account.

***

### maxNetworkRetries?

> `optional` **maxNetworkRetries?**: `number`

Defined in: [core/client.ts:32](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/client.ts#L32)

Number of times the Stripe SDK retries failed requests.

#### Default

```ts
1
```
