# Test plan

## 1. Test items
**Crown-chop** - web application for selling different products and provide to user convenient way to overview entire amount of clothes, which shop provide to customer.

Web application was developed with React library, which allows to create web application, written in JS or TS.

## 2. Risk Issues
There are some risks due to using 3d party services, like Firebase(Auth, Cloud Store).

## 3. Featured to be tested
The main features will be tested: Authentication, Cart management, Payment.

## 4. Test approaches
App testing will be performed manually. App mostly use Firebase to handle back-end task(like Auth, Products DB) and use server to handle Stripe payment.

## 5. Pass/Fail criteria.
All result will be provided with content table. Only fully equality will be treated as passed test otherwise test will be treated as failed.

## 6. Conclusion
This requirements allow test web app, ensure functionally stable and correctness, which may help in future development.