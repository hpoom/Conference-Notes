# JSON API: your anti-bikeshedding weapon

## Steve Klabnik - @steveklabnik - 6 May 2015

Project Steve has been working on for a couple of years now.

###Theory###

We as programmers like to waste time discussing irrelevant details. Rails is fast because you don't need to waste time bike shedding on these details.

In the rails world database design is coupled to REST routes. This is bad, coupling is bad and we should be decoupling things where possible.

With spoken languages some statements are easier to communicate in some languages over others. The same is true for programming languages and API interfaces.

One thing that would be really hard would be if we each spoke a different language. This would make it impossible to converse, but this is the way we build APIs today. Each API we talk to has a custom payload message format. It is it's own language and the barrier to entry is high!

To overcome these issues we have standards like W3C etc. These standards are good because they encourage standardisation.

### History ###

We meet these idols of the web. We believe that they know everything about programming. This is not the case. They might be experts in some areas, but nobody can know everything. You need to combine minds to get out good ideas.

Yehuda Katz wanted Ember to be agnostic of a Rails backend. So they went with json:api to make it agnostic of technology on the backend. Ember today supports json:api.

[Parkinson's Law of Triviality](https://en.wikipedia.org/wiki/Parkinson%27s_law_of_triviality)

### Practice ###

Many companies are using this in production.

Releasing version 1.0 of the spec on 21st of May!

They will not break backwards compatibility after this time.

json:api encourages but does not enforce hypermedia in APIs


