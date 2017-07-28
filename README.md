# facet-panel

A Polymer Element containing a group of facet-lists and date-range-facets.

### Example
```html
<facet-panel
    domain="[[domain]]"
    facets-query="[[facetsQuery]]"
    search-keys="[[searchKeys]]"
    process-request="{{processRequest}}"
    search-endpoint="[[searchEndpoint]]"
    search-fields="[[searchFields]]"
    search-parameters="{{searchParameters}}">
</facet-panel>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

