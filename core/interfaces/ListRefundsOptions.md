[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / ListRefundsOptions

# Interface: ListRefundsOptions

Defined in: [core/services/refunds.service.ts:39](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/refunds.service.ts#L39)

Options for listing refunds

## Properties

### chargeId?

> `optional` **chargeId?**: `string`

Defined in: [core/services/refunds.service.ts:44](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/refunds.service.ts#L44)

Only return refunds for this charge

***

### limit?

> `optional` **limit?**: `number`

Defined in: [core/services/refunds.service.ts:40](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/refunds.service.ts#L40)

***

### paymentIntentId?

> `optional` **paymentIntentId?**: `string`

Defined in: [core/services/refunds.service.ts:42](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/refunds.service.ts#L42)

Only return refunds for this PaymentIntent

***

### startingAfter?

> `optional` **startingAfter?**: `string`

Defined in: [core/services/refunds.service.ts:46](https://github.com/mbates/stripe/blob/df8c0d46cab5828e5e46677223aaddbd83f760ad/src/core/services/refunds.service.ts#L46)

Cursor: return records after this refund ID
