# A Community Driven API Lifecycle

## Kin Lane - @kinlane - 6 May 2015

All his talks are on Github talks.kinlane.com

Has spent the last 5 years studying APIs. Although a developer he has spent more time focusing on the business of APIs.

In 2010 Kin started API Evangelist. Used APIs instead of Wordpress. As he tracked more stuff he added more endpoints to his API. Then he created a news endpoint to curate the API news he was finding.

APIs come and go, so then linkrot was added as an endpoint. Took screenshots of sites incase they went offline or were deprecated. Then needed to manage images/icons as again added another endpoint.

Worked with 3scale to open up his API and get the advantages of an API management tool.

Ended up with a very messy backend, messy MySQL DB. Ended up with an architecture nightmare. If he rebooted one API they all rebooted.

Then he found Swagger. Moved to defining his APIs in Swagger. Swagger is not the docs, Swagger UI is the docs. Swagger is a definition format. From this APIs.json came about. A machine readable index of an API. Came out of a Government initiative to make services discoverable.

Used APIs.json to form a collection of all the APIs he was consumer as well as the ones he was authoring. With Swagger and APIs.json Kin started to add order to his stack.

Then along came Docker. Started to think how could he build independent API Stacks. Sort of Microservices. Kin feels Microservices are very personal to each company or individual.

Created the new Kin Lane Master Stack with Docker. Old stack still running, but plan to fully migrate to this new Next Gen Stack.

Now stack agnostic. Can fire up in AWS, Google or Azure. Strong tie to Github, using Github pages a lot.

Everything sits in a repo, the docs, pages, APIs.json, the backups, the table structures. Everything is inside a single repo!

APIs.json is becoming the manifest file to all his work.

API Science for monitoring. Also working with Runscope, and talking to SmartBear. Using his API as a gateway for providers to provide tooling to Kin.

Then created Postman collections and linked those in APIs.json. Not just machine readable, but also runs a script that creates a nice UI for human readable.

API CodeGen can read an APIs.json and produce and SKD in 7 programming languages.

Now APIs.json has evolved not longer just meta data or tagging of an API, but also exposing documentation, availability data (uptime), licensing, pricing models, and other information to provide an informed decisions on the choice of API. All of which is both machine and human readable.

Transcends technical API discovery and enters into the business domain.
