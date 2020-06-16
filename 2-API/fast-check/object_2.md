[Home](/) &gt; [fast-check](../fast-check.md) &gt; [object](object_2.md)

## object() function

For any objects following the constraints defined by `settings`

You may use [sample()](sample_1.md) to preview the values that will be generated

<b>Signature:</b>

```typescript
declare function object(settings: ObjectConstraints.Settings): Arbitrary<Record<string, unknown>>;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  settings | <code>ObjectConstraints.Settings</code> | Constraints to apply when building instances |

<b>Returns:</b>

`Arbitrary<Record<string, unknown>>`

#### Example

\`\`\`<!-- -->{<!-- -->} or {<!-- -->k: \[{<!-- -->}<!-- -->, 1, 2\]<!-- -->}<!-- -->\`\`\`

