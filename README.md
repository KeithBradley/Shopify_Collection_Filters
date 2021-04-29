# Shopify Collection Product Tag Filters

Shopify  **Product Tag Filters** for collection pages.

## Setup

1. Copy the file to the snippets directory ```snippets/collection-filters-grouped.liquid```
2. Include on your ```collection.liquid``` template ```{% include 'collection-filters-grouped' %}```

Product tag naming convension needs to be 'FilterName__FilterValue' (Double underscore)

E.g. ```Brand__Nike``` or ```Size__Small```

Note that there is no css included with the snippet. It's been designed to work with Bootstrap 4 

Inspired/Adapted from https://gist.github.com/darryn/8047749

![GITHUB__Shopify-Filters](https://user-images.githubusercontent.com/390332/111279941-265cc480-8633-11eb-8987-41daf95f175a.gif)
