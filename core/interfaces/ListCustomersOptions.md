[**@bates-solutions/stripe API Reference v1.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / ListCustomersOptions

# Interface: ListCustomersOptions

Defined in: [core/services/customers.service.ts:51](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/services/customers.service.ts#L51)

Options for listing customers

## Properties

### email?

> `optional` **email?**: `string`

Defined in: [core/services/customers.service.ts:54](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/services/customers.service.ts#L54)

Filter by exact email address

***

### limit?

> `optional` **limit?**: `number`

Defined in: [core/services/customers.service.ts:52](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/services/customers.service.ts#L52)

***

### startingAfter?

> `optional` **startingAfter?**: `string`

Defined in: [core/services/customers.service.ts:56](https://github.com/mbates/stripe/blob/5209173c3c3431432a88ab1fd7f64106c9d10472/src/core/services/customers.service.ts#L56)

Cursor: return records after this customer ID
