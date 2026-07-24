[**@bates-solutions/stripe API Reference v1.0.2**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / getInvoiceId

# Function: getInvoiceId()

> **getInvoiceId**(`event`): `string` \| `undefined`

Defined in: [server/webhook.ts:362](https://github.com/mbates/stripe/blob/dfaed1936ced38c35148bf61aab578023de18d7b/src/server/webhook.ts#L362)

Extract the Invoice ID from a webhook event, when present.

Works on `invoice.*` events (the object is the invoice) and on objects that
reference an invoice (e.g. Checkout Sessions, PaymentIntents).

## Parameters

### event

`Event`

## Returns

`string` \| `undefined`
