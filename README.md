This aims to be a repository of
[OpenSearch](http://www.opensearch.org/Specifications/OpenSearch/1.1)
descriptions of as many websites as possible.
As awesome as the [bangs](https://duckduckgo.com/bang.html) of DuckDuckGo are,
they always require a full roundtrip to duckduckgo.com including a SSL
handshake.

I don't get the reason why my browser, which can already does everything and
the kitchensink, shouldn't do this right away.

On the other hand it should be easy to get as many predefined search engines
(or as many as one wants) into a freshly installed browser (profile).
Luckily Firefox makes this easy, just copy the OpenSearch XML files to
`/usr/lib/firefox/browser/searchplugins` and you are all set.
(If you know instructions for Chrome, please document it and open a pull
request)

This is where this repository comes into play.

# Contributing

As this project tries to be as privacy friendly as possible some here is some
guidance:

* Use SSL whenever possible
* mark non-SSL engines in the filename and description
* use include the favicons/images inline
* Document if your XML is based on an official one (from the website itself)
* Use the long version for `Url` for better extensibility
* XML namespaces

# TODO

* Is it a good idea to add a `rel="self"` link? Probably not, people can just
  update the repository
* Autogeneration of engines with multiple languages (Wikipedia)
