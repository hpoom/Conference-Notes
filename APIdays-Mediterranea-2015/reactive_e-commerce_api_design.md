# Reactive e-commerce API design

## Oleg Ilyenko - @easyangel - 6 May 2015

Creator of Scaldi - Scala DI library

Is building Sphere.io which is an ecommerce API

Designing the API you need to separate the Model.

Have separate Query and Write models instead of sharing a common model.

CQRS - Command Query Responsibility Segregation

Has an example showing lines on and order. Add line item, remove line item, and another line item.

Send the changes, a lot smaller, instead of sending the whole model as it looks now. Reminds me of PATCH in REST.

http://adrianmarriott.net/logosroot/papers/LifeBeyondTxns.pdf

Atomic Transactions

[Reactive Manifesto](http://www.reactivemanifesto.org/)




