---
layout: docs
title: 'AddRequest'
---

```ts
export interface AddRequest {
  type: 'add';
  trans: DBCoreTransaction;
  values: any[];
  keys?: Key[];
  wantResults?: boolean;
}
```
