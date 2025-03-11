# Subscriptions: FAQ

This article intends to answer some of the most frequently asked questions about Subscriptions.

### Can I have more than one subscription in my store?

The number of subscriptions is unlimited, both for your store and for your customer. It means that there is not a limited number of subscriptions to be sold by your store or purchased by your customer. However, it is important to be aware of the conditions that apply to subscriptions.  

### Can my customer buy via subscription and pick up from stores or other pickup points?

Yes, read our article [Pickup points for Subscriptions (Beta)](https://help.vtex.com/en/tutorial/pickup-points-for-subscription-orders-beta--csIqB6iBh4QNIFdEj0nVv) for more information.

### Can my customer add more than one address to their subscription?

It is not possible to add more than one address to the same subscription.  

### What is the delivery estimate, and what are the shipping rules?

The delivery estimate and shipping rules are based on the applicable delivery policies for each cycle.  

### Can my customer pay for their subscription orders in installments?

Yes, as long as the store is configured to allow installments for subscriptions orders. This is done through the [Edit subscriptions settings](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#post-/api/rns/settings) endpoint, marking the `isMultipleInstallmentsEnabledOnCreation` and `isMultipleInstallmentsEnabledOnUpdate` fields as `true`.

### What happens if my customer's card has been canceled?

The system will not generate the subscription due to the lack of payment.

### Can my customers request a scheduled delivery for their subscription orders?

Currently, it is not possible to request scheduled deliveries for subscription orders. We have made this decision to prevent your customers from being affected if your store's logistic configuration changes.
However, your customer can create a new subscription with a future delivery date of their choosing.

### How can I cancel, skip or pause my customer's subscription order?

Currently, it is not possible to change your customer's subscription orders through VTEX's Admin. It is only possible to pause, cancel or skip a subscription order accessing your client's account through the Call center, in the subscriptions dashboard, or via our [APIs](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#overview).

### Is it possible to add items from sellers or marketplaces to a subscription order?

Subscriptions can be created with items from the store, VTEX sellers, and white label sellers (franchise account).

### If the retailer creates a minimum value rule, will it affect subscriptions?

Yes, if the subscription order value is below the threshold defined by the _Minimum total value in cart_ setting. Note that our subscription module does not support cycles/orders with a total value of $0.

### If the price of an SKU changes, will it affect my customer's subscription?

Yes, the price charged for the subscription is based on the price configured for each SKU. The customer's subscription does not follow the price conditions of the first subscription order. The scheduled order will have the same products as the original order, but the system will calculate the price based on the next cycle's valid price.

### What time are subscription orders generated?

Subscription orders are created between 6:00 and 7:00 am in Brazil zone (GMT-3).

### Does the functionality Subscriptions work with Seller Portal?

No, Subscriptions does not work with [Seller Portal](https://help.vtex.com/en/tutorial/how-to-set-up-your-store-on-seller-portal).

### How does it work to create subscriptions from original orders that have SKUs with attachments?

By default, stores do not create subscription orders associating SKU [attachments](https://help.vtex.com/en/tutorial/o-que-e-um-anexo--aGICk0RVbqKg6GYmQcWUm) with the original order, i.e., attachments are not considered in recurring orders. However, you can enable this setting for your store, but it can only be done via API using the [Edit subscriptions settings](https://developers.vtex.com/docs/api-reference/subscriptions-api-v3#post-/api/rns/settings) endpoint. Learn more in [How to keep attachments from original orders in subscriptions](https://developers.vtex.com/docs/guides/how-to-keep-attachments-from-original-orders-in-subscriptions).
