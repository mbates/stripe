[**@bates-solutions/stripe API Reference v1.0.2**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / PaginationOptions

# Interface: PaginationOptions

Defined in: [core/types/index.ts:20](https://github.com/mbates/stripe/blob/dfaed1936ced38c35148bf61aab578023de18d7b/src/core/types/index.ts#L20)

Common cursor pagination options

## Properties

### limit?

> `optional` **limit?**: `number`

Defined in: [core/types/index.ts:22](https://github.com/mbates/stripe/blob/dfaed1936ced38c35148bf61aab578023de18d7b/src/core/types/index.ts#L22)

Maximum number of records to return

***

### startingAfter?

> `optional` **startingAfter?**: `string`

Defined in: [core/types/index.ts:24](https://github.com/mbates/stripe/blob/dfaed1936ced38c35148bf61aab578023de18d7b/src/core/types/index.ts#L24)

Cursor: return records after this object ID (`starting_after`)
