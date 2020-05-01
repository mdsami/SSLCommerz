### SSLCommerz Payment Gateway Flutter package.


### Installation


In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
  sslcommerz:
```

### How to use:


```dart
import 'package:sslcommerz/sslcommerz.dart';

class MyApp extends SsLCommerz {

}
```


##### For Sandbox:
```
const test = new SSLCzPayment({
    store_id: 'testbox',
    store_passwd: 'qwerty',
    total_amount: 100,
    currency: 'BDT',
    tran_id: 'REF123',
    success_url: 'http://yoursite.com/success.php',
    fail_url: 'http://yoursite.com/fail.php',
    cancel_url: 'http://yoursite.com/cancel.php',
    shipping_method:'Courier',
    product_name:'Computer.',
    product_category:'Electronic',
    product_profile:'general',
    cus_name: 'Customer Name',
    cus_email: 'cust@email.com',
    cus_add1: 'Dhaka',
    cus_add2: 'Dhaka',
    cus_city: 'Dhaka',
    cus_state: 'Dhaka',
    cus_postcode: '1207',
    cus_country: 'Bangladesh',
    cus_phone: '01711111111',
    cus_fax: '01711111111',
    ship_name: 'Customer Name',
    ship_add1: 'Dhaka',
    ship_add2: 'Dhaka',
    ship_city: 'Dhaka',
    ship_state: 'Dhaka',
    ship_postcode: 1207,
    ship_country: 'Bangladesh',
    multi_card_name: 'mastercard',
    value_a: 'ref001_A',
    value_b: 'ref002_B',
    value_c: 'ref003_C',
    value_d: 'ref004_D'
}, false);

```
##### For Live Transaction:
```
const test = new SSLCzPayment({
    store_id: 'testbox',
    store_passwd: 'qwerty',
    total_amount: 100,
    currency: 'BDT',
    tran_id: 'REF123',
    success_url: 'http://yoursite.com/success.php',
    fail_url: 'http://yoursite.com/fail.php',
    cancel_url: 'http://yoursite.com/cancel.php',
    shipping_method:'Courier',
    product_name:'Computer.',
    product_category:'Electronic',
    product_profile:'general',
    cus_name: 'Customer Name',
    cus_email: 'cust@email.com',
    cus_add1: 'Dhaka',
    cus_add2: 'Dhaka',
    cus_city: 'Dhaka',
    cus_state: 'Dhaka',
    cus_postcode: '1207',
    cus_country: 'Bangladesh',
    cus_phone: '01711111111',
    cus_fax: '01711111111',
    ship_name: 'Customer Name',
    ship_add1: 'Dhaka',
    ship_add2: 'Dhaka',
    ship_city: 'Dhaka',
    ship_state: 'Dhaka',
    ship_postcode: 1207,
    ship_country: 'Bangladesh',
    multi_card_name: 'mastercard',
    value_a: 'ref001_A',
    value_b: 'ref002_B',
    value_c: 'ref003_C',
    value_d: 'ref004_D'
}, true);

```

Find more details in [SSLCommerz Developer's Guide](https://developer.sslcommerz.com/)