[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / CheckoutLineItem

# Interface: CheckoutLineItem

Defined in: [core/services/checkout.service.ts:14](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/checkout.service.ts#L14)

A line item for a Checkout Session (references an existing Price).

## Properties

### price

> **price**: `string`

Defined in: [core/services/checkout.service.ts:16](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/checkout.service.ts#L16)

Price ID (e.g. `price_…`)

***

### quantity?

> `optional` **quantity?**: `number`

Defined in: [core/services/checkout.service.ts:18](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/checkout.service.ts#L18)

Quantity (default 1)
