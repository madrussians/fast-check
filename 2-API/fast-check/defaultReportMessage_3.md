[Home](/) &gt; [fast-check](../fast-check.md) &gt; [defaultReportMessage](defaultReportMessage_3.md)

## defaultReportMessage() function

Format output of `fc.check` using the default error reporting of `fc.assert`

Produce a string containing the formated error in case of failed run, undefined otherwise.

<b>Signature:</b>

```typescript
declare function defaultReportMessage<Ts>(out: RunDetails<Ts>): string | undefined;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  out | <code>RunDetails&lt;Ts&gt;</code> |  |

<b>Returns:</b>

`string | undefined`

