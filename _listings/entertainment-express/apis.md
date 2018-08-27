---
name: Entertainment Express
x-slug: entertainment-express
description: Internet Video Archive (IVA) is a leading entertainment data company
  providing metadata, images and trailers/clips, for movie and TV content. With the
  launch of its award-winning Entertainment Express APIs, clients can easily access
  everything they need to create engaging content discovery experiences. By using
  Entertainment Express, clients can also connect to other services like movie showtimes
  and ticketing, content recommendations, content availability and TV channel line-ups.
  With over a million titles, episodes and over 150,000 videos available, IVA makes
  it easy for developers to integrate all the services they need at a very affordable
  price.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Common
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/apis.md
specificationVersion: "0.14"
apis:
- name: Entertainment Express - Paged list of companies.
  x-api-slug: commoncompanies-get
  description: 'Companies are listed in a movie, show, or game response as those whom
    are involved with the program.  EX: Universal Pictures.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commoncompanies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commoncompanies-get-openapi.md
- name: Entertainment Express - Returns a list of countries.
  x-api-slug: commoncountries-get
  description: List of Countries, ISO codes and Country IDs used throughout the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commoncountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commoncountries-get-openapi.md
- name: Entertainment Express - List of image types contained in the database.
  x-api-slug: commonimagetypes-get
  description: 'A list of image types available in the IVA database. **EX: Poster**'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commonimagetypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commonimagetypes-get-openapi.md
- name: Entertainment Express - Gets all languages.
  x-api-slug: commonlanguages-get
  description: Returns a list of languages used in the API as well as the ISO code
    and language ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commonlanguages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commonlanguages-get-openapi.md
- name: Entertainment Express - Gets all tags.
  x-api-slug: commontags-get
  description: Paged list of all tags used in the API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commontags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commontags-get-openapi.md
- name: Entertainment Express - Gets all VideoTypes.
  x-api-slug: commonvideotypes-get
  description: Returns a list of the types of videos that can be associated to a title.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IVA-logo.png
  humanURL: https://www.internetvideoarchive.com/
  baseURL: https://ee.iva-api.com//
  tags: Celebrities, Movies, General Data, Televisions, Videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commonvideotypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/common/master/_listings/entertainment-express/commonvideotypes-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://emuseum.api.docs.api.gallery.streamdata.io
- type: x-api-stack
  url: http://entertainment.express.stack.network
- type: x-blog
  url: https://www.internetvideoarchive.com/blog/
- type: x-developer
  url: https://developer.iva-api.com/
- type: x-pricing
  url: https://www.internetvideoarchive.com/pricing/
- type: x-website
  url: https://www.internetvideoarchive.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---