---
id: data-store.identifier.getlatestclaimvalue
title: Identifier.getLatestClaimValue() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## Identifier.getLatestClaimValue() method

Convenience method

const name = await identifier.getLatestClaimValue( {<!-- -->type: 'name'<!-- -->}<!-- -->)

<b>Signature:</b>

```typescript
getLatestClaimValue(dbConnection: Promise<Connection>, where: {
        type: string;
    }): Promise<string | null | undefined>;
```

## Parameters

| Parameter    | Type                      | Description |
| ------------ | ------------------------- | ----------- |
| dbConnection | Promise&lt;Connection&gt; |             |
| where        | { type: string; }         |             |

<b>Returns:</b>

Promise&lt;string \| null \| undefined&gt;
