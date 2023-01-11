# Public GraphQL APIs

*A collective list of public [GraphQL](https://graphql.org/) APIs. PRs are welcome :smile:*
If you are interested in GraphQL in general, check out [awesome-graphql](https://github.com/chentsulin/awesome-graphql).

## Official APIs

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| AniList | Anime and manga datum, including character, staff, and live airing data. | [Try it!](https://anilist.co/graphiql) | [Docs](https://anilist.gitbook.io/anilist-apiv2-docs/)
| Bitquery | on-chain blockchain analytics | [Try it!](https://graphql.bitquery.io) | [Docs](https://bitquery.io/blog/working-with-blockchain-data)
| Braintree | Payment platform | [Try it!](https://graphql.braintreepayments.com/explorer) | [Docs](https://graphql.braintreepayments.com/)
| Buildkite | Continuous integration and deployments | [Try it!](https://graphql.buildkite.com/) | [Docs](https://building.buildkite.com/tutorial-getting-started-with-graphql-queries-and-mutations-11211dfe5d64#.7uhjusw1q)
| Catalysis Hub | Chemical surface reaction energies and structures | [Try it!](http://api.catalysis-hub.org/graphql) | [Repo](https://github.com/SUNCAT-Center/CatalysisHubBackend)<br> [Docs](http://docs.catalysis-hub.org/en/latest/tutorials/index.html#graphql)
| Changetrip | The Chargetrip API gives you the ability to integrate smart, EV-specific routing into products built for electric car drivers. | [Try it!](https://playground.chargetrip.com/) | [Docs](https://developers.chargetrip.com/API-Reference/API/introduction)
| CommerceTools | e-commerce solutions | [Try it!](https://impex.commercetools.com/graphiql) | [Docs](https://docs.commercetools.com/graphql-api)
| Contentful | "CMS as a Service". Graph*i*QL demo allows to query a simple blog, but the library itself generates a schema automatically for any content model you store in Contentful. | [Try it!](https://graphql.contentful.com/content/v1/spaces/f8bqpb154z8p/explore?access_token=9d5de88248563ebc0d2ad688d0473f56fcd31c600e419d6c8962f6aed0150599&query=%7B%0A%20%20lessonCollection(where%3A%20%7B%20%0A%09%09OR%3A%20%5B%0A%09%09%09%7B%20title_contains%3A%20%22content%22%20%7D%2C%0A%09%09%09%7B%20title_contains%3A%20%22SDK%22%20%7D%0A%09%09%5D%0A%20%20%7D)%20%7B%0A%20%20%20%20items%20%7B%0A%20%20%20%20%20%20title%0A%20%20%20%20%20%20slug%0A%20%20%20%20%20%20modulesCollection(limit%3A%202%2C%20skip%3A%201)%20%7B%0A%20%20%20%20%20%20%20%20total%0A%09%09%09%09limit%0A%09%09%09%09skip%0A%20%20%20%20%20%20%20%20items%20%7B%0A%20%20%20%20%20%20%20%20%20%20...imageUrl%0A%09%09%09%09%09...%20on%20LessonCodeSnippets%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20...%20on%20LessonCopy%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20sys%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20id%0A%20%20%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A%0Afragment%20imageUrl%20on%20LessonImage%20%7B%0A%20%20title%0A%20%20image%20%7B%0A%20%20%20%20url%0A%20%20%7D%0A%7D) | [Docs](https://www.contentful.com/developers/docs/tutorials/general/graphql/)
| Countries | Information about countries, continents, and languages, based on [Countries List](https://annexare.github.io/Countries/) | [Try it!](https://countries.trevorblades.com) | [Repo](https://github.com/trevorblades/countries)
| EAN-Search | Search barcodes and products | [Try it!](https://api.ean-search.org/graphql) | [Docs](https://www.ean-search.org/blog/graphql-ean-api.html)
| EHRI | Holocaust-related archival materials | [Try it!](https://portal.ehri-project.eu/api/graphql/ui) | [Docs](https://portal.ehri-project.eu/api/graphql)
| EtMDB | Ethiopian Movie Database | [Try it!](https://etmdb.com/graphql?query=%7B%0A%20%20allCinemaDetails(before%3A%20%222017-10-04%22%2C%20after%3A%20%222010-01-01%22)%20%7B%0A%20%20%20%20edges%20%7B%0A%20%20%20%20%20%20node%20%7B%0A%20%20%20%20%20%20%20%20slug%0A%20%20%20%20%20%20%20%20hallName%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D%0A) | [Docs](https://etmdb.com/api/docs/)
| FaunaDB | Serverless GraphQL Database | [Try it!](https://fauna.com/blog/try-faunadbs-graphql-api) | [Docs](https://docs.fauna.com/fauna/current/graphql)
| GitHub | Web-based Git repository hosting service | [Try it!](https://developer.github.com/v4/explorer/) | [Docs](https://docs.github.com/v4/)
| GitLab | Host-your-own Git repository hosting service | [Try it!](https://gitlab.com/-/graphql-explorer) | [Docs](https://docs.gitlab.com/ee/api/graphql/)
| GraphLoc  | Find a geolocation of an IP address including latitude, longitude, city, country, time zone and area code. Free to use, SSL supported | [Try it!](https://graphloc.com) | [Docs](https://www.graphloc.com)
| HIVDB | A curated database to represent, store and analyze HIV drug resistance data | [Try it!](https://hivdb.stanford.edu/page/graphiql/) | [Docs](https://hivdb.stanford.edu/page/webservice/)
| Idobata | Dedicated chat for team development. | [Try it!](https://idobata.io/api) | |
| leanIX | Tools for business strategy | | [Docs](https://dev.leanix.net/docs/graphql-api)
| Pipefy | The operations excellence platform. | [Try it!](https://app.pipefy.com/graphiql) | [Docs](https://developers.pipefy.com) |
| Mattermark | Business research and networking | | [Docs](https://developer.mattermark.com/docs/graphql)
| Memair | Quantified self / extended mind platform | [Try it!](https://memair.com/graphiql) | [Docs](https://docs.memair.com)
| React Finland | React Finland API is built with conferences and meetups in mind | [Try it!](https://api.react-finland.fi/graphql) | [Repo](https://github.com/ReactFinland/graphql-api)
| Shopify Storefront | The Storefront API gives you full creative control to build customized purchasing experiences for your customers. | [Try it!](https://help.shopify.com/api/storefront-graphiql) | [Docs](https://help.shopify.com/api/storefront-api)<br>[Examples](https://github.com/Shopify/storefront-api-examples)
| Shopify Admin | The Admin API is the primary way that apps and services interact with Shopify. | [Try it!](https://shopify-graphiql-app.shopifycloud.com/login) | [Docs](https://shopify.dev/docs/admin-api/graphql/reference)
| SWOP | GraphQL and REST foreign exchange rate API. Note: Required registration. | [Try it!](https://swop.cx/) | [Docs](https://swop.cx/documentation)
| Universe |  Check what your friends are doing & find unique events near you using our filter. | [Try it!](https://www.universe.com/graphiql) | [Docs](https://developers.universe.com/docs/graphql)
| Yelp  | User Reviews and Recommendations of Top Restaurants, Shopping, Nightlife, Entertainment, Services and More | [Try it!](https://www.yelp.com/developers/graphiql) | [Docs](https://www.yelp.com/developers/graphql/guides/intro)
| TravelgateX | The global marketplace for the travel trade | [Try it!](https://api.travelgatex.com/) | [Docs](https://docs.travelgatex.com/getting-started/)
| TCGdex | A Multilanguage Pokémon TCG Database with Cards Pictures and most of the informations contained on the cards. | [Try it!](https://api.tcgdex.net/v2/graphql) | [Repo](https://github.com/tcgdex/cards-database)

## Unofficial API proxies

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| Barcelona Urban Mobility API | Information about the different public transport / urban mobility services of Barcelona | [Try it!](https://barcelona-urban-mobility-graphql-api.netlify.app/graphql) | [Repo](https://github.com/aalises/barcelona-urban-mobility-graphql-api)
| Favware's GraphQL Pokémon | Query for all the Pokémon, and their abilities, moves, items, learnsets, and type matchups from generations 1 through 8. This API strives to always stay up-to-date with new Pokémon releases, and has multiple contributors to achieve this. | [Try it!](https://graphqlpokemon.favware.tech) | [Repo](https://github.com/favware/graphql-pokemon)|
| Spacex Land | A non official platform for SpaceX's data! | [Try it!](https://api.spacex.land/graphql/) | [Docs](https://spacex.land/)
| Stratz | Dota 2 Statistics Api | [Try it!](https://api.stratz.com/graphiql/) | [Site](https://stratz.com/welcome)
| SWAPI | Star Wars API | [Try it!](https://graphql.org/swapi-graphql/) | [Repo](https://github.com/graphql/swapi-graphql)
| TMDB | The Movie Database Wrapper | [Try it!](https://tmdb.apps.quintero.io/) | [Repo](https://github.com/nerdsupremacist/tmdb)


## Demonstration-only APIs

| API | Description | Graph*i*QL | Docs/Repo
| --- | ----------- | :--------: | :-: |
| Lucas Bento's GraphQL Pokémon | Get information of a Pokémon with GraphQL! (**Note**: Only has data on Generation 1, and only has data on Pokémon!) | [Try it!](https://react-relay-pokemon.now.sh/#/) | [Repo](https://github.com/lucasbento/graphql-pokemon)<br>[ClientRepo](https://github.com/lucasbento/react-relay-pokemon)
| MongoDB Northwind demo | [Demo App](https://nodkz.github.io/relay-northwind/) build on top of [graphql-compose](https://github.com/nodkz/graphql-compose) and [mongoose](https://github.com/Automattic/mongoose) | [Try Relay version!](https://nodkz.github.io/relay-northwind/) | [Docs](https://github.com/nodkz/graphql-compose)<br>[ServerRepo](https://github.com/nodkz/graphql-compose-examples)<br>[ClientRepo](https://github.com/nodkz/relay-northwind-app)
| Three.js demo | Declare a Three.js program with GraphQL | [Try it!](https://jwerle.github.io/three.graphql/) | [Repo](https://github.com/jwerle/three.graphql)
| FakeQL | GraphQL API mocking as a service. | [Try it!](https://fakeql.com/) | [Docs](https://www.blowson.com/docs/)
| The Rick and Morty API | All the Rick and Morty information. | [Try it!](https://rickandmortyapi.com/graphql) | [Docs](https://rickandmortyapi.com/documentation/#graphql)
| Fake GraphQL API | Mock user and to do data | [Try it!](https://mocki.io/graphql) | [Docs](https://mocki.io/docs)
| Fruits API | Information of fruit trees of the world | [Try it!](https://fruits-api.netlify.app/graphql) | [Docs](https://github.com/Franqsanz/fruits-api/blob/main/readme.md)
