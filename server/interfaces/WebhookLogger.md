[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [server](../README.md) / WebhookLogger

# Interface: WebhookLogger

Defined in: [server/middleware/lambda.ts:57](https://github.com/mbates/stripe/blob/15e917425b05c6cb89295d7a886146a00e971266/src/server/middleware/lambda.ts#L57)

Logger interface for the Lambda webhook handler.

## Properties

### error

> **error**: (`message`, `data?`) => `void`

Defined in: [server/middleware/lambda.ts:59](https://github.com/mbates/stripe/blob/15e917425b05c6cb89295d7a886146a00e971266/src/server/middleware/lambda.ts#L59)

#### Parameters

##### message

`string`

##### data?

`Record`\<`string`, `unknown`\>

#### Returns

`void`

***

### info

> **info**: (`message`, `data?`) => `void`

Defined in: [server/middleware/lambda.ts:58](https://github.com/mbates/stripe/blob/15e917425b05c6cb89295d7a886146a00e971266/src/server/middleware/lambda.ts#L58)

#### Parameters

##### message

`string`

##### data?

`Record`\<`string`, `unknown`\>

#### Returns

`void`
