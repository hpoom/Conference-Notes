# Challenges of Building a Distributed API

## Sylvain Utard - @sylvainutard - 6 May 2015

Talks about how to build and API to meet the needs of users all around the world.

Works for Algolia. Company started as a mobile offline SDK.
https://www.algolia.com/

Looks like, but I could be wrong, a sort of hosted Elastic Search solution.

When speeding things up latency can cause you a lot of issues. Therefor you need to be close to the user. Distributed CDN approach.

Infrastructure costs vary a lot around the world.

Most providers do not obey the TTL on DNS records. So TTL and DNS is not enough. The solution is to have a fallback built into the API, so when DNS does not work the API can route traffic to healthy servers. Sometimes these fallbacks are event to other regions.

There are speed differences between different domain extensions. For example .net is not same speed as .io, it is all related to how many master DNS servers there are for this data.

_Read more into this!!!_