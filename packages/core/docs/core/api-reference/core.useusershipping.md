<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@vue-storefront/core](./core.md) &gt; [UseUserShipping](./core.useusershipping.md)

## UseUserShipping interface

<b>Signature:</b>

```typescript
export interface UseUserShipping<USER_SHIPPING, USER_SHIPPING_ITEM> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [addAddress](./core.useusershipping.addaddress.md) | (params: { address: USER\_SHIPPING\_ITEM; customQuery?: [CustomQuery](./core.customquery.md)<!-- -->; }) =&gt; Promise&lt;void&gt; |  |
|  [deleteAddress](./core.useusershipping.deleteaddress.md) | (params: { address: USER\_SHIPPING\_ITEM; customQuery?: [CustomQuery](./core.customquery.md)<!-- -->; }) =&gt; Promise&lt;void&gt; |  |
|  [error](./core.useusershipping.error.md) | [ComputedProperty](./core.computedproperty.md)<!-- -->&lt;[UseUserShippingErrors](./core.useusershippingerrors.md)<!-- -->&gt; |  |
|  [load](./core.useusershipping.load.md) | () =&gt; Promise&lt;void&gt; |  |
|  [loading](./core.useusershipping.loading.md) | [ComputedProperty](./core.computedproperty.md)<!-- -->&lt;boolean&gt; |  |
|  [setDefaultAddress](./core.useusershipping.setdefaultaddress.md) | (params: { address: USER\_SHIPPING\_ITEM; customQuery?: [CustomQuery](./core.customquery.md)<!-- -->; }) =&gt; Promise&lt;void&gt; |  |
|  [shipping](./core.useusershipping.shipping.md) | [ComputedProperty](./core.computedproperty.md)<!-- -->&lt;USER\_SHIPPING&gt; |  |
|  [updateAddress](./core.useusershipping.updateaddress.md) | (params: { address: USER\_SHIPPING\_ITEM; customQuery?: [CustomQuery](./core.customquery.md)<!-- -->; }) =&gt; Promise&lt;void&gt; |  |
