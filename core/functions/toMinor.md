[**@bates-solutions/stripe API Reference v0.0.0**](../../README.md)

***

[@bates-solutions/stripe API Reference](../../README.md) / [core](../README.md) / toMinor

# Function: toMinor()

> **toMinor**(`amount`, `currency?`): `number`

Defined in: [core/utils.ts:40](https://github.com/mbates/stripe/blob/698c522e9256b4bd044155c04123d6d3b30db7e4/src/core/utils.ts#L40)

Convert a major-unit amount to the smallest currency unit Stripe expects.

## Parameters

### amount

`number`

Major-unit amount (e.g. 10.50 dollars)

### currency?

[`CurrencyCode`](../type-aliases/CurrencyCode.md) = `'usd'`

Currency code (default: usd)

## Returns

`number`

Amount in the smallest currency unit (e.g. 1050 for $10.50)

## Example

```typescript
toMinor(10.50) // 1050
toMinor(1000, 'jpy') // 1000 (JPY has no decimal places)
```
