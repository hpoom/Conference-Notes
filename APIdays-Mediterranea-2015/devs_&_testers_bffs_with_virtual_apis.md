# Devs & Testers, BFFs with Virtual APIs 

## Paul Bruce - @paulsbruce - 6 May 2015

From SmartBear http://smartbear.com/

Paul see's APIs like environmental concepts.
Reuse, Reduce, Recycle

But APIs come with a lot of baggage. The APIs need to be well documented.
Swagger is a good tool for this.

When you have a developer with no internet (on a plane, in a country with flaky internet), you need to offer them tools to aid their development.

REST is like a zelda dungeon without a map and a compass. 

Good multitask people are hard to find. There should be a separation of concern between the person producing an API and those outside testing that API.

It is important to have separation when it comes to testing. "Don't test the code you write, get somebody else to do it."

By separating out the build to different people, you play to peoples strengths and get a better solution for the business. QA's have a role and Developers have a role. They are equally important world.

Paul talks about QA's writing tests and doing documentation. (although at times both QAs and Devs document).

Dev says to a QA "You broke my code". The QA did not break your code, they found the bugs you coded and you should be appreciative of this feedback not challenging.

What I called Fake APIs, the industry refers to as Virtual APIs. Virtual APIs can stand in as a tool for people to test their APIs.

Comparison of Virtual APIs to Mock APIs. Also these can be used to diagnose things quicker. We can performance test our code because we are consuming a Virtual API which is fast and does not cause us performance issues.

_Start with a swagger spec, then host a virtual API off that spec for consumers to start building against with fake data hosted from a Virtual API. Later you can make it a real API that ties to your business._

This enables people to work independently. Gives us something to test against. Gives consumers something to build against and start feeding back on what they think.

