{% docs payment_method %}
    
One of the following values: 

| status         | definition                                                                      |
|----------------|---------------------------------------------------------------------------------|
| bank_transfer  | Making a transfer from the bank, using the money you have there to the seller   |
| coupon         | Using a coupon, like a discount, to pay the order made                          |
| gift_card      | Using a gift card, to pay the order                                             |
| credit_card    | Using credit card to make the payment                                           |
| debit_card     | Using debit card to make the payment                                            |

{% enddocs %}

{% docs payment_status %}
    
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| success        | The payment was a success, being made correctly  |
| fail           | The payment failed at some point                 |

{% enddocs %}