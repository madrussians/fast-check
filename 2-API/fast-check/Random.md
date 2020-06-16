[Home](/) &gt; [fast-check](../fast-check.md) &gt; [Random](Random.md)

## Random class

<b>Signature:</b>

```typescript
export declare class Random 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [clone()](Random.md#clone) | Clone the random number generator |
|  [next(bits)](Random.md#next) | Generate an integer having <code>bits</code> random bits |
|  [nextBigInt(min, max)](Random.md#nextbigint) | Generate a random any between min (included) and max (included) |
|  [nextBoolean()](Random.md#nextboolean) | Generate a random boolean |
|  [nextDouble()](Random.md#nextdouble) | Generate a random floating point number between 0.0 (included) and 1.0 (excluded) |
|  [nextInt()](Random.md#nextint) | Generate a random integer (32 bits) |
|  [nextInt(min, max)](Random.md#nextint) | Generate a random integer between min (included) and max (included) |

### clone

Clone the random number generator

<b>Signature:</b>

```typescript
clone(): Random;
```
<b>Returns:</b>

`Random`

### next

Generate an integer having `bits` random bits

<b>Signature:</b>

```typescript
next(bits: number): number;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  bits | <code>number</code> | Number of bits to generate |

<b>Returns:</b>

`number`

### nextBigInt

Generate a random any between min (included) and max (included)

<b>Signature:</b>

```typescript
nextBigInt(min: any, max: any): any;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  min | <code>any</code> | Minimal any value |
|  max | <code>any</code> | Maximal any value |

<b>Returns:</b>

`any`

### nextBoolean

Generate a random boolean

<b>Signature:</b>

```typescript
nextBoolean(): boolean;
```
<b>Returns:</b>

`boolean`

### nextDouble

Generate a random floating point number between 0.0 (included) and 1.0 (excluded)

<b>Signature:</b>

```typescript
nextDouble(): number;
```
<b>Returns:</b>

`number`

### nextInt

Generate a random integer (32 bits)

<b>Signature:</b>

```typescript
nextInt(): number;
```
<b>Returns:</b>

`number`

### nextInt

Generate a random integer between min (included) and max (included)

<b>Signature:</b>

```typescript
nextInt(min: number, max: number): number;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  min | <code>number</code> | Minimal integer value |
|  max | <code>number</code> | Maximal integer value |

<b>Returns:</b>

`number`

