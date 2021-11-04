<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@stripe/firestore-stripe-payments](./firestore-stripe-payments.md) &gt; [CreateCheckoutSessionOptions](./firestore-stripe-payments.createcheckoutsessionoptions.md)

## CreateCheckoutSessionOptions interface

Optional settings for the [createCheckoutSession()](./firestore-stripe-payments.createcheckoutsession.md) function.

<b>Signature:</b>

```typescript
export interface CreateCheckoutSessionOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [timeoutMillis?](./firestore-stripe-payments.createcheckoutsessionoptions.timeoutmillis.md) | number | <i>(Optional)</i> Time to wait (in milliseconds) until the session is created and acknowledged by Stripe. If not specified, defaults to [CREATE\_SESSION\_TIMEOUT\_MILLIS](./firestore-stripe-payments.create_session_timeout_millis.md)<!-- -->. |
