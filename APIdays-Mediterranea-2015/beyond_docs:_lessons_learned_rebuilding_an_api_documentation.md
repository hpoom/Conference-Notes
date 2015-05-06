# Beyond Docs: Lessons learned rebuilding an API documentation

## Yann Irbah - @yannirbah - 6 May 2015

Yann is an evangelist at Paymill

Has been working on wrwriting the new docs for Paymill and will share this story today.

Developers are a difficult crowd. Working for a company that offers Dev Tools can be hard. Devs can smell bulls@%t. Developers also like fancy stuff.

Documentation is to show the way to the user. Show them how to consume your product

Documentation is a marketing tool to developers. Good docs means less developer pain.

Using example of Twitter Fabric as a good example of docs. Also the Facebook developer pages as another good example. Each with different purposes, but good examples.

Documentation has to be easy to maintain by the team, otherwise the docs will not get updated and will become stale.

Open source your docs, then people outside your organisation can do Pull Requests on your docs. Those that find bugs in your docs can raise GitHub issues.

Pick the right tool. Lots to choose from like Swagger, RAML, API Blueprint etc. None of them are magic bullets. All are good tools.

Paymill choose DocPad (SSG) to host their static pages docs.

Their documentation process is all automated. When new content is pushed on git a webhook runs and trigger a regeneration of the docs.

Building documentation is not a simple task.

