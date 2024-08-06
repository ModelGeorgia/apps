[Footprint Builder](/io/template)
# Community Footprints

View our latest [OpenFootprint Data Panels](/openfootprint)

## About zip code (ZCTA) Impacts

Fork our fork from [https://github.com/modelearth/ZCTAImpacts](https://github.com/modelearth/ZCTAImpacts).

The parent repo is at [https://github.com/abrie/ZCTAImpacts](https://github.com/abrie/ZCTAImpacts).  The [ZCTAImpacts Demo](https://zctaimpacts.abrie.dev) is not running a secure cert, so it may not be accessible. It loads slowly, so revisions are needed for loading the data.

You can run the demo on your local computer after downloading 220MB of data from the County Business Patterns API.

Let's figure out how to point the app at our static files instead.

**Innovation**

The app provides a simple search interface. Users are able to search by state, county, or zipcode and get an overview of the area's environmental impact. The overview is presented as a ["Nutrition Label"](https://model.earth/io/template/), indicating its contribution to the ["metabolism of the anthroposphere"](https://en.wikipedia.org/wiki/Anthropogenic_metabolism)

**Implementation**

The app fuses the EPA's USEEIO v2 to US Census Business Patterns through a searchable interface. It uses a React frontend and a Python backend.

**Integration**

The app provides a JSON API for querying the aggregated community totals. It's the same API used to generate the nutritional labels. Consumers of the API could use the data to generate a more compelling label, rank a set of communities, or measure local environmental trends over time.




